<h2>CSS-Variablen:</h2>

<p>Pseudoklasse <code>:root{}</code><br>
ist inhaltlich das selbe wie der Tag-Selektor <code>html{}</code><br>
Aber als Pseudoklasse stärker.</p>

<p>In <code>:root{}</code> können CSS-Variablen definiert werden, die dann aufgerufen werden können.</p>

<p>CSS-Variablen starten immer mit doppeltem Bindestrich.<br>
Zum Aufrufen <code>var( )</code> nutzen.</p>

<pre><code>:root{
 --colorMain: #cd0211;
 --colorBack: #f0f0f0;
}

body{
   color: var(--colorMain);
   background-color: var(--colorBack);
}
</code></pre>

<p>Auf diese Art können die Farben über <code>:root{}</code> 1x angepasst werden.</p>

<br>

<h3>Infos Thema Navbar:</h3>

<p>
<a href="https://www.w3schools.com/css/css_navbar.asp">
https://www.w3schools.com/css/css_navbar.asp
</a>
<br>
<a href="https://wiki.selfhtml.org/wiki/Navigation/Grundstruktur">
https://wiki.selfhtml.org/wiki/Navigation/Grundstruktur
</a>
</p>

<h3>Infos Thema Barrierefreiheit:</h3>

<p>
<a href="https://www.barrierefreiheit-dienstekonsolidierung.bund.de/Webs/PB/DE/umsetzungshilfen/webentwicklung/aria/aria-node.html">
https://www.barrierefreiheit-dienstekonsolidierung.bund.de/Webs/PB/DE/umsetzungshilfen/webentwicklung/aria/aria-node.html
</a>
</p>
