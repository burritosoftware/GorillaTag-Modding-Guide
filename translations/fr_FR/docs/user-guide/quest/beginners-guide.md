# Guide du débutant pour Quest
---
>
> Ce guide ne s'applique qu'à la version Quest de Gorilla Tag. Si vous utilisez un casque SteamVR ou un Quest **avec link**, allez au guide [**Mise à jour du mod PC**](pc-guide).

<!-- <div class="horizontal bordered" data-ea-publisher="gorillatagmodding-burrito-software" data-ea-type="image" data-ea-manual="true" id="quest-mod-guide"></div> -->
<!-- Guide Page Ad -->
<ins class="adsbygoogle"
     style="display:block"
     data-ad-client="ca-pub-1545654854838298"
     data-ad-slot="8114351325"
     data-ad-format="auto"
     data-full-width-responsive="true"></ins>

## Installation de QuestPatcher

Présentement, la seule manière recommandée pour installer des mods est avec **QuestPatcher**. Installez **QuestPatcher** depuis [Lauriethefish's GitHub](https://github.com/Lauriethefish/QuestPatcher/releases/latest).

### Windows

> La seule version de Windows officiellement prise en charge est Windows 10. D'autres versions peuvent fonctionner, mais nous ne pouvons pas garantir la pleine fonctionnalité de celle-ci.

1. Sélectionnez le menu déroulant des assets sur GitHub, et cliquez sur `QuestPatcher-windows.exe`, puis attendez que le téléchargement se termine.
2. Ouvrez votre dossier de téléchargements et double-cliquez sur l'installateur.
3. Il est possible qu'une invite de ce type s'ouvre lors de l'exécution de QuestPatcher. Ceci est un **faux positif**, appuyez simplement sur `Plus d'info` puis `Exécuter quand même`.

![Smartscreen pop-up](../docs/files/questpatchersmartscreen.png)

4. Sélectionnez `Installer pour tous les utilisateurs` ou `Installer pour moi seulement` et appuyez sur `Oui` si une invite d'administration apparaît.
5. Acceptez le contrat de licence, appuyez sur Suivant, appuyez à nouveau sur Suivant, puis appuyez sur Installer.
6. Attendez que l'installation se termine, puis appuyez sur Suivant, puis terminez pour ouvrir QuestPatcher.


### macOS

!> QuestPatcher devrait automatiquement installer Java. Si vous utiliser une version plus ancienne de macOS, Java pourrait être détecté lorsqu'il ne l'est pas. Si vous avez de la difficulté à modder le jeu, veuillez installer manuellement Java [ici](https://www.java.com/en/).

1. Sélectionnez le menu déroulant des assets sur GitHub, et cliquez sur `QuestPatcher-mac.dmg`, puis attendez que le téléchargement se termine.
2. Ouvrez votre dossier Téléchargements, et double-cliquez sur `QuestPatcher-mac.dmg`.
3. Faites glisser l'application QuestPatcher dans le dossier Applications.
4. Fermez la fenêtre DMG, faites un clic droit sur QuestPatcher sur votre bureau et cliquez sur `Éjecter "QuestPatcher"`.
5. Ouvrez votre dossier Téléchargements, et double-cliquez sur QuestPatcher. **__Assurez-vous de maintenir contrôle__**, puis cliquez sur Ouvrir (Vous n'aurez qu'à le faire la première fois).
6. Dans le développeur non reconnu qui arrive (voir ci-dessous), cliquez sur `Ouvrir`.

![Unverified app pop-up](../docs/files/questpatchermacunverified.png)


### Linux

> QuestPatcher est compilé pour [Ubuntu](https://ubuntu.com/) Linux. D'autres distributions Linux peuvent fonctionner, mais vous pouvez rencontrer des problèmes.

!> Ces instructions sont plus compliquées que Mac et Windows, et il vous est recommandé de savoir comment utiliser un terminal.

1. Sélectionnez le menu déroulant des assets sur GitHub, et cliquez sur `QuestPatcher-ubuntu.zip`, puis attendez que le téléchargement se termine.
2. Extraire le fichier ZIP à l'aide du gestionnaire d'archives.
3. Entrez le dossier extrait, faites un clic droit, puis appuyez sur `Ouvrir dans le Terminal`.
4. Tapez `chmod +x QuestPatcher` et appuyez sur Entrée.
5. Si tout se passe bien, tapez `./QuestPatcher` et QuestPatcher se chargera.

## Patch

En ouvrant pour la première fois QuestPatcher, vous serez accueilli par un écran de chargement comme ci-dessous. Il y aura quelques barres de chargement pendant que QuestPatcher installe des fichiers importants. (`Downloading openjre` and `Downloading platform-tools`).

![QuestPatcher Loading](../docs/files/questpatcherloading.png)

> Si vous obtenez un message indiquant `Quest Not Connected`, assurez-vous que votre quête est branchée, et vous avez configuré le mode développeur conformément aux instructions d'installation de [SideQuest](https://sidequestvr.com/setup-howto). 
> 
> Si vous obtenez une invite disant `App Not Installed`, assurez-vous que vous avez installé Gorilla Tag depuis Oculus App Lab [ici](https://www.oculus.com/experiences/quest/4979055762136823/).


Après environ 30 secondes (dépendant de votre connexion internet, cela peut aller jusqu'à 5 minutes), QuestPatcher aura fini de charger and vous serez accueilli par un écran, comme représenté ci-dessous.

![QuestPatcher Ready To Patch](../docs/files/questpatcherpatch.png)

**Pour commencer à patcher le jeu, cliquez le bouton `Patch my App!`.**

> Cela peut prendre 1 à 15 minutes pour patcher votre application (grossièrement) Vous devez vous assurer que votre connexion Internet reste en ligne pendant ce temps.

> Ne fermez pas Questpatcher pendant qu'il patch votre jeu.

## Gérer les mods

Lorsque QuestPatcher aura fini l'installation, vous serez accompagné à cet écran.

> La prochaine fois que vous ouvrirez QuestPatcher, vous serez amené directement à cet écran car votre jeu est déjà mis à jour.

![Patching Completed](../docs/files/questpatcherpatched.png)

### Installer les mods

Pour installer des mods, il faut que vous installiez un fichier de type `.qmod` du mod que vous voulez. Vous pouvez les trouver dans la section `#quest-mod-releases` dans le [GorillaTag Modding Discord](https://discord.gg/b2MhDBAzTv).

!> N'installer pas des fichier .DLL, ils sont des mods pour PCVR, qui ne peuvent pas être utilisés pour la version Quest de GorillaTag.

Pour installer un mod, appuyez le bouton browse dans la section `Mod Management` du QuestPatcher and sélectionnez les mods que vous voulez installer. Finalement, appuyez le bouton `Open` pour installer les mods. ![Selecting a mod in QuestPatcher](../docs/files/questpatcherselectmod.png)

!> Installer un mod peut installer d'autres mods qui sont nécessaires au fonctionnement de celui-ci. Ne les désinstaller pas!

Une fois que le mod est installé, vous devriez le voir dans la section Mods du QuestPatcher. ![Mods Installed](../docs/files/questpatcherinstalledmods.png)

**Vous pouvez désormais ouvrir votre jeu et utiliser vos mods!**

?> Si vous voyez cet écran en ouvrant GorillaTag, appuyez tout simplement **Open App**. N'appuyez pas Restore, cela restaurera votre jeu à vanilla et peut causez certains problèmes avec votre installation.  
![Restore App](../docs/files/restoreapp.png)

### Désinstaller les Mods

Les mods peuvent être activés ou désactivés en cliquant le bouton à côté de celui-ci. Désactiver un mod fait que celui-ci agit comme s'il n'a jamais été installé, mais vous pouvez toujours le réactiver.


Si vous voulez supprimer un de vos mods, appuyez sur le bouton `Delete` à côté de ce mod.

## Gestion des cosmétiques & autres objets

!> Pour utiliser les cosmétiques, vous devrez installer le Gorilla Cosmetics mod. Sinon, il n'apparaîtront jamais dans le jeu.

Pour voir les cosmétiques et les cartes que vous avez installés, appuyez sur la section `Cosmetics & Other Items` du QuestPatcher. Déroulez le menu pour sélectionner le ou les fichiers que vous voulez modifier.

**Les cosmétiques peuvent être installés en les apportant directement dans la partie grise du QuestPatcher depuis vos fichiers, ou en appuyant le bouton Browse.**

![QuestPatcher Cosmetics Menu](../docs/files/questpatcherotheritems.png)

## Installation des cartes {docsify-ignore}

> Consultez le Guide [**Guide des Cartes Personnalisée Quest**](quest-maploading) pour plus d'informations sur les cartes personnalisées, l'installation et où trouver de nouvelles cartes.

## Mise à jour des mods {docsify-ignore}

> Consultez le [**Guide de Mise à Jour des Mods de Quest**](quest-updating) pour plus d'informations sur la mise à jour de Gorilla Tag avec des mods installés.

---

> Si vous avez apprécié ce guide, vous pouvez [envoyer un conseil](https://streamelements.com/burritosoft/tip) ou [parrainer l'écrivain principal](https://github.com/sponsors/burritosoftware).