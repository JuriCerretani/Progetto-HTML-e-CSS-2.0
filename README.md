# Sito di Juri Cerretani

## Struttura del sito
La cartella di questo progetto è molto semplice.
Troviamo un index.html che è il file che definisce la vera e propria struttura del sito e 3 cartelle:
* CSS
* JS
* SRC
Come si intuisce dal nome nella cartella CSS e JS si sono i file .css che definiscono lo stile e i file .js che ho implementato ma che coprono un ruolo puramente estetico, 
la cartella SRC invece contiene le immagini, video e logo utilizzati nella pagina.

l'index.html è strutturato in questo modo:
* Header
* Window
* About
* Skill
* Footer

### Header

L'Header è una semplice barra di navigazione che serve a spostare l'utente nella pagina web.
E' formato da 3 pulsanti Home , About e Skills.
I pulsanti sono associati ad una libreria che ho importato chiamata scrollspy che permette di associare un 'anchor' ad una sezione specifica della pagina senza dover ricaricare nulla rendendo l'esperienza utente più fluida.

### Window

La sezione Window è una sorta di vetrina che appare all'utente
con un video in background ed il mio nome e ruolo.
Nel file Css ho aggiunto anche un'immagine gradient nera come sfondo che rende più scuro lo sfondo dove appaiono le scritte per rendele più visibili.

### About 

Nella sezione About Me ho disposto un'immagine che occupa il 60% dello spazio e il restante 40% l'ho sfruttato per poter inserire il contenuto inerente alle mie informazioni personali, le mie esperienze ecc.

### Skill

La sezione Skills invece è Css puro, sono riuscito a riprodurre una semplice interfaccia che mostra le mie skill e ne evidenzia lo 'skill level' tramite delle barre che vanno da 1 a 5.

### Footer

Il Footer riprende gli stessi colori dell'Header e contiene i loghi di GitHub , Instagram e Gmail.
Essi una volta cliccati rimandano ai miei rispettivi profili

## Responsive
La features che ho voluto ottimizzare è il responsive.
Infatti ho implementato nel Css dei frammenti di codice che tramite delle query rilevano la grandezza del dispositivo utilizzato e adatta il sito in base ad esso.
Per esempio ho scelto che i visitatori da smartphone non vedono l'Header perché avendo uno schermo gia piccolo potrebbe risultare eccessivo e al posto dell'Header ho aggiunto un pulsante con una freccia in basso a sinistra che l'utente da cellulare può utilizzare per tornare all'inizio della pagina (odiamo tutti scrollare dall'alto verso il basso)

