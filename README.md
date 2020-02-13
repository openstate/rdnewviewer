# RD New Viewer

Basic viewer for Dutch *Rijksdriehoeksco&ouml;rdinaten* (<abbr title="European Petroleum Survey Group">EPSG</abbr> 28992 / *RD New*) and <abbr title="World Geodetic System 1984">WGS 84</abbr> data.

[View online](https://openstate.github.io/rdnewviewer/).

Input (per line):
```
X Y radius text
```

`X` and `Y` are required, `radius` and `text` are optional.
Item separators are space(s), tab(s) and `;`.

`X Y` can be expressed in RD New or WGS 84, the decimal separator can be `.` or `,`.
`X Y` can be entered as `Y X`.
Only *Dutch* bounds, for *RD New*: <code>0 &le; X &le; 300000</code> and <code>289000 &le; Y &le; 629000</code> and for *WGS 84*: <code>50 &le; <abbr title="latitude"><i>lat</i> (X)</abbr> &le; 54</code> and <code>3 &le; <abbr title="longitude"><i>lng</i> (Y)</abbr> &le; 10</code>.

`radius` is either the radius in meters for a circle marker (maximized at `100000` / 100km), or a non number to use a marker (<abbr title="for example (latin: exempli gratia)">e.g.</abbr> `x`).

`text` can contain HTML and spaces.

# ToDo

* Probably recode in Svelte/Sapper
* Create code to store (maybe in a GitHub gist?)
* Create `<iframe>` embed code (option without store is to use deflate encoded in `src=#hash` ?))
* Option to change base map tiles / zoom / center
* Option to change colors per item / chomajs
* Zipcode geocoder