# Opdracht <abbr title="Provincie Zuid-Holland">PZH</abbr> Subsidieregister op de kaart

1. Open het Subsidieregister van de Provincie Zuid-Holland:
<a href="https://subsidieregister.zuid-holland.nl/" target="_blank" rel="noopener">https://subsidieregister.zuid-holland.nl/</a>

1. Zoek de bedrijfslocatie met behulp van de <abbr title="Kamer van Koophandel">KvK</abbr>:
<a href="https://www.kvk.nl/zoeken/" target="_blank" rel="noopener">https://www.kvk.nl/zoeken/</a>

1. Zoek de bijbehorende `X Y` co&ouml;rdinaten bij het adres in het Kadaster:
<a href="https://bagviewer.kadaster.nl/" target="_blank" rel="noopener">https://bagviewer.kadaster.nl/</a>

1. Vul de co&ouml;rdinaten in:
<a href="https://openstate.github.io/rdnewviewer/" target="_blank" rel="noopener">https://openstate.github.io/rdnewviewer/</a>

## Bonus

Voeg een radius toe op basis van het bedrag.

Let op: schaal niet lineair met de radius, dat zorgt voor <a href="https://en.wikipedia.org/wiki/Misleading_graph#Improper_scaling" target="_blank" rel="noopener">misleidende visualisaties</a>. De oppervlakte van een cirkel is *<code><abbr title="pi &asymp; 3.14159">&pi;</abbr>r<sup>2</sup></code>* (*`r = radius`*), de formule om een radius bij een gewenste oppervlakte te vinden is *<code>r = &radic;(oppervlakte/<abbr title="pi &asymp; 3.14159">&pi;</abbr>)</code>*.