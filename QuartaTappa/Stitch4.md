## Descrizione dei Passaggi effettuati (Stitch4)
Per la creazione delle braccia, invece, i passaggi iniziali sono sempre i medesimi fatti finora: 
- prendere il Cube (`Shift + A, Mesh > Cube`);
- posizionarlo vicino al busto (`G`) e ruotarlo di pochi gradi verso l'alto (`R`)
- in Edit Mode aggiungiamo due Loop cut, uno verso il centro e l'altro verso la base inferiore del braccio
- deformarlo per fare in modo che assomigli al braccio di Stitch, prendendo i vertici superiori ed inferiori della figura con `S + X` per stringerli e la linea centrale, sempre con `S + X` per allungarlo
- applichiamo il Modifier Subdivision Surface (`Add Modifier > Generate > Subdivision Surface`)
- aggiungere Shade Smooth (tasto destro sull'oggetto > `Shade Smooth`)

    - <img src = "../images/braccio.png" width = "260">


- per poter ottenere due braccia uguali si applica il modifier Mirror(`Add Modifier > Generate > Mirror`) con oggetto di riferimento il busto creato in precedenza
    - <img src = "../images/duebraccia.png" width = "260">



- aggiungere il Modifier Subdivision Surface (`Add Modifier > Generate > Subdivision Surface`)
- aggiungere Shade Smooth (tasto destro sull'oggetto > `Shade Smooth`)