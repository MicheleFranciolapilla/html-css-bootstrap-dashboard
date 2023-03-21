# BOOTSTRAP DASHBOARD #

---

## Esercizio incentrato su una dashboard (web app 100vh - desktop mode) responsive (mobile first) ##

---

**Gli elementi della pagina sono i seguenti:**
- *Header (`fixed`) contenente logo (responsive) e navbar (responsive)*
- *Side bar (`fixed`) con menu verticale (responsive)*
- *Corpo centrale, contenente cinque sezioni, la cui disposizione varia al variare del device. Il corpo centrale, presenta una scrollbar dedicata.*

---

**Lo spazio occupato dai singoli elementi, oltreche' la loro disposizione, sono responsive.**

**Oltre all'utilizzo dei breakpoints tipici di Bootstrap (xs, sm, md, lg) vi sono anche delle media queries nel foglio di stile:**

- **`@media only screen and (min-width: 576px)`** *in cui il logo nello header viene adattato ad uno spazio utile che passa da 2/12 ad 1/12 ed il menu della side_bar (icone + testo) subisce un ridimensionamento di font*
- **`@media only screen and (min-width: 992px)`** *in cui il menu verticale della side_bar passa da una visualizzazione a sole icone ad una visualizzazione di tipo icona + testo. In questa fase si pratica un allineamento fine (al pixel) delle icone e del relativo testo di fianco, a prescindere dalle dimensioni differenti delle varie icone.*
- **`@media only screen and (min-width: 1200px)`** *in cui, il cambiamento piu' significativo sta nell'**offcanvas** che passa da una copertura del 100% in larghezza ad una del 50%.*
- **`@media only screen and (max-height: 500px)`** *nel quale si incrementano le dimensioni dello header (altezza) per compensare la rigidita' della navbar.*

---

*Gli elementi (sezioni) al centro dell'area principale sono:*

- *un rigo centrale (width 100% del corpo centrale) in cui sono presenti testo, badges e tasto di apertura offcanvas*
- *una tabella responsive contenente testo, icone, badges,....*
- *una sezione f.a.q. realizzata mediante "Bootstrap Accordion"*
- *una checklist con le "things to do"*
- *una card (Bootstrap card) con grafico (immagine) ed elementi testuali e link*.

---

***La pagina e' estremamente flessibile ed adattabile ai vari device e mantiene una perfetta struttura fino a valori inferiori a 350 pixel (vw) e 350 pixel (vh)***