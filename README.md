# Guide d'enregistrement d'écran pour la Salle de Briefing

[![Discord SdB](https://img.shields.io/discord/258541615017099264.svg?label=Discord&logo=Discord&colorB=7289da&style=for-the-badge)](https://discord.gg/sdb)

## ⚠ Guide en cour de conception, c'est une ébauche sans travail de relecture

### Dans ce guide vous trouverais une aide complète pour faire des clip de vos sessions en jeu
_Penser a cliquer sur cette iconne pour faire dérouler le texte quand elle est présente : `▶`_

Nous n'allons pas vous présenter tout les logiciels, seulement les plus simple a prendre en main :

- [Geforce Experience](#geforce-experience)
- [Radeon ReLive](#radeon-relive)
- [Seelseries moments](#seelseries-moments)
- [Medal](#medal)
- [Outplayed](#outplayed)
- [OBS](#obs)

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
  🔻 Aucune option d'édition pour vos clips vidéo
  🔻 Les pc portable sont obliger d'être en jeux pour enregistrer
  🔻 Limité uniquement aux carte graphique Nvidia
  🔻 Prend les performances sur la carte graphique
  ```

- Radeon ReLive :
	*Ne possédant pas de carte graphique amd, cette partie du guide n'est pour le moment pas réalisable, navré pour la gêne.*

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
  🟢 Quelques outils basiques pour l'édition de vos clips vidéo
  🔻 Limiter a enregistrer les 20 dernières minutes maximum, ne permet pas de faire d'enregistrement d'écran classique
  🔻 Prend les performances sur la mémoire
  ```

- Medal:

  ```
  🟢 En une touche enregistre les X dernières minutes
  🟢 Capture en qualitée élevée
  🟢 En un click fournis un lien pour voir le clip en ligne
  🟢 Quelques outils basiques pour l'édition de vos clips vidéo
  🔻 Possède des pubs
  🔻 Prend les performances sur le processeur ou sur la carte graphique (au choix)
  ```

- Outplayed:
  ```
  🟢 En une touche enregistre les X dernières minutes
  🟢 Capture en qualitée élevée
  🟢 En un click fournis un lien pour voir le clip en ligne
  🟢 Quelques outils basiques pour l'édition de vos clips vidéo
  🔻 Possède des pubs
  🔻 S'installe uniquement avec Overwolf, donc un logiciel en plus qui tourne sur le pc
  🔻 Prend les performances sur le processeur ou sur la carte graphique (au choix)
  ```

- OBS:

  ```
  🟢 Capture en qualitée élevée
  🟢 Permet de stream et de mettre en ligne les vidéos sur youtube (et autre) facilement
  🔻 Prise en main moins simple
  🔻 Aucune option d'édition pour vos clips vidéo
  🔻 Ne possède pas de fonctionalité pour enregistrer les X dernières minutes
  🔻 Prend de grosses performances sur le processeur
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
>
> [`OBS`](#obs) est très bien pour stream, pour de l'enregsitrement vidéo, beaucoup moins...

## Guide d'installation, configuration et d'utilisation

### Geforce Experience

<details>
  <summary>Installation</summary>

- Pour commencer télécharger l'installeur[ici.](https://www.nvidia.com/fr-fr/geforce/geforce-experience/)
`https://www.nvidia.com/fr-fr/geforce/geforce-experience/`

- Une fois installé et connecté à GeForce Experience, vous pouvez activer la superposition en jeu si ce n'est pas déjà fait :
![Superposition en jeu](https://i.imgur.com/tOXaiWt.png)

> ❗ par ailleurs dans la section `pilotes` vous pouvez mettre a jour votre carte graphique Nvidia

</details>

<details>
  <summary>Configuration</summary>

- Pour acceder au pannel il vous suffit de faire `Alt+z`
![Présentation de l'overlay](https://i.imgur.com/lHEYzUW.png)

- L'engrange a droite vous permet d'accèder aux options : 

1. Raccorucis claiver >
Vous pouvez changer pour commencer le raccourcis pour ouvrir l'interfce superposée, `Alt+z` peut être préssé pendant vos session de jeux sans vouloir forcément ouvrir cette interface.
Vous pouvez également prendre connaissance des autres racourcis.
La partie intéréssante est `Enregistrement`:
![Raccourcis clavier](https://i.imgur.com/vbRNzsh.png) 

1. Enregistrements >
Ici vous pouvez définir dans quel dossier enregistrer vos vidéos. 

1. Capture vidéo >
Ici vous allez pouvoir choisir la durée de vos clips (enregitrer les X dernières minutes au moment d'appuyer sur `Alt+F10`)
Et définir qualité de vos enregistrement, plus la qualitée est élevée, plus votre enregistrement prendra des performances et votre clip de la place sur vote pc.
![Capture vidéo](https://i.imgur.com/xSu9K3h.png) 

1. Contôle de la confidentialité _(Uniquement sur pc fixe)_ >
Permet d'enregistrer votre écran totalement, et ne se limite pas a votre jeux

</details>

<details>
  <summary>Utilisation</summary>

Pour l'ancer l'enregistrement une fois en jeu pour avez seulement a lancer le replay instantané via le menu `Alt+z` ou avec le raccourci `Alt+Shift+F10`
Puis, en jeu quand vous voulez enregistrer les X dernières minutes, faire `Alt+F10`
Vous retrouverais vos clips dans le dossier que vous avez défini dans les options d'enregistrement. Par défaut, il se trouve dans `C:\Users\{leNomDeVotrePc}\Videos\`

![Enregistrement](https://i.imgur.com/L6Ccv9v.png)

</details>

---

### Radeon ReLive
*Ne possédant pas de carte graphique amd, cette partie du guide n'est pour le moment pas réalisable, navré pour la gêne.*
<details>
  <summary>Installation</summary>
</details>
<details>
  <summary>Configuration</summary>
</details>
<details>
  <summary>Utilisation</summary>
</details>

---

### Seelseries Moments

<details>
  <summary>Installation</summary>

- Pour commencer télécharger l'installeur [ici.](https://fr.steelseries.com/gg/moments)
`https://fr.steelseries.com/gg/moments`

- Une fois installé et connecté à Steelseries vous pouvez activer `Moments` si ce n'est pas déjà fait:
![Capture en jeu](https://i.imgur.com/x1ExAgV.png)
> ❗ Depuis ce menu vous avez accès a toutes les options baisques, changement de qualité, le racourcis pour enregistrer, et autres.

</details>
<details>
  <summary>Configuration</summary>

Pour accéder aux options vous avez les praramètres en bas a gauche, puis tout en bas vous avez les options pour `Moments`

- `Capture et audio` >
	Vous avez quelques options très sommaires, nous vous laissons les découvrir.

- `Paramètres de clip` > 
	Vous pouvez définir la durée de vos clips, la qualité de vos clips, et l'emlplacement de sauvgarde.
	Attention, plus la qualité est élevée, plus la mémoire de votre pc sera utiliser.
	![Paramètres de clip](https://i.imgur.com/d5kYXAq.png)

- `Détection des jeux` >
	Si au lancement du jeu, moments ne vous propose pas de lancer l'enregistrement, vous pouvez ajouter manuellement vos jeux ici.

	> ❗ Moments vous propose d'enregistrer de 2 manières différentes, soit la capture du jeu ou de l'écran, si vous prenez la capture de jeu, l'enregistrment se limitera a votre jeu et au son de votre jeu, si vous prenez la capture d'écran, les sons tel que discord ou autre serons enregistrer également.
	> ![Mode d'enregistrement](https://i.imgur.com/7LEzvMr.png)

</details>

<details>
  <summary>Utilisation</summary>

En jeu, normalement vous devriez recevoir une notification pour vous dire que `Moments` est prêt a enregistrer
![Notification](https://i.imgur.com/Hd2X3Tj.png)
> Si ce n'est pas le cas, ne paniquez pas, parfois `Moments` a du mal avec les noficiations, vous le verrais avec la notification bleue en bas a droite de votre barre des tâches sur l'application `Steelseries`
> 
> ![Notification](https://i.imgur.com/QFPB9gU.png)

Une fois l'enregistrement fait vous pouvez le retrouver dans l'onglet `Moments` de l'apllcation `Steelseries`
Depuis ce menu vous pouvez éditer votre clip, le partager, ou le supprimer.
> Si vous partagez votre clip avec le bouton `Partager le clip`, un watermark sera présent sur votre clip, si vous partagez votre clip avec le bouton `Exporter`, il n'y aura pas de watermark. 

https://github.com/Hrodvitnir-Fenrir/SdB_Record_Guide/assets/44929201/9b34e878-4c5f-48dc-92ac-36426fb555a1

</details>

---

### Medal

<details>
  <summary>Installation</summary>

- Pour commencer télécharger l'installeur [ici.](https://medal.tv/fr)
`https://medal.tv/fr`

- Une fois installé et connecté a Medal, tout devrais être fonctionnel
![Menu Medal](https://i.imgur.com/7gzAmLo.png)

</details>
<details>
  <summary>Configuration</summary>

Pour accéder aux options vous avez l'engrenage en bas a gauche de l'application

`Audio et caméra` >
	Ici vous pouvez définir ce que vous voulez enregistrer, entre uniquement le son du jeu, ou le son de votre pc (musique, discord, etc)
	Ainsi que les options pour votre micro

`Clip et enregistrements` >

1. `Enregistrement général` >
	Ici vous pouvez définir le temps du clip.
	> (c'est a dire au moment ou vous cliquerais sur le racourcis cela enregistrera les X dernières minutes)

	Ainsi que le raccourcis pour enregistrer
	> Tu peux également définir plusieurs raccourcis pour enregistrer des clips de différentes durées

	![Exemple de raccourcis](https://i.imgur.com/eLYKH11.png)

2. `Qualité` >
   	Ici vous pouvez définir la qualité de vos clips, plus la qualité est élevée, plus les performances de votre pc seront sollicitées ainsi que la taille du clip.
	Vous pouvez également choisir si vous voulez que cela sois votre processeur (`CPU`) ou votre carte graphique (`GPU`) qui sois solliciter pour enregistrer.

	![Exemple qualité](https://i.imgur.com/JFhGuMR.png)

3. `Enregsitrement intégral` >
	Par défaut cela lance un enregistrement pour toute la session de jeu 
	*(du moment qu'il est lancé a sa fermeture)*

	> ❗ Attention a la place que cela prend sur le disque !

4. `Stockage` >
	Vous pouvez définir une taille maximale d'enregistrement, cela supprimera les clips les plus anciens pour faire de la place pour les nouveaux.
	Vous pouvez également définir l'emplacement de sauvegarde de vos clips.

	![Exemple stockage](https://i.imgur.com/9fgGyuc.png)

</details>
<details>
  <summary>Utilisation</summary>

En jeu, normalement vous devriez recevoir une notification pour vous dire que `Medal` est prêt a enregistrer ou directement depuis le menu medal

![Notification](https://i.imgur.com/ugsLrss.png)

Une fois l'enregistrement fait vous pouvez le retrouver dans l'onglet `Library` de l'apllcation `Medal`
Vous pouvez ensuite éditer le clip, créé un lien pour le partager, ou le supprimer.

https://github.com/Hrodvitnir-Fenrir/SdB_Record_Guide/assets/44929201/ac9d8b7c-3f55-4849-a72b-434e59439e45

</details>

---

### Outplayed
*En cours de rédaction*
<details>
  <summary>Installation</summary>
</details>
<details>
  <summary>Configuration</summary>
</details>
<details>
  <summary>Utilisation</summary>
  
</details>

---

### OBS
*En cours de rédaction*
<details>
  <summary>Installation</summary>
</details>
<details>
  <summary>Configuration</summary>
</details>
<details>
  <summary>Utilisation</summary>
  
</details>

---

## Performances

<details>
  <summary>Comment choisir un logiciel selon les ressources du pc</summary>

Nous vous invitons lancer une partie avec le gestionaire des taches en fond sur l'ongelt `performance` pour voir ce que votre pc consomme le plus.
Dépendament des résultats, vous pouvez choisir un logiciel qui peux prendre les ressources qui sont le moins sollicitées.
> ![Gestionnaire des taches](https://i.imgur.com/t1jrgAX.png)
> 
> Dans cet exemple la mémoire est très peu sollicitée, ainsi que le processeur, donc `Seelseries moments` est un bon choix. Sinon `Medal` et `Outplayed` sont également de bon choix. Sinon si la carte graphique était peu sollicitée, `Geforce Experience` ou `Radeon ReLive` aurait été un bon choix.

</details>

___

##### _Merci pour votre lecture, si jamais vous avez des suggestions, nhésitez pas a nous en faire part via le bot `Opérateur SdB` sur le serveur_<br>Le bô esprit, le bô jeu.

[![logo](https://raw.githubusercontent.com/MrLixm/Sdb.branding/main/brand/header/twitter/variantB/SdB.header.twitter.master.png)](https://discord.gg/sdb)
