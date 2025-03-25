Spoony Firmware Repository
This repository contains all compiled firmware binaries for the Spoony device — DotVision’s industrial energy submeter.
It is intended for users, partners, and integrators who need to deploy or update Spoony devices with ready-to-use firmware files.

➡️ French version below – 🇫🇷 – faites défiler pour la version française 🇫🇷

📁 Contents
✅ Precompiled firmware files (.bin or .hex), organized by version
📝 Release notes and changelogs
🧭 Firmware update instructions
⚙️ Hardware compatibility details (Spoony v1, v2, etc.)
⚠️ No source code is included in this repository.
Only official and validated firmware binaries ready for deployment are provided.

🔄 Firmware Update Instructions
The firmware can be updated by placing the new .bin or .hex file in the firmware directory of the device’s MicroSD card and then rebooting the device.

Upon reboot, the device will automatically detect and install the new firmware if valid.

💡 In some cases, firmware updates may require updated configuration files to ensure proper operation. If needed, DotVision will provide the required files along with the firmware.

🔧 Method 1 – Copy via MicroSD card (manual)
Remove the MicroSD card from the device.
Insert it into a computer.
Copy the firmware file into the firmware folder on the card.
Reinsert the MicroSD card into the device.
Press the Reset button (see user manual, section 2.4.2).
Wait about 2 minutes for the device to reboot with the new firmware.
You can verify the firmware version on the Device Information page of the Web UI (see section 5.5 of the user manual).

🌐 Method 2 – Upload via Web Interface
Access the device's Web interface.
Go to the Firmware Update section (see chapter 5.10.4 of the user manual).
Upload the new firmware file.
Restart the device via the interface.
📌 Notes
Always check compatibility with your device hardware version (Spoony v1, v2, etc.).
When in doubt, contact DotVision support before updating.
📘 Version Française – 🇫🇷 – Spoony Firmware
Ce dépôt contient l’ensemble des firmwares compilés pour le dispositif Spoony, le sous-compteur énergétique industriel développé par DotVision.
Il est destiné aux utilisateurs, partenaires et intégrateurs souhaitant déployer ou mettre à jour leurs appareils Spoony avec des fichiers binaires prêts à l’emploi.

📁 Contenu
✅ Fichiers firmware précompilés (.bin ou .hex), classés par version
📝 Notes de version et changelogs
🧭 Instructions de mise à jour
⚙️ Informations de compatibilité matérielle (Spoony v1, v2, etc.)
⚠️ Aucun code source n’est inclus dans ce dépôt.
Seuls les firmwares officiels, validés et prêts à être installés sur les appareils sont disponibles.

🔄 Instructions de mise à jour du firmware
Le firmware de l’appareil peut être mis à jour simplement en plaçant le nouveau fichier dans le répertoire firmware de la carte MicroSD avant de redémarrer l’appareil.

À son redémarrage, l’appareil détectera automatiquement le nouveau fichier, le vérifiera, et appliquera la mise à jour.

💡 Dans certains cas, une mise à jour du firmware peut nécessiter également la mise à jour de certains fichiers de configuration. Si c’est le cas, DotVision vous fournira les fichiers nécessaires.

🔧 Méthode 1 – Copie directe sur la carte MicroSD
Retirez la carte MicroSD de l’appareil.
Insérez-la dans un ordinateur.
Copiez le fichier .bin ou .hex dans le dossier firmware de la carte.
Réinstallez la carte MicroSD dans l’appareil.
Appuyez sur le bouton Reset (voir manuel utilisateur, section 2.4.2).
Attendez environ 2 minutes pour que l’appareil redémarre avec la nouvelle version.
Vous pouvez vérifier la version installée depuis la page Device information de l’interface Web (voir section 5.5 du manuel).

🌐 Méthode 2 – Copie via l’interface Web
Accédez à l’interface Web de l’appareil.
Rendez-vous dans la section Mise à jour Firmware (voir chapitre 5.10.4 du manuel).
Téléversez le nouveau fichier firmware via le navigateur.
Redémarrez l’appareil depuis l’interface.
📌 Notes
Vérifiez toujours la compatibilité de la version du firmware avec votre modèle de Spoony (v1, v2, etc.).
En cas de doute, contactez le support DotVision avant de procéder.
© DotVision – Tous droits réservés.
