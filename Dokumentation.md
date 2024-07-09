# Dokumentation M158 Praxisarbeit

## zuerst habe ich das Learner Lab gestartet auf AWS
![alt text](Umgebung1.png)
## Umgebung aufbauen / einrichten 
![alt text](Umgebung2.png)
![alt text](Umgebung3.png)
![alt text](Umgebung4.png)
![alt text](Umgebung5.png) 
![alt text](Umgebung6.png) 
![alt text](Umgebung7.png) 
![alt text](Umgebung8.png)
![alt text](Umgebung9.png) 

## Elastische IP
![alt text](ElasticIP.png)
## via SSH verbinden
![alt text](Umgebung10.png) 

## mit superuser einloggen und ein update
![alt text](sudosu-update.png)

## nala installieren (als schnellerer wrapper von apt)
![alt text](nala.png)

## nginx Webserver installieren
![alt text](nginx.png)

## mysql DB-server installieren
![alt text](mysql.png)

## mysql konfigurieren
![alt text](mysqlsecure.png)
![alt text](mysqlsecure2.png)

## DB-User für wordpress 
![alt text](DBWordpressUser.png)

## DB-Login testen
![alt text](loginTestenDb.png)

## DB für Wordpress erstellen
![alt text](wordpressDB-1.png)

## PHP installieren
![alt text](PHP.png)

## PHP restart
![alt text](phpRestart.png)

## Nginx konfigurieren
![alt text](nginxConfigDatei1.png)
![alt text](nginxConfig.png)

## DNS eintrag auf www.duckdns.org
![alt text](duckDNSEintrag.png)

## Nginx Konfiguration Domain anpassen
![alt text](NachDomainConfigAnpassen.png)

## Nginx restart
![alt text](nginxRestart2.png) 

## erster Test im Browser
![alt text](testBrowser.png)

## nochmals Nginx Konfigurationsdatei anpassen
![alt text](NginxKonfigAnpassen.png)

## PhpMyAdmin installieren
![alt text](PHPMyAdmin.png)

## PhpMyAdmin Dateien verlinken 
![alt text](PhpMyAdminSynLinc.png)

## PhpMyAdmin erstes Login
![alt text](phpmyadminlogin.png)

## Passwort von WOrdpress zurückgesetzt
![alt text](Passwort1.png)
![alt text](Passwort2.png)

## Login in Wordpress mit neuem Passwort
![alt text](Passwort3.png)


## Da ich keine verbindung mit dem FTP Server herstellen konnte, habe ich einfach die dateien lokal auf mein Gerät abgelegt und dann via SSH auf den Ubuntu Server kopiert

## unzip installieren
![alt text](Unzip.png)

## temporärer Ordner für wp Dateien
![alt text](temporärerOrdner.png)

## Dateien in temporären Ordner entzipen
![alt text](Dateienentzipen.png)

## Dateien in var/www/html Ordner verschieben
![alt text](DateienHTMLOrdner.png)

## Datenbank importieren
![alt text](DB-import.png)

## Konfiguration nochmals anpassen
![alt text](ConfigANpassen.png)

## Berechtigungen für html Ordner anpassen
![alt text](Berechtigungen.png)

## PHP mysqli installieren
![alt text](phpmysqli.png)

## DNS-Server mit Zone eingerichtet mit folgender Anleitung:
https://tecadmin.net/configure-dns-server-on-ubuntu-linuxmint/#:~:text=How%20to%20Setup%20Your%20Own%20DNS%20Server%20on,6%20Step%206%3A%20Testing%20the%20DNS%20Server%20

## Datenbank Backup Script
### Ich habe im /var/www/html Ordner ein Dackup-Script gemacht ,,backupDB.sh'' , welches jeweils einmal pro Tag einen Dump erstellt von der wp-Datenbank und im Directory backups ablegt. 
![alt text](DBbackupScript.png)
## Crontab 
![alt text](crontab.png)

## Endergebnis
![alt text](ENdprodukt.png)


