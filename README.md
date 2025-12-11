# GASPRA - Gruppo Astrofili Pescaresi "RA"

![GASPRA Logo](img/logo.jpg)

Benvenuti nel repository del sito web ufficiale del **GASPRA** (Gruppo Astrofili Pescaresi "RA"). Questo progetto ospita la vetrina digitale dell'associazione, dedicata alla divulgazione astronomica, alla ricerca e all'organizzazione di eventi osservativi nel Centro Italia.

## 🔭 Descrizione del Progetto

Questo sito web è stato recentemente modernizzato e ristrutturato per offrire una navigazione intuitiva, un design responsivo e un accesso facilitato all'archivio storico e alle nuove produzioni del gruppo. Il sito funge da punto di riferimento per soci e appassionati, fornendo informazioni su eventi, strumenti, tecniche di osservazione e gallerie fotografiche.

### Caratteristiche Principali
*   **Design Responsivo**: Layout adattabile a dispositivi mobili e desktop.
*   **Galleria Fotografica**: Sezioni dedicate alle riprese storiche e moderne (Deep Sky, Planetario).
*   **Archivio Attività**: Cronologia completa delle attività svolte dal 1999 ad oggi.
*   **Mappe Osservatori**: Schede dettagliate sui siti osservativi (Colle Leone, Capolavilla, Fonte Vetica, ecc.).
*   **Sezione Didattica e Tecnica**: Guide, tutorial e recensioni di strumentazione astronomica e autocostruzione.

## 📂 Struttura del Progetto

Il progetto segue una struttura ordinata per facilitare la manutenzione:

```
/ (Root)
├── index.html          # Home page principale
├── css/                # Fogli di stile (style.css e asset font)
├── img/                # Immagini, icone e media grafici
├── js/                 # Script JavaScript per funzionalità interattive
├── pages/              # Tutte le pagine interne (Chi Siamo, Attività, Strumenti, ecc.)
└── docs/               # Documenti scaricabili (PDF, guide)
```

## 🛠️ Tecnologie Utilizzate

*   **HTML5**: Semantica e struttura delle pagine.
*   **CSS3**: Styling moderno con Flexbox, Grid e variabili CSS per la gestione dei temi.
*   **JavaScript (Vanilla)**: Interattività leggera (menu mobile, contatori, logica UI).
*   **FontAwesome**: Iconografia vettoriale.

## 📝 Note per gli Sviluppatori

*   Il file `.nojekyll` è incluso per evitare che GitHub Pages ignori file o cartelle che iniziano con underscore (se presenti) e per servire il sito come file statici puri.
*   Per modifiche allo stile, intervenire principalmente su `css/style.css`. Le pagine interne in `pages/` fanno riferimento alle risorse risalendo di un livello (`../`).

## 👥 Contatti e Credits

**Gruppo Astrofili Pescaresi "RA"**
*   Sito Web: [www.gaspra.org](https://www.gaspra.org)
*   Partner: Forum Quasar - Dagli Appennini alle Stelle

---
&copy; 1999-2025 GASPRA. Tutti i diritti riservati.
