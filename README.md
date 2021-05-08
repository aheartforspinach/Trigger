# Trigger
Das Plugin erlaubt es Nutzern einen Trigger für Themen anzugeben und in einer Liste festzuhalten welche eigenen Trigger sie haben. Sollte ein Nutzer auf ein Thema zugreifen wollen, welches durch einen Trigger ausgezeichnet ist, den man auch selber angegeben hat, erfolgt eine Meldung, die darauf aufmerksam macht. An dieser Stelle kann der Nutzer dann entscheiden, ob er das Thema trotzdem lesen oder zurück auf den Index gehen möchte.

## Funktionen
__allgemeine Funktionen__
* Übersichtsseite über Trigger, welche andere Nutzer haben
* Möglichkeit eigene Trigger anzugeben und zu verwalten
* in neuen Themen (wenn diese zu dem entsprechenden Bereich gehören) Trigger anzugeben
* Darstellung der Trigger in der Threadübersicht
* Darstellung der Trigger in der Themenübersicht
* Warnung, wenn Thema einen Trigger hat, welchen man selber auch angegeben hat
* Ausgabe im Profil eines Profilfeldes

__Funktionen für Admins__
* Festlegung für Bereiche in welchen Trigger angegeben werden

## Voraussetzungen
keine

## Template-Änderungen
Zusätzlich wird ein CSS-File mit dem Namen trigger.css angelegt

__Neue Templates:__
* `trigger_forumdisplay`
* `trigger_memberprofile`
* `trigger_misc`
* `trigger_misc_row`
* `trigger_newthread`
* `trigger_show_box_warning`
* `trigger_showthread`

__Veränderte Templates:__
* `showthread` (wird um die Variablen `$trigger_box_warning` und `$trigger` erweitert)
* `member_profile` (wird um die Variable `$trigger` erweitert)
* `newthread` (wird um die Variable `$trigger` erweitert)
* `editpost` (wird um die Variable `$trigger` erweitert)
* `forumdisplay_thread` (wird um die Variable `$trigger` erweitert)

## Vorschaubilder
__Ansicht in der Übersichtsseite__
![overview](https://aheartforspinach.de/upload/plugins/trigger_misc_overview.png)

__Ansicht in der Übersichtsseite, Trigger bearbeiten__
![managetrigger](https://aheartforspinach.de/upload/plugins/trigger_misc_manage.png)

__Ansicht in der Threadübersicht__


__Ansicht in Threadansicht__
![showthread](https://aheartforspinach.de/upload/plugins/trigger_showthread.png)
