# claudi-talk
Nutzung von Nextcloud-Talk in Verbindung mit linuxmuster.net als Schulmessenger.
## Voraussetzungen
- Eine Nextcloud :)
- Einen API-Nutzer mit Admin-Rechten
- Eine Linuxmuster.net-Installation

## Nutzung
- `cd /opt`  (oder einen anderen gewünschten Ort)
- `git clone https://github.com/anschuetz/linuxmuster-nctalk`
- `cd linuxmuster-nctalk`
- Hinzufügen von `/opt/linuxmuster-nctalk` zum Pfad (in /etc/environment)
- `cp api-calls.config-dist api-calls.config`
- Anpassen der Konfiguration 
- Erzeugen der Fachschaftsraum-Definition & Anpassung
- Anpassen der Chatraum-Definitionsdateien



## Bemerkungen
Wenn die die Skripte nicht auf dem selben Host wie die Nextcloud laufen, muss der mysql-Aufruf angepasst werden.
Sollte die Datenbank von extern nicht erreichbar sein, funktionieren manche Teile nicht.
Für Installationen, bei der die Nextcloud unter docker auf dem selben Host läuft wie die Skripte, sollte alles out of the box gehen.

