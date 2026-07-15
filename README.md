# D'Annunzio e il Déco

Progetto di digital humanities dedicato al legame tra Gabriele D'Annunzio e il gusto Art Déco italiano tra Otto e Novecento: un catalogo di opere, artisti, materiali/tecniche e luoghi che hanno costruito l'estetica decorativa del periodo dannunziano.

## Struttura del sito

- **Home** (`index.html`) — pagina d'ingresso con accesso al progetto
- **Il progetto** (`pages/ilprogetto.html`) — presentazione del progetto e dei suoi obiettivi
- **Catalogo** (`pages/catalogo.html`) — schede degli oggetti, filtrabili per tipologia (dipinti, sculture, oggetti d'arte, archivio)
- **Materiali e tecniche** (`pages/materialitecniche.html`) — vetro muranese, ferro battuto, ceramica, tessili e altre arti decorative
- **Artisti** (`pages/persone.html`) — pittori, scultori, fabbri d'arte, committenti e imprenditori, filtrabili per ruolo
- **Luoghi** (`pages/luoghi.html`) — musei, case museo e manifatture, con mappa interattiva
- **Schede oggetto** (`pages/items/`) — pagine di dettaglio delle singole opere, con metadati scaricabili
- **Pagine artista/luogo/tecnica** (`pages/artistiluoghitecniche/`) — approfondimenti monografici

## Struttura delle cartelle

```
assets/css/      fogli di stile (style1.css per le pagine interne, styleindexclaude.css per la home)
assets/images/   immagini e icona del sito
data/            metadati delle opere in formato LIDO (XML) e EDM/RDF (Turtle)
pages/           tutte le pagine del sito
```
.

## Tecnologie e standard usati

- **Bootstrap 5** (via CDN) per la struttura grafica
- **Leaflet** per la mappa interattiva dei luoghi
- **LIDO** (*Lightweight Information Describing Objects*) per la schedatura delle opere
- **EDM/RDF** (Europeana Data Model) per l'interoperabilità dei metadati con Europeana
