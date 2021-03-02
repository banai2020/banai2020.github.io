[&lt; HOME](/)

# User Interface (Frontend)

***--- WICHTIG: nicht vollständig! ---***

{% include /_includes/toc.html html=content sanitize=true class="inline_toc" id="my_toc" h_min=3 h_max=6 %}

Dieser Teil beschreibt die technischen Aspekte der Web App, 
die als User Interface oder Frontend dient.

## Architektur der App

### Technologien und Frameworks

Die App, oder was der Benutzer als Frontend bekommt, ist auf Basis von

* [`React`][1]{:target="_blank"} - v16.13.1

mit der Facebook-Framework, [`CRA`][2]{:target="_blank"}
aufgebaut, und liefert Browser-basierte `HTML`- und `ES6-Javascript`-Code. 

Wichtige [`React`][1]{:target="_blank"} Module, die eingesetzt werden,
sind, u.a.:

* axios
* bootstrap
* lodash
* lunr
* react-google-maps
* react-parallax
* react-pdf
* react-redux
* react-scroll-section
* react-search-lunr
* styled-component

### Build & Deployment (Software-Erstellung- und Bereitstellungssprozess)

Die App wurde in einer `Linux` Umgebung entwickelt, und benötigt die folgende Tools:

* `node` - v15.7.0
* `npm` (mit `npx`) - v7.4.3
* `yarn` - v1.22.5

Die Erstellung des fertigen ***Builds*** erfolgt durch folgendes Bash-Kommando:

```bash
yarn build
```

und die daduch entstandende Datei-Struktur in ``./build`` wird zum Wurzelverzeichnis 
des Webservers hochgeladen bzw. übertragen. 

## Schnittstellen

### Google Analytics

Siehe auch [Konfigurationen](/konfig/).


[1]: https://reactjs.org
[2]: https://create-react-app.dev
