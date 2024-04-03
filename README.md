# Guide d'enregistrement d'écran pour la Salle de Briefing

[![Discord SdB](https://img.shields.io/discord/258541615017099264.svg?label=Discord&logo=Discord&colorB=7289da&style=for-the-badge)](https://discord.gg/sdb)

## ⚠ Guide en cour de conception, c'est une ébauche sans travail de relecture

### Dans ce guide vous trouverais une aide complète pour faire des clip de vos sessions en jeu

_Penser a cliquer sur cette iconne pour faire dérouler le texte quand elle est présente : `▶`_

Nous n'allons pas vous présenter tout les logiciels, seulement les plus simple a prendre en main :

- [Geforce Experience](https://www.nvidia.com/fr-fr/geforce/geforce-experience/)
- [Radeon ReLive](https://www.amd.com/fr/support/kb/faq/relive-install)
- [Seelseries moments](https://fr.steelseries.com/gg/moments)
- [Medal](https://medal.tv/fr)
- [Outplayed](https://go.overwolf.com/outplayed/)

> [!CAUTION]
> Enregistrer son écran prend des performances sur votre système quoi qu'il arrive. Cependant, chaque logiciels d'enregistrement n'utilise pas les même ressources de votre pc.
> Nous vous invitons du coup à regarder ce que votre pc consomme le moins pendant vos session de jeux, et de choisir en dépend le logiciel si votre appareil a des performances limitées
>
> Plus d'informations [ici](#performances).

## Avantages et inconvénient

<details>
	<summary>Oui mais du coup, le quel choisir ?</summary>

- Geforce Experience :

  ```
  🟢 En une touche enregistre les X dernières minutes
  🟢 Capture en qualitée élevée
  🟢 Permet de stream et de mettre en ligne les vidéos sur youtube (et autre) facilement
  🔻 Les pc portable sont obliger d'être en jeux pour enregistrer
  🔻 Limité uniquement aux carte graphique Nvidia
  🔻 Prend les performances sur la carte graphique
  ```

- Radeon ReLive (WIP ⚠):

  ```
  🔻 Limité uniquement aux carte graphique Amd
  🔻 Prend les performances sur la carte graphique
  ```

- Seelseries moments :

  ```
  🟢 En une touche enregistre les X dernières minutes
  🟢 Capture en qualitée élevée
  🟢 Permet  de mettre en ligne les vidéos sur youtube (et autre) facilement
  🟢 Peux compresser la vidéo pour la partager sur discord sans nitro (ou avec)
  🔻 Limiter a enregistrer les 20 dernières minutes maximum, ne permet pas de faire d'enregistrement d'écran classique
  🔻 Prend les performances sur la mémoire
  ```

- Medal:

  ```
  🟢 En une touche enregistre les X dernières minutes
  🟢 Capture en qualitée élevée
  🟢 En un click fournis un lien pour voir le clip en ligne
  🔻 Possède des pubs
  🔻 Prend les performances sur le processeur ou sur la carte graphique (au choix)
  ```

- Outplayed:
  ```
  🟢 En une touche enregistre les X dernières minutes
  🟢 Capture en qualitée élevée
  🟢 En un click fournis un lien pour voir le clip en ligne
  🔻 Possède des pubs
  🔻 S'installe uniquement avec Overwolf, donc un logiciel en plus qui tourne sur le pc
  🔻 Prend les performances sur le processeur ou sur la carte graphique (au choix)
  ```

</details>

> [!TIP]
> En résumé :
>
> Si vous possédez une grosse carte graphique, passez directement par le logiciel de votre carte graphique [`Geforce Experience`](#geforce-experience) ou [`Radeon ReLive`](#radeon-relive). Le logiciel est nécéssaire pour mettre a jour votre carte graphique également, donc d'une pierre deux coup.
>
> Si vous possédez un gros processeur , privilégiez plutôt [`Medal`](#medal) ou [`Outplayed`](#outplayed) pour forcer l'enregistrement sur votre processeur.
>
> Sinon, [`Seelseries moments`](#seelseries-moments) est une bonne alternative, en utilisant la ram, généralement peu utiliser sur les jeux, et surtout a très peu d'impact sur les performances.

## Guide d'installation, configuration et d'utilisation

### Geforce Experience

<details>
  <summary>Installation</summary>
  	<ul>
		<li>
  			Pour commencer télécharger l'installeur <a href="https://www.nvidia.com/fr-fr/geforce/geforce-experience/">ici.</a>
			<br>
			(<code>https://www.nvidia.com/fr-fr/geforce/geforce-experience/</code>)
		</li>
    	<li>
			Une fois installé et connecté à GeForce Experience, vous pouvez activer la superposition en jeu si ce n'est pas déjà fait :
      		<br>
      		<img src="https://i.imgur.com/tOXaiWt.png" alt="Superposition en jeu">
			<br>
			<blockquote style="font-style: italic;">par ailleurs dans la section <code>pilotes</code> vous pouvez mettre a jour votre carte graphique Nvidia.</blockquote>
    	</li>
  	</ul>
</details>
<details>
  <summary>Configuration</summary>
	<ul>
		<li>
			Pour acceder au pannel il vous suffit de faire <code>Alt+z</code> <br>
			<img src="https://i.imgur.com/lHEYzUW.png" alt="Présentation de l'overlay">
		</li>
		<li>
			Si vous cliquez sur l'engrenage pour les options, vous allez pouvoir modifier certaines choses a votre convenance :
			<ol start="1">
			<li>
			Raccorucis claiver > <br> Vous pouvez changer pour commencer le raccourcis pour ouvrir l'interfce superposée, <code>Alt+z</code> peut être préssé pendant vos session de jeux sans vouloir forcément ouvrir cette interface.<br>Vous pouvez également prendre connaissance des autres racourcis.<br>La partie intéréssante est <code>Enregistrement</code>:
						<img src="https://i.imgur.com/vbRNzsh.png" alt="Enregistrement">
			</li>
			<li>
			Enregistrements ><br>Ici vous pouvez définir dans quel dossier enregistrer vos vidéos.
			</li>
			<li>
			Capture vidéo ><br>Ici vous allez pouvoir choisir la durée de vos clips (enregitrer les X dernières minutes au moment d'appuyer sur <code>Alt+F10</code>).<br>La qualité de vos enregistrement, plus la qualitée est élevée, plus votre enregistrement prendra des performances et votre clip de la place sur vote pc.
									<img src="https://i.imgur.com/xSu9K3h.png" alt="Enregistrement">
			</li>
			<li>
			Contôle de la confidentialité <span style="font-style: italic;">(Uniquement sur pc fixe)</span> > <br>Permet d'enregistrer votre écran totalement, et ne se limite pas a votre jeux
			</li>
			</ol> 
		</li>
</details>
<details>
  <summary>Utilisation</summary>
		Pour l'ancer l'enregistrement une fois en jeu pour avez seulement a lancer le replay instantané via le menu <code>Alt+z</code> ou avec le raccourci <code>Alt+Shift+F10</code>
		<br>
		Puis, en jeu quand vous voulez enregistrer les X dernières minutes, faire <code>Alt+F10</code> 
		<br>
		<img src="https://i.imgur.com/L6Ccv9v.png" alt="Enregistrement">
</details>

---

### Radeon ReLive

<details>
  <summary>Installation</summary>
</details>
<details>
  <summary>Configuration</summary>
</details>
<details>
  <summary>Utilisation ?</summary>
  
</details>

---

## Seelseries Moments

<details>
  <summary>Installation</summary>
</details>
<details>
  <summary>Configuration</summary>
</details>
<details>
  <summary>Utilisation ?</summary>
  
</details>

---

### Medal

<details>
  <summary>Installation</summary>
</details>
<details>
  <summary>Configuration</summary>
</details>
<details>
  <summary>Utilisation ?</summary>
  
</details>

---

### Outplayed

<details>
  <summary>Installation</summary>
</details>
<details>
  <summary>Configuration</summary>
</details>
<details>
  <summary>Utilisation ?</summary>
  
</details>

---

## Performances

<details>
  <summary>Comment choisir un logiciel selon les ressources du pc</summary>
    <blockquote>heyyy</blockquote>

</details>

##### _Merci pour votre lecture, si jamais vous avez des suggestions, nhésitez pas a nous en faire part via le bot `Opérateur SdB` sur le serveur_<br/>Le bô esprit, le bô jeu.

[![logo](https://raw.githubusercontent.com/MrLixm/Sdb.branding/main/brand/header/twitter/variantB/SdB.header.twitter.master.png)](https://discord.gg/sdb)
