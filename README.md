# TowerLog

You can use the [editor on GitHub](https://github.com/DO9THW/TowerLog/edit/master/README.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

## Installation

### Schritt 1: Du brauchst folgende Programme

#### Einen Webserver
Zum Beispiel Apache HTTP Server:

[Apache Homepage](https://httpd.apache.org)
```
sudo apt install apache2
```
Du kannst aber auch etwas anderes Verwenden.

#### PHP 
Du brauchst auch PHP, um die verbindung mit der SQL Datenbank herzustellen. (Falls jemand eine einfachere Lösung hat, einfach mal melden):

[PHP Homepage](https://php.net)
```
sudo apt install php 
```

#### SQL Server
Außerdem ist ein SQL Server für die Datenbank erforderlich:

```
sudo apt install mysql-server 
```

### Schritt 2: Dateien kopieren
Du kannst nun die Dateien von Github herunterladen und in das Verzeichnis Kopiert werden in dem der Webserver läuft, unter Linux meist `/var/www/html`.
