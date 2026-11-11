# Art islàmic i art mudèjar

Recurs educatiu en valencià per a Batxillerat. Web estàtica, accessible i adaptable a mòbils, amb activitats, vocabulari, taula comparativa i versió imprimible.

## Publicació en GitHub Pages

1. Descomprimeix l’arxiu ZIP.
2. Crea un repositori en GitHub i puja el contingut d’aquesta carpeta (index.html ha de quedar a l’arrel).
3. Ves a **Settings → Pages → Build and deployment → Deploy from a branch**.
4. Selecciona **main** i **/ (root)** i prem **Save**.
5. GitHub mostrarà l’adreça del recurs quan acabe la publicació.

Per veure’l al teu ordinador, obri `index.html` amb un navegador. No requereix instal·lació ni connexió per mostrar les imatges.

## Contingut i edició

El recurs adapta didàcticament els apartats 5.3–5.6 del material aportat. No inclou els peus d’imatge originals. Es poden editar directament index.html i style.css. build.py és el generador opcional (Python 3).

S’han matisat les generalitzacions sobre materials i figuració i s’ha corregit la datació de la sinagoga del Trànsit (segle XIV).

## Imatges i mapes

Les imatges es distribueixen localment en assets/. assets.json conserva la font de Wikipèdia, el fitxer de Commons i les dades de llicència disponibles. Consulta els crèdits de la pàgina i les fitxes originals abans de redistribuir o modificar cada imatge. Les llicències de les imatges són les de cada autoria; no s’aplica una llicència conjunta al text derivat del manual.


## Ampliació de novembre de 2026

El web inclou ara una secció d'aprofundiment històric, una galeria visual amb huit peces i mapes que ja existien a `assets/`, i un apartat **Obres PAU**. La primera fitxa completa és la **mesquita de Còrdova**, amb context, planta, elements formals, cinc fases constructives, funció, influències, comentari model i autocorrecció.

### Com afegir una nova obra PAU

1. A `index.html`, dins de `<section id="pau">`, copia el bloc `<article class="pau-work">` de Còrdova i canvia-li l'identificador (per exemple, `pau-alhambra`).
2. Incorpora la nova obra al bloc `pau-list` amb un enllaç intern al seu identificador.
3. Completa els apartats d'identificació, context, anàlisi formal, funció i significat, influències, comentari model i preguntes.
4. Posa les imatges al directori `assets/`, enllaça la fitxa de Wikimedia Commons i indica'n l'autoria i la llicència en l'apartat de crèdits. Verifica que les imatges carreguen.
5. Contrasta la selecció d'obres amb la relació oficial de la PAU vigent. El fet de figurar en aquest recurs no significa que una obra forme part del llistat oficial.

Els estils de les fitxes, la galeria i les taules es troben a `style.css`. Publicar en la branca `main` conserva el funcionament de GitHub Pages existent.
