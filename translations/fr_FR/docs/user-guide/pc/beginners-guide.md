# Guide du débutant
---
>
> Ce guide ne s'applique qu'à la version PC de Gorilla Tag.  
> Si vous utilisez un Quest (sans link), aller au guide de mise à jour des mods Quest [****](quest-guide).

<!-- <div class="horizontal bordered" data-ea-publisher="gorillatagmodding-burrito-software" data-ea-type="image" data-ea-manual="true" id="pc-mod-guide"></div> -->
<!-- Guide Page Ad -->
<ins class="adsbygoogle"
     style="display:block"
     data-ad-client="ca-pub-1545654854838298"
     data-ad-slot="8114351325"
     data-ad-format="auto"
     data-full-width-responsive="true"></ins>

## Installeurs

### Monke Mod Manager {docsify-ignore}

![Monke Mod Manager logo](../docs/files/mmmlogo.png)

?> Ceci est présentement **l'installeur de mods recommandé**.

Monke Mod Manager est un installeur de mods qui installe automatiquement des mods dans Gorilla Tag, et qui peut mettre à jour ses mods lorsqu'on le réutilise. Le Monke Mod Manager vous avertit lorsque vous le démarrer s'il y a des mises à jour disponibles en ouvrant la page avec la plus récente mise à jour.  
Vous pouvez installer Monke Mod Manager depuis [**le Github de Steven**](https://github.com/DeadlyKitten/MonkeModManager/releases/latest). Sélectionnez le menu déroulant **Assets** et installez le fichier .exe appelé `MonkeModManager.exe`.

> Note : Si Windows vous avertit que le fichier est dangereux ou risqué, choisissez de conserver/exécuter quand même. C'est un faux positif.

![Preview](../docs/files/mmmpreview.png)

## Instructions d'installation

Après avoir installé le Monke Mod Manager, cliquer le 2 fois depuis vos fichiers pour l'ouvrir. Par défaut, Monke Mod Manager devrait automatiquement s'installer dans votre dossier d'installation de Gorilla Tag.

?> Si vous avez installé Gorilla Tag sur une autre unité de stockage, Monke Mod Manager vous demandera de sélectionner `Gorilla Tag.exe` depuis votre dossier d'installation. Allez à la section [**Dossier d'installation**](#install-folder) pour trouver votre dossier d'installation.

Ensuite, vous pouvez choisir les mods que vous voulez installer. BepInEx is the modloader for Gorilla Tag and cannot be unchecked. To update a mod, simply select the installed mod again. If you would like to get more information on a mod, click on it then hit the *View Mod Info* button.

After you select the mods you would like to install/update, hit the *Install/Update* button to begin the process. When the status monitor in the bottom left says "*Install complete!*", you're almost there!

If it's your first time modding (or starting with a clean install), you'll need to launch Gorilla Tag once and close it to initialize BepInEx. **You may not see any mods load the first time you launch Gorilla Tag after modding, this is normal.**  
After that, re-launch Gorilla Tag and if everything went well, your mods will now load into the game. Congratulations!

## Dossier d'installation

### Emplacement par défaut

If you installed your game on your main drive, this should be your installation folder. `C:\Program Files (x86)\Steam\steamapps\common\Gorilla Tag`

### Autres emplacements

If you installed your game in a different location, follow these instructions to find your installation folder.

1. Ouvrez Steam et cliquez avec le bouton droit sur l'étiquette Gorilla. Ensuite, allez à `Gérer > Parcourir les fichiers locaux`.

![Right-click Menu Preview](../docs/files/localfilescontext.png)

2. Cliquez sur la barre d'adresse en haut pour sélectionner le chemin du dossier d'installation. Appuyez sur `CTRL`+`C` pour copier ceci dans votre presse-papiers.

![Copy Folder Path Preview](../docs/files/copyfolderpath.png)

## Installation manuelle
A mod installer is the recommended way to install mods. See the section [above](#installers). If you have patched the game and just need to install mods that are not available in the installer, skip to step 4.

### Installez BepInEx

1. Télécharger [BepInEx](https://github.com/BepInEx/BepInEx/releases/latest). Vous obtiendrez `BepinEx_x64_VERSION.zip`, avec `VERSION` le numéro de version.
2. Extrayez le contenu du fichier .zip BepInEx dans le dossier [install](#install-folder) de votre installation de la balise Gorilla.

![BepInEx Folder Preview](../docs/files/bepinexfolder.png)

3. Exécutez Gorilla Tag une fois pour terminer l'installation.

### Installer les mods

4. Téléchargez le(s) mod(s) que vous souhaitez mettre à jour, que ce soit depuis GitHub, le canal [GorillaTag Modding Discord](https://discord.gg/b2MhDBAzTv) **#pc-mod-releases** ou d'autres sources. **Assurez-vous de télécharger toutes les dépendances requises pour chaque mod.**

![Plugins Folder Preview](../docs/files/pluginsfolder.png)

5. Certains mods ont des instructions d'installation précises, certains non. Généralement, il suffit de glisser-déposer le contenu du zip dans le dossier d'installation du jeu, et les fichiers doivent aller dans les dossiers correspondant. Si vous avez un fichier .dll, vous devrez généralement le mettre dans `BepInEx/plugins`.

## Désinstaller les Mods

Either remove the mod's .dll or folder from the `BepInEx/plugins` folder, which is located in your Gorilla Tag install folder.

## Installation des cartes {docsify-ignore}

> Consultez le [**Guide des Cartes Personnalisée Quest**](pc-maploading) pour plus d'informations sur les cartes personnalisées, l'installation et où trouver de nouvelles cartes.

## Mise à jour des mods {docsify-ignore}

> Consultez le [**Guide de Mise à Jour des Mods de Quest**](pc-updating) pour plus d'informations sur la mise à jour de Gorilla Tag avec des mods installés.

---

> Si vous avez apprécié ce guide, vous pouvez [envoyer un conseil](https://streamelements.com/burritosoft/tip) ou [parrainer l'écrivain principal](https://github.com/sponsors/burritosoftware).