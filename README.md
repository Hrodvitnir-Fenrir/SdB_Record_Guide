# Guide d'enregistrement d'écran pour la Salle de Briefing

[![Discord SdB](https://img.shields.io/discord/258541615017099264.svg?label=Discord&logo=Discord&colorB=7289da&style=for-the-badge)](https://discord.gg/sdb)

## ⚠ Guide en cours de conception, c'est une ébauche sans travail de relecture

### Dans ce guide vous trouverez une aide complète pour faire des clips de vos sessions de jeu
_Pensez à cliquer sur cette iconne pour faire dérouler le texte quand elle est présente : `▶`_

Nous n'allons pas vous présenter tous les logiciels, seulement les plus simples à prendre en main :

- [Geforce Experience](#geforce-experience)
- [Radeon ReLive](#radeon-relive)
- [Seelseries moments](#seelseries-moments)
- [Medal](#medal)
- [Outplayed](#outplayed)
- [OBS](#obs)

> [!CAUTION]
> Enregistrer son écran prend des performances sur votre système quoi qu'il arrive. Cependant, chaque logiciel d'enregistrement n'utilise pas les mêmes ressources de votre pc.
> Nous vous invitons du coup à regarder ce que votre pc consomme le moins pendant vos sessions de jeux, et de choisir en fonction le logiciel si votre appareil a des performances limitées
>
> Plus d'informations [ici](#performances).

## Avantages et inconvénients

<details>
	<summary>Oui mais du coup, lequel choisir ?</summary>

- Geforce Experience :

  ```
  🟢 En une touche, enregistre les X dernières minutes
  🟢 Capture en qualitée élevée
  🟢 Permet de stream et de mettre en ligne les vidéos sur youtube (et autres) facilement
  🔻 Aucune option d'édition pour vos clips vidéo
  🔻 Les pc portables sont obligés d'être en jeu pour enregistrer
  🔻 Limité uniquement aux cartes graphiques Nvidia
  🔻 Prend les performances sur la carte graphique
  ```

- Radeon ReLive :
	*Ne possédant pas de carte graphique amd, cette partie du guide n'est pour le moment pas réalisable, navré pour la gêne.*

  ```
  🔻 Limité uniquement aux cartes graphiques Amd
  🔻 Prend les performances sur la carte graphique
  ```

- Seelseries moments :

  ```
  🟢 En une touche, enregistre les X dernières minutes
  🟢 Capture en qualitée élevée
  🟢 Permet de mettre en ligne les vidéos sur youtube (et autre) facilement
  🟢 Peut compresser la vidéo pour la partager sur discord sans nitro (ou avec)
  🟢 Quelques outils basiques pour l'édition de vos clips vidéo
  🔻 Limité à enregistrer les 20 dernières minutes maximum, ne permet pas de faire d'enregistrement d'écran classique
  🔻 Prend les performances sur la mémoire
  ```

- Medal:

  ```
  🟢 En une touche, enregistre les X dernières minutes
  🟢 Capture en qualitée élevée
  🟢 En un clic, fournis un lien pour voir le clip en ligne
  🟢 Quelques outils basiques pour l'édition de vos clips vidéo
  🔻 Possède des pubs
  🔻 Prend les performances sur le processeur ou sur la carte graphique (au choix)
  ```

- Outplayed:
  ```
  🟢 En une touche, enregistre les X dernières minutes
  🟢 Capture en qualitée élevée
  🟢 En un clic, fournis un lien pour voir le clip en ligne
  🟢 Quelques outils basiques pour l'édition de vos clips vidéo
  🔻 Vous devez fermer votre jeu pour avoir accès à vos clips
  🔻 Possède des pubs
  🔻 S'installe uniquement avec Overwolf, donc un logiciel de plus qui tourne sur le pc
  🔻 Prend les performances sur le processeur ou sur la carte graphique (au choix)
  ```

- OBS:

  ```
  🟢 Capture en qualitée élevée
  🟢 Permet de stream et de mettre en ligne les vidéos sur youtube (et autre) facilement
  🔻 Prise en main moins simple
  🔻 Aucune option d'édition pour vos clips vidéo
  🔻 Ne possède pas de fonctionnalité pour enregistrer les X dernières minutes
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
> Sinon, [`Seelseries moments`](#seelseries-moments) est une bonne alternative, en utilisant la ram, généralement peu utilisée sur les jeux, et surtout a très peu d'impact sur les performances.
>
> [`OBS`](#obs) est très bien pour stream, pour de l'enregistrement vidéo, beaucoup moins...

## Guide d'installation, configuration et d'utilisation

### Geforce Experience

<details>
  <summary>Installation</summary>

- Pour commencer, téléchargez l'installeur [ici.](https://www.nvidia.com/fr-fr/geforce/geforce-experience/)
`https://www.nvidia.com/fr-fr/geforce/geforce-experience/`

- Une fois installé et connecté à GeForce Experience, vous pouvez activer la superposition en jeu si ce n'est pas déjà fait :
![Superposition en jeu](https://i.imgur.com/tOXaiWt.png)

> ❗ Par ailleurs, dans la section `pilotes` vous pouvez mettre à jour votre carte graphique Nvidia

</details>

<details>
  <summary>Configuration</summary>

- Pour acceder au pannel, il vous suffit de faire `Alt+z`
![Présentation de l'overlay](https://i.imgur.com/lHEYzUW.png)

- L'engrange à droite vous permet d'accéder aux options : 

1. Raccourcis claiver >
Pour commencer, vous pouvez changer le raccourci pour ouvrir l'interface superposée, `Alt+z` peut être préssé pendant vos sessions de jeu sans vouloir forcément ouvrir cette interface.
Vous pouvez également prendre connaissance des autres racourcis.
La partie intéréssante est `Enregistrement`:
![Raccourcis clavier](https://i.imgur.com/vbRNzsh.png) 

1. Enregistrement >
Ici vous pouvez définir dans quel dossier enregistrer vos vidéos. 

1. Capture vidéo >
Ici vous allez pouvoir choisir la durée de vos clips (enregitrer les X dernières minutes au moment d'appuyer sur `Alt+F10`)
Et définir la qualité de vos enregistrements; Plus la qualitée est élevée, plus votre enregistrement prendra des performances et votre clip de la place sur vote pc.
![Capture vidéo](https://i.imgur.com/xSu9K3h.png) 

1. Contrôle de la confidentialité _(Uniquement sur pc fixe)_ >
Permet d'enregistrer votre écran totalement, et ne se limite pas à votre jeux

</details>

<details>
  <summary>Utilisation</summary>

Pour lancer l'enregistrement une fois en jeu, vous avez seulement à lancer le replay instantané via le menu `Alt+z` ou avec le raccourci `Alt+Shift+F10`
Puis en jeu, quand vous voulez enregistrer les X dernières minutes, faites `Alt+F10`
Vous retrouverez vos clips dans le dossier que vous avez défini dans les options d'enregistrement. Par défaut, il se trouve dans `C:\Users\{leNomDeVotrePc}\Videos\`

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

- Pour commencer, téléchargez l'installeur [ici.](https://fr.steelseries.com/gg/moments)
`https://fr.steelseries.com/gg/moments`

- Une fois installé et connecté à Steelseries vous pouvez activer `Moments` si ce n'est pas déjà fait:
![Capture en jeu](https://i.imgur.com/x1ExAgV.png)
> ❗ Depuis ce menu, vous avez accès a toutes les options basiques, changement de qualité, racourci pour enregistrer, et autres.

</details>
<details>
  <summary>Configuration</summary>

Pour accéder aux options, vous avez les paramètres en bas à gauche, puis tout en bas vous avez les options pour `Moments`

- `Capture et audio` >
	Vous avez quelques options très sommaires, nous vous laissons les découvrir.

- `Paramètres de clip` > 
	Vous pouvez définir la durée de vos clips, la qualité de vos clips, et l'emplacement de sauvegarde.
	Attention, plus la qualité est élevée, plus la mémoire de votre pc sera utilisée.
	![Paramètres de clip](https://i.imgur.com/d5kYXAq.png)

- `Détection des jeux` >
	Si au lancement du jeu, moments ne vous propose pas de lancer l'enregistrement, vous pouvez ajouter manuellement vos jeux ici.

	> ❗ Moments vous propose d'enregistrer de 2 manières différentes, soit la capture du jeu ou de l'écran. Si vous prenez la capture de jeu, l'enregistrment se limitera à votre jeu et au son de votre jeu. Si vous prenez la capture d'écran, les sons tels que discord ou autres serons enregistrés également.
	> ![Mode d'enregistrement](https://i.imgur.com/7LEzvMr.png)

</details>

<details>
  <summary>Utilisation</summary>

En jeu, normalement vous devriez recevoir une notification pour vous dire que `Moments` est prêt à enregistrer
![Notification](https://i.imgur.com/Hd2X3Tj.png)
> Si ce n'est pas le cas, ne paniquez pas, parfois `Moments` a du mal avec les notifications, vous le verrez avec la notification bleue en bas à droite de votre barre des tâches sur l'application `Steelseries`
> 
> ![Notification](https://i.imgur.com/QFPB9gU.png)

Une fois l'enregistrement fait vous pouvez le retrouver dans l'onglet `Moments` de l'application `Steelseries`
Depuis ce menu, vous pouvez éditer votre clip, le partager, ou le supprimer.
> Si vous partagez votre clip avec le bouton `Partager le clip`, un watermark sera présent sur votre clip, si vous partagez votre clip avec le bouton `Exporter`, il n'y aura pas de watermark. 

https://github.com/Hrodvitnir-Fenrir/SdB_Record_Guide/assets/44929201/9b34e878-4c5f-48dc-92ac-36426fb555a1

</details>

---

### Medal

<details>
  <summary>Installation</summary>

- Pour commencer, téléchargez l'installeur [ici.](https://medal.tv/fr)
`https://medal.tv/fr`

- Une fois installé et connecté à Medal, tout devrait être fonctionnel.
![Menu Medal](https://i.imgur.com/7gzAmLo.png)

</details>
<details>
  <summary>Configuration</summary>

Pour accéder aux options, vous trouverez l'engrenage en bas à gauche de l'application

- `Audio et caméra` >
	Ici vous pouvez définir ce que vous voulez enregistrer, entre uniquement le son du jeu, ou le son de votre pc (musique, discord, etc)
	Ainsi que les options pour votre micro

- `Clip et enregistrements` >

  1. `Enregistrement général` >
	Ici vous pouvez définir le temps du clip.
	> (c'est à dire au moment ou vous cliquerez sur le racourci cela enregistrera les X dernières minutes)

	Ainsi que le raccourci pour enregistrer
	> Vous pouvez également définir plusieurs raccourcis pour enregistrer des clips de différentes durées

	![Exemple de raccourcis](https://i.imgur.com/eLYKH11.png)

  2. `Qualité` >
   	Ici vous pouvez définir la qualité de vos clips. Plus la qualité est élevée, plus les performances de votre pc seront sollicitées ainsi que la taille du clip.
	Vous pouvez également choisir si vous voulez que cela soit votre processeur (`CPU`) ou votre carte graphique (`GPU`) qui soit solliciter pour enregistrer.

	![Exemple qualité](https://i.imgur.com/JFhGuMR.png)

  3. `Enregistrement intégral` >
	Par défaut, cela lance un enregistrement pour toute la session de jeu 
	*(du moment qu'il est lancé à sa fermeture)*

	> ❗ Attention à la place que cela prend sur le disque dur !

  4. `Stockage` >
	Vous pouvez définir une taille maximale d'enregistrement, cela supprimera les clips les plus anciens pour faire de la place pour les nouveaux.
	Vous pouvez également définir l'emplacement de sauvegarde de vos clips.

	![Exemple stockage](https://i.imgur.com/9fgGyuc.png)

</details>
<details>
  <summary>Utilisation</summary>

En jeu, normalement vous devriez recevoir une notification pour vous dire que `Medal` est prêt à enregistrer ou directement depuis le menu medal

![Notification](https://i.imgur.com/ugsLrss.png)

Une fois l'enregistrement fait, vous pouvez le retrouver dans l'onglet `Library` de l'application `Medal`
Vous pouvez ensuite éditer le clip, créer un lien pour le partager, ou le supprimer.

https://github.com/Hrodvitnir-Fenrir/SdB_Record_Guide/assets/44929201/ac9d8b7c-3f55-4849-a72b-434e59439e45

</details>

---

### Outplayed
*En cours de rédaction*
<details>
  <summary>Installation</summary>

- Pour commencer, téléchargez l'installeur [ici.](https://go.overwolf.com/outplayed/) `https://go.overwolf.com/outplayed/`
> Outplayed fonctionne avec Overwolf, c'est une application qui va s'installer automatiquement avec Outplayed

- Une fois installé, et quelques configuration d'options sommaires, tout devrait être fonctionnel.
![Menu Outplayed](https://i.imgur.com/fa9VpFU.png)

</details>
<details>
  <summary>Configuration</summary>

Pour accéder aux options, vous avez l'engrenage en bas à gauche de l'application

- `Games` > Ici vous pouvez sélectionner les jeux où `Outplayed` enregistre

- `Capture` > Vous pouvez définir la qualité des clips, définir si l'enregistrement se fait sur le processeur ou la carte graphique, et des options sur le son et la webcam

![Capture](https://i.imgur.com/Gba6maN.png)

- `Sotage` > Si vous voulez que `Outplayed` supprime automatiquement les clips les plus anciens pour faire de la place pour les nouveaux, vous pouvez définir une taille maximale d'enregistrement

- `My games` > Pour chacun des jeux vous pouvez définir si vous voulez que `Outplayed` enregistre automatiquement ou non, la durée des clips `Before duration`, et les raccourcis.

![My games](https://i.imgur.com/scNBlZx.png)

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

Nous vous invitons à lancer une partie avec le gestionaire des tâches en fond sur l'onglet `performance` pour voir ce que votre pc consomme le plus.
En fonction des résultats, vous pouvez choisir un logiciel qui peut prendre les ressources qui sont le moins sollicitées.
> ![Gestionnaire des tâches](https://i.imgur.com/t1jrgAX.png)
> 
> Dans cet exemple, la mémoire est très peu sollicitée, ainsi que le processeur, donc `Seelseries moments` est un bon choix. Sinon `Medal` et `Outplayed` sont également de bons choix. Sinon, si la carte graphique était peu sollicitée, `Geforce Experience` ou `Radeon ReLive` aurait été un bon choix.

</details>

___

##### _Merci pour votre lecture, si jamais vous avez des suggestions, n'hésitez pas à nous en faire part via le bot `Opérateur SdB` sur le serveur_<br>Le bon esprit, le bô jeu.

[![logo](https://raw.githubusercontent.com/MrLixm/Sdb.branding/main/brand/header/twitter/variantB/SdB.header.twitter.master.png)](https://discord.gg/sdb)
