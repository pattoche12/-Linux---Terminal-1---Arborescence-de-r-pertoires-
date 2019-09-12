# -Linux---Terminal-1---Arborescence-de-r-pertoires-


wilder@legolas:~$ ls
Bureau     examples.desktop  Images   Musique  Téléchargements
Documents  foo               Modèles  Public   Vidéos
wilder@legolas:~$ ls.

La commande « ls. » n'a pas été trouvée, voulez-vous dire :

  commande « lsd » du snap lsd (0.16.0)
  commande « lsc » du deb livescript
  commande « lsw » du deb suckless-tools
  commande « lsm » du deb lsm
  commande « ls » du deb coreutils
  commande « lsh » du deb lsh-client

Voir « snap info <nomdusnap> » pour des versions supplémentaires.

wilder@legolas:~$ pwd
/home/wilder
wilder@legolas:~$ ls/home/wilder
bash: ls/home/wilder: Aucun fichier ou dossier de ce type
wilder@legolas:~$ ls ..
lost+found  wilder
wilder@legolas:~$ pwd
/home/wilder
wilder@legolas:~$ cd ..
wilder@legolas:/home$ pwd
/home
wilder@legolas:/home$ cd /home
wilder@legolas:/home$ cd/home/wilder
bash: cd/home/wilder: Aucun fichier ou dossier de ce type
wilder@legolas:/home$ cd /home/wilder
wilder@legolas:~$ ls -l
total 48
drwxr-xr-x 2 wilder wilder 4096 juil. 26 14:15 Bureau
drwxr-xr-x 2 wilder wilder 4096 sept. 11 00:03 Documents
-rw-r--r-- 1 wilder wilder 8980 juil. 26 12:11 examples.desktop
drwxr-xr-x 2 wilder wilder 4096 sept. 10 20:06 foo
drwxr-xr-x 2 wilder wilder 4096 juil. 26 14:15 Images
drwxr-xr-x 2 wilder wilder 4096 juil. 26 14:15 Modèles
drwxr-xr-x 2 wilder wilder 4096 juil. 26 14:15 Musique
drwxr-xr-x 2 wilder wilder 4096 juil. 26 14:15 Public
drwxr-xr-x 2 wilder wilder 4096 juil. 26 14:15 Téléchargements
drwxr-xr-x 2 wilder wilder 4096 juil. 26 14:15 Vidéos
wilder@legolas:~$ pwd
/home/wilder
wilder@legolas:~$ cd /
wilder@legolas:/$ ls
bin    dev   initrd.img      lib64       mnt   root  snap  tmp  vmlinuz
boot   etc   initrd.img.old  lost+found  opt   run   srv   usr  vmlinuz.old
cdrom  home  lib             media       proc  sbin  sys   var
wilder@legolas:/$ cd /opt
wilder@legolas:/opt$ ls
wilder@legolas:/opt$ ls -l
total 0
wilder@legolas:/opt$ cd ~
wilder@legolas:~$ ls ~/téléchargements
ls: impossible d'accéder à '/home/wilder/téléchargements': Aucun fichier ou dossier de ce type
wilder@legolas:~$ cd /home
wilder@legolas:/home$ ls ~/Téléchargemnts
ls: impossible d'accéder à '/home/wilder/Téléchargemnts': Aucun fichier ou dossier de ce type
wilder@legolas:/home$ cd ..
wilder@legolas:/$ cd /home
wilder@legolas:/home$ pwd
/home
wilder@legolas:/home$ ls ~/Téléchagements
ls: impossible d'accéder à '/home/wilder/Téléchagements': Aucun fichier ou dossier de ce type
wilder@legolas:/home$ pwd
/home
wilder@legolas:/home$ pwd
/home
wilder@legolas:/home$ cd ~/Musique
wilder@legolas:~/Musique$ cd /usr/bin
wilder@legolas:/usr/bin$ cd
wilder@legolas:~$ cd ~/Téléchargements
wilder@legolas:~/Téléchargements$ cd
wilder@legolas:~$ 
