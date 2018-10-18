


# UbuntuStation

# Sous Windows 

## defragmenter le disque si on est pas en SSD

## Scandisk
Lancer en mode administrateur
CHKDSK X: /F 

## partitionnement sous windows
EASEUS en FREE
<https://www.easeus.fr/>


# Sous Linux 


### Accéder à un répertoire distant ssh
```
sudo apt-get install sshfs
sshfs  cdelamarre@mustang.fcsystem.com:/home/fcs/ ~/fcs/
```
#### montage automatique avec Autofs
Regarder le point 6 Autofs
<https://doc.ubuntu-fr.org/sshfs>

### Capture d'ecran 
```
sudo apt install flameshot
flameshot gui
```


### Correction vitesse pavétactile
/usr/share/X11/xorg.conf.d/70-synaptics.conf

### Php
```
sudo apt-get install php
```
### Thunderbird
```
sudo apt-get install thunderbird
```

### Docker
```
sudo apt-get install docker
```

### Pour configurer les accès en écriture des partitions 
```
sudo apt-get install  ntfs-config
sudo ntfs-config
```
Si les répertoires de windows ne sont accessible qu'en lecture malgré le paramétrage de ntfs-config, il faut désactiver l'hibernation sous windows aussi appelé « Démarrage Rapide »
<https://www.zebulon.fr/astuces/273-desactiver-le-demarrage-rapide-de-windows-8.html>

### Editeur de développement
```
sudo snap install notepad-plus-plus
```

### Gestionnaire de base de donnée
```
sudo apt-get install libreoffice-base
sudo apt-get install libreoffice-sdbc-postgresql
```

### Barre de lancement macOsLike
```
sudo apt-get install docky
docky
```
Pour supprimer l'icone de configuration de docky
```
gconftool-2 --type Boolean --set /apps/docky-2/Docky/Items/DockyItem/ShowDockyItem False
```

### GIT & Smartgit
```
sudo add-apt-repository ppa:git-core/ppa # apt update; 
sudo apt-get install git
wget https://www.syntevo.com/downloads/smartgit/smartgit-18_1_5.deb
dpkg -i smartgit-18_1_5.deb
```

### node.js
```
sudo apt-get install npm
```
