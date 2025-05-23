# Descrizione dei Passaggi effettuati (`Stitch1.blend` - Busto)
Per la creazione del busto è stato necessario l'utilizzo dell'oggetto Cube, selezionabile con il comando `Shift + A`.
Questo comando apre una finestra da cui si possono aggiungere diversi oggetti e dove si potrà
selezionare la Mesh che vogliamo, ovvero `Mesh > Cube`.

<img src = "../image/menu.PNG" width = "250"> 

Il cubo scelto è stato allargato in altezza (`S + Z`) e in lunghezza (`S + X`), per farlo assomigliare
ad un busto (inizialmente senza forma). Poi si passa in Edit Mode (`Tab`) e si
usa il comando `Ctrl + R`, usando i Loop Cut, per poter creare una nuova linea centrale utile 
per la suddivisione successiva delle varie parti del corpo.

<img src = "../images/bustoS.png" width = "250">


Per eliminare la forma rigida della Mesh bisognerà applicare un Modifier (in basso a destra di Blender), il 
Subdivision Surface (`Add Modifier > Generate > Subdivision Surface`).

<img src = "../images/busto.png" width = "250">

Alla base della progetto vi è l'utilizzo dell'oggetto Cube, quindi i procedimenti per la manipulazione di questi oggetti saranno molto simili.
