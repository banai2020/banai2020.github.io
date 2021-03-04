---
pageheader: Backend Content-Management-System (CMS)
backlinktext: "< HOME"
backlinkpath: "/"
notoc: true
---

***--- WICHTIG: nicht vollständig! ---***

Hier wird der Aufbau und die Konfiguration des Content-Management-Systems - als Backend - 
beschrieben.

=> ***Siehe auch [die Benutzer-Anleitungen zum Content-Management-System (CMS) Interface](/wp-admin).***

## Überblick

Um Sicherheit zu erhöhen und Wartung zu minimieren, wird nur die Kern-Funktionalität 
von Wordpress eingesetzt. Keine fremd Plugins, noch fremd Themes, werden verwendet. 

``Apache`` dient als Webserver mit MySQL als Datenbank. 

## Software Auflistung

FUNKTION    | SOFTWARE  | VERSION
:--         | :--       |:--
Content-Management | [Wordpress](https://de.wikipedia.org/wiki/WordPress_Foundation){:target="_blank"} | Version 5.6.1 (28. Februar 2021)
Webserver   | Apache    | 2.4
Datenbank   | MySQL     | 5.7.33 

## Funktionalitäten und Erweiterungen

- RESTful API (JSON)
- Eigenes Basis-Theme
- Eigene Plugins (Module)

## Konfigurationen

#### Wordpress

#### Apache