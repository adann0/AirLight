# AirLight

Ce script a pour but de reunir les commandes consacrés aux tests de sécurité des réseaux WIFI WPA/WPA2 par le biais de la suite aircrack-ng. 

<b> ChangeLog : </b>

    v0.1 : Attaque par Déauthentification
    

<b> Installation : </b>

Pour télécharger et rendre executable le script :

    $ wget -P $HOME https://github.com/adann0/AirLight/archive/master.zip
    $ unzip master.zip -d ~
    $ cd AirLight-master
    $ chmod +x airlight airlightdeauth
    $ mkdir logs dic

Le seul chemin pour que le script s'éxécute correctement à l'heure actuelle est : 

    /home/$USER/AirLight-master 

On peut ajouter le AirLight-master au $PATH :
    
    $ echo $PATH
    $ echo 'export PATH=$PATH:/home/$USER/AirLight-master' >> /home/$USER/.bashrc
    
pour pourvoir ensuite l'executer directement :

    $ airlight

<p align="center">
  <img src="http://image.noelshack.com/fichiers/2018/25/1/1529356089-capture-du-2018-06-18-23-07-54.png">
</p>

Pour plus de détails :

    https://aircrack-ng.org/
    https://github.com/aircrack-ng/aircrack-ng
    http://wiki.backtrack-fr.net/index.php/Casser_une_cl%C3%A9_wep/wpa_avec_la_suite_Aircrack-ng
