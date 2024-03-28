# Docker Compose GeoFS Server
Roundcube and Dokuwiki Docker for Uni Münster GeoFS Mail
## Installation
1. `docker-compose.yaml` runterladen (docker/docker compose sollte schon installiert sein)
2. In der Datei **Ports** anpassen!
3. Im Ordner mit der Datei `docker compose up` ausführen
## Roundcube
- Roundcube Image: https://github.com/roundcube/roundcubemail-docker
## Dokuwiki
- Dokuwiki Image: https://hub.docker.com/r/linuxserver/dokuwiki
### Wiki Migration
- [Dateien von der alten Instanz zur neuen kopieren:](https://www.dokuwiki.org/faq:servermove)
- dokuwikiroot\data\pages (für die Wikiseiten)
- dokuwikiroot\data\media (für Fotos und Dateien)
- dokuwikiroot\lib\plugins (für Plugins)
- dokuwikiroot\conf\local.php ([für Configs](https://www.dokuwiki.org/config#configuration_files))
