\# Docker Basics – c’t 3003 Übung



\## Dienste



\### Pi-hole

\- Blockiert Werbung und Tracking im Netzwerk (DNS-Server).  

\- Weboberfläche: http://localhost/admin  

\- Passwort steht in der Datei `pihole.yml` (WEBPASSWORD).  

\- Achtung: Auf Windows ist Port 53 manchmal schon belegt → dann Pi-hole evtl. nicht startbar.



\### Portainer

\- Oberfläche um Docker Container zu verwalten.  

\- Weboberfläche: https://localhost:9443  

\- Beim ersten Aufruf legst du einen Admin-User an.  



\### Watchtower

\- Aktualisiert Container automatisch, wenn es neue Versionen gibt.  

\- Keine eigene Webseite, läuft im Hintergrund.  

\- Logs anschauen mit: `docker logs -f watchtower`  



\### Nginx

\- Einfacher Webserver.  

\- Zeigt eine kleine Testseite an.  

\- Weboberfläche: http://localhost:8080  



