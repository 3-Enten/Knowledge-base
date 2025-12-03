css-variablen:

Pseudoklasse :root{}
ist inhaltlich das selbe wie der tag-Selektor html{}
Aber als Pseudoklasse stärker.

in :root{} können CSS-Variablen definiert werden, die dann aufgerufen werden können.

CSS-Variablen starten immer mit doppeltem Bindestrich.
Zum Aufrufen var( ) nutzen.

:root{
 --colorMain: #cd0211;
 --colorBack: #f0f0f0;
}

body{
   color: var(--colorMain);
   background-color: var(--colorBack);
}

Auf diese Art können die Farben über :root{} 1x angepasst werden.


Infos Thema Navbar:
https://www.w3schools.com/css/css_navbar.asp
[https://wiki.selfhtml.org/wiki/Navigation/Grundstruktur](https://wiki.selfhtml.org/wiki/Navigation)

Infos Thema Barrierefreiheit:
https://www.barrierefreiheit-dienstekonsolidierung.bund.de/Webs/PB/DE/umsetzungshilfen/webentwicklung/aria/aria-node.html
