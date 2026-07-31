# Nuba Psicologia — web

Web d'una sola pàgina (SPA) implementada des del disseny de Claude Design
(`Nuba Psicologia.dc.html`). Tot el codi és autònom dins de `index.html`
(HTML + CSS + JS en línia, tipografies de Google Fonts).

## Com veure-la

- Obre `index.html` directament al navegador, **o**
- Serveix la carpeta amb qualsevol servidor estàtic i entra a `http://localhost:PORT/`.

## Pàgines (navegació per hash `#/ruta`)

Inici · Sobre mi · Serveis · Consulta · Tallers · Club Hípic Julivert ·
Contacte · FAQs · Blog · Blogpost

## Imatges

`images/` conté les **26 imatges reals** del projecte de disseny, en format
**WebP** (2,2 MB en total). Originalment eren PNG i ocupaven 46,6 MB, cosa que
feia que la web trigués massa a carregar.

- Fotografies: WebP amb qualitat 82 i el costat llarg limitat a 1600 px.
- Els dos logotips: WebP sense pèrdua, per conservar la transparència.

Els PNG originals no s'han perdut: es poden recuperar de l'historial de git
amb `git checkout e5ed771 -- images/`.

Si vols canviar una imatge, substitueix el fitxer mantenint el mateix nom
(i la mateixa extensió `.webp`).
