# Hack the Box Meetup Conakry, GN
Comment démarrer avec le groupe HacktheBox Meetup Conakry, GN.

# Reunions
Nous nous réunissons en ligne sur notre serveur Discord 2fois par mois soit environ chaque 15 jours.

# Getting Started
1. Rejoignez notre groupe de rencontre et participez à nos prochain événement : https://www.meetup.com/fr-FR/hack-the-box-meetup-conakry-gn/
2. Rejoignez HacktheBox, si vous ne l'avez pas encore fait : https://app.hackthebox.com/home
3. Préparez votre ordinateur (voir ci-dessous).

Voici un excellent aperçu pour commencer votre parcours en Cybersecurite :
https://www.hackthebox.com/blog/learn-to-hack-beginners-bible

# Préparer votre ordinateur
Bien qu'il existe de nombreuses façons de préparer votre ordinateur, nous recommandons d'utiliser un logiciel de virtualisation, de télécharger une machine virtuelle `Kali Linux `pré-construite et d'utiliser celle-ci pour vous connecter à HacktheBox.
## Télécharger et Installer un Logiciel de Virtualisation
1. Téléchargez VMware Workstation Player : https://www.vmware.com/products/workstation-player/workstation-player-evaluation.html
2. Une fois téléchargé, faites un clic droit sur le fichier et sélectionnez **Run as Administrator**
3. Suivez les instructions à l'écran
4. Redémarrez votre ordinateur

## Télécharger la Machine Virtuelle Pré-construite (VM)
1. Téléchargez la VM Kali Linux depuis : https://www.kali.org/get-kali/#kali-virtual-machines
2. Cliquez sur l'option  **VMware** 
3. Une fois téléchargée, décompressez le fichier (téléchargez 7zip pour décompresser le fichier : https://www.7-zip.org/download.html)
4. Ouvrez VMware Workstation Player
5. Cliquez sur **Ouvrir une Machine Virtuelle**
6. Accédez au dossier décompressé ci-dessus et sélectionnez le fichier se terminant par ``.vmx``
7. Effectuez les modifications nécessaires aux ressources attribuées
8. Cliquez sur le bouton de lecture pour démarrer la VM
9. Nom d'utilisateur/mot de passe par défaut : `kali/kali`

Source: https://www.kali.org/docs/virtualization/import-premade-vmware/

## Connexion à HacktheBox
Depuis votre VM Kali Linux :
1. Connectez-vous à votre compte HacktheBox: https://app.hackthebox.com/home
2. Cliquez sur **CONNECT TO HTB**
3. Cliquez sur **Machines**
4. Cliquez sur **OpenVPN**
5. Dans **VPN ACCESS**, choisissez la région dans laquelle vous vous trouvez, ou la région la plus proche disponible
6. Dans **VPN SERVERS**, choisissez le serveur avec la latence la plus faible (nombre à droite)
7. Cliquer sur **DOWNLOAD VPN**
8. Ouvrez un terminal dans Kali et exécutez (en remplaçant "nom_utilisateur" par votre nom d'utilisateur) : ``sudo openvpn ~/Download/lab_nom_utilisateur.ovpn``

Source: https://help.hackthebox.com/en/articles/5185687-introduction-to-lab-access

# Dépannage
Parfois, les choses ne se passent pas comme prévu.
## VPN
Si vous ne parvenez pas à établir une connexion VPN à HacktheBox :
1. Vérifiez que vous exécutez la commande openvpn avec des privilèges `root`
2. Essayez de changer le serveur VPN auquel vous vous connectez, puis re-téléchargez le pack de connexion VPN
## Machines
Si la machine sur laquelle vous travaillez ne répond pas correctement :
1. Réinitialisez la machine
## Autres
Si le problème que vous rencontrez n'est pas répertorié ci-dessus, consultez cette page pour le problème :
https://help.hackthebox.com/en/articles/5185536-connection-troubleshooting
