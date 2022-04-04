# projectpython  ABDOUL_DJAFAR -- SEYNABOU_DIALLO

Environnemment : 

1. 2 machines Ubuntu (21.10) et 1 machine Kali Linux (20.04)
2. Fixation des adresses IP grâce à netplan ( /etc/netplan/)
3. Machine serveur: installation des paquets bind9 pour le DNS et isc-dhcp-server pour le DHCP
5. Scripts python utilisés : client.py, database.py, server.py

Partie 0 :

![image](https://user-images.githubusercontent.com/76455540/161460146-101e8b81-4874-4e59-99f0-5621ba272bbb.png)

![image](https://user-images.githubusercontent.com/76455540/161460002-dd6e5a97-854b-47a2-b4a3-845960ed344a.png)

![image](https://user-images.githubusercontent.com/76455540/161460029-8e84dc77-562b-48cc-85af-ab4efa3af4b7.png)

![image](https://user-images.githubusercontent.com/76455540/161460176-45a79774-8127-45b8-b7ac-d6b19583df27.png)

![image](https://user-images.githubusercontent.com/76455540/161460195-63f0b4c6-2eb8-4c6b-80f2-2e470929866c.png)

![image](https://user-images.githubusercontent.com/76455540/161460219-18f4d2e0-4754-4291-abb3-f0f3620d7e11.png)

![image](https://user-images.githubusercontent.com/76455540/161461771-46a82221-6ddf-4c62-9d78-cb4eb3b84a3c.png)

Partie 1 : 

1. Script Install_MYSQL_DEPENDENCIES.sh : les dépendances qu’il faudra pour l’installation de MYSQL.
2. Script Install_IREDMAIL_DEPENDENCIES.sh : les dépendances requises pour l’installation de IREDMAIL.

![image](https://user-images.githubusercontent.com/76455540/161460788-7137e2b1-356e-46fd-b367-67a701fe99b8.png)

Partie 2 :

1. Database.py : Ce script permet de vérifier le mail de s'inscrire dans la base et de se connecter à cette dernière.
2. Login: qui permet au client de saisir ses identifiants et de se connecter. Pour l’exécuter il suffit de faire python3 database.py
3. Serveur.py : ce script permet au serveur de recupérer les informations d'inscription d'un client . Pour l’exécuter il suffit de faire 	python3 serveur.py
4. Client.py : ce script permet au client de créer un compte ou de se connecter. Pour l’exécuter il suffit de faire python3 client.py

NB: Nous pouvons mettre l’ensemble de ces scripts dans un même dossier pour que l’exécution soit plus facile;

