# InterAACtionBox-Live

## Etape 1: Téléchargement de l'ISO

Le fichier est disponible ici :
- https://www.swisstransfer.com/d/977a58c2-4174-4bf3-84b9-ff84378b28ae

## Etape 2: Graver l'ISO téléchargé sur la clé USB

- Utiliser Startup Disk Creator sur Ubuntu

Après avoir téléchargé startup Disk creator cette fenêtre apparait.

![startup Disk creator](assets/tutorial/startupDiskCreator.png)

Il faudra choisir le périphérique où graver l'ISO.<br>
Puis aller sélectionner l'ISO à graver.

![creator peripherique iso](assets/tutorial/creatorPeripheriqueIso.png)

Au moment de graver l'ISO sur la clé USB, une fenêtre d'avertissement apparaîtra.

![creator avertissement](assets/tutorial/fenetreDavertissement.png)

Cliquer sur "oui".

Après plusieurs minutes d'attente, cette fenêtre apparaîtra si tout s'est bien passé.

![creator reussit](assets/tutorial/CreatorReussit.png)

- Utiliser [Rufus](https://rufus.ie/fr/) sur Window (télécharger ici : https://rufus.ie/fr/)

Il vous faudra choisir le périphérique où graver l'ISO. <br>
Puis aller sélectionner l'ISO que à graver.

![rufus peripherique ISO](assets/tutorial/rufusPeripheriqueISO.png)

Lors du clique sur le bouton "démarrer" cette fenêtre apparaîtra.

![rufus ISO hybrid](assets/tutorial/rufusISOHybrid.png)

Laisser le choix recommandé puis appuyer sur "OK". <br>

Il est possible que cette fenêtre s'ouvre.

![rufus telechargement](assets/tutorial/rufusTelechargementAvertissement.png)

Accepter en cliquant sur "Oui".<br>

Si tout s'est bien passé, cette fenêtre apparaîtra.

- Utiliser [mac tool](https://ipom.fr/2019/07/03/creer-windows-10-bootable-graver-un-fichier-iso-sur-usb-dvd-cd-sur-mac-os-x/) on Mac

## Etape 3: inséré la clé USB dans l'ordinateur

cf https://github.com/InteraactionGroup/InterAACtionBox pour voir l'ordinateur que nous avons sélectionné.

## Etape 4: boot sur la clé USB

- 2 possibilités pour accéder au menu BIOS [BIOS menu](https://www.dell.com/support/kbdoc/fr-fr/000126121/acc%c3%a8s-%c3%a0-la-configuration-syst%c3%a8me-uefi-bios-sous-windows-sur-votre-syst%c3%a8me-dell#:~:text=Appuyez%20sur%20la%20touche%20F2%3E%20sur%20l'%C3%A9cran%20du%20logo,pendant%20le%20d%C3%A9marrage%20du%20syst%C3%A8me)

Une fois dans le menu BIOS.

![menuBIOS](assets/tutorial/bootMenu.png)

Il faudra aller dans la rubrique "Boot configuration".

![boot config](assets/tutorial/bootConfiguration.png)

Puis il faudra réorganiser les lignes en mettant les ports USB en premier.

![boot Organiser](assets/tutorial/bootOrganisation.png)

Pour finir, appliquer les modifications et redémarrer l'ordinateur.

![boot accept](assets/tutorial/bootAcceptChanges.png)

## Etape 5: installation de l'OS

Avant d'arriver au menu, cet écran de chargement s'affichera, veuillez patienter..

![chargement](assets/tutorial/chargementUbuntu.png)

Vous allez arriver sur le premier écran.

![installation premier ecran](assets/tutorial/InstallationInteraaaction.png)

Sélectionner "installer interaaaction". <br>

Choisir la langue de votre clavier.

![langue du clavier](assets/tutorial/langueClavier.png)

Choisir votre réseau Wi-Fi (Attention, pour installer les logiciels ou faire les mises à jour une connexion internet est obligatoire !).

![connexion](assets/tutorial/connexion.png)

Choisir l'installation minimale et laisser le reste par défaut.

![minimal](assets/tutorial/choisirMinimal.png)

Le type d'installation va être demandé, ici 2 choix s'offrent à vous :

- Soit vous décidez de créer un dual boot et vous sélectionnez le premier choix (mais vous aurez assurément des complications si vous avez un window au parallèle).
- Soit vous décidez d'écraser votre ancien système d'exploitation et mettre celui-ci à la place, dans ce cas prendre le second choix.

![dualboot choix](assets/tutorial/dualbootOrFormat.png)

Si vous prenez le second choix vous aurez une fenêtre qui vous demandera si vous êtes sûr d'écraser le système d'exploitation précédent.

![confirmation](assets/tutorial/Overwrite.png)

Cliquer sur continuer. <br>

Sélectionner votre ville puis continuer.

![fuseau horaire](assets/tutorial/fuseauHoraire.png)

Créer votre utilisateur avec un nom et un mot de passe puis continuer.

![user](assets/tutorial/createUser.png)

Ubuntu va s'installer veuillez attendre.

![chargementUbuntu](assets/tutorial/chargementApresInstall.png)

Une fois l'installation terminée, une fenêtre va apparaître et vous demandera de redémarrer, appuyez sur "redémarrer maintenant".

![redemarrer](assets/tutorial/redemarrer.jpg)

Au redémarrage, l'interAACtion box se lance automatiquement, il vous faudra aller dans "Mise à jour disponible !" en haut à gauche de l'écran.

![interaaaction](assets/tutorial/interaactionBox.png)

Sur cette page, vous devez appuyer sur "installer tous" pour avoir accès à toutes les applications.
![mise à jour](assets/tutorial/miseajour.png)

## Bug connu

Si l'interAACtion box vous bloque dans les menus et que vous devez sortir, allumez l'ordinateur, sortez du mode veille et allez dans le menu utilisateur, puis redémarrez l'ordinateur.
