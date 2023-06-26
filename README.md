# Xplab-Stage

Questa è la raccolta dei progetti realizzati durante le tre settimane di stage presso [Xplab S.a.s.](http://xplab.net/), dal 12/06/2023 al 30/06/2023
L'obiettivo era di realizzare un piccolo programma per ogni nuova libreria imparata, in modo da prendere dimestichezza con la stessa. Sono tutti realizzati nel linguaggio proprietario della Xplab, [Power-KI](http://power-ki.com/) ed il mio livello di conoscenza del linguaggio all'arrivo in azienda era nullo.
### Ciao-01 e Ciao-02
I primi due programmi realizzati nel primo giorno di stage, ciao-01 è un programma da riga di comando(CLI), invece ciao-02 sfrutta le funzionalità GUI di Power-KI. Questi due esercizi fanno parte della rivista [Fast.Track-01](https://issuu.com/xplab/docs/pwk-ft-01-it) e servono come punto di partenza per conoscere l'ambiente Power-KI.

<img style="object-fit:cover; width:100%" src="https://i.ibb.co/1dPdMVS/ciao-01.png" >
<img style="object-fit:cover; width:100%" src="https://i.ibb.co/hL64cBB/ciao-02.png" >

### Agenda-01
Questo programma non è stato realizzato da noi ma abbiamo assistito uno degli sviluppatori della XpLab che, programmando e spiegando, ci illustrava alcune funzionalità del linguaggio, in particolare ci ha introdotto alla struttura dati "Table".

<img style="object-fit:cover; width:100%" src="https://i.ibb.co/WvB6KM2/agenda-01.png" >

### Scherzo-01
Questo programma è una versione modificata del "Ciao-02", che rende impossibile per l'utente cliccare il tasto INVIA spostandolo e cambiandogli dimensione.

<img style="object-fit:cover; width:100%" src="https://i.ibb.co/sQ9v0j1/scherzo-01.png">

### Rete-01
Questo programma sfrutta il protocollo UDP per creare uno scambio di messaggi tra due o più host sfruttando la libreria SOK per le operazioni con le socket. Nella casella di input in alto basta inserire l'ip del destinatario e, se esso è in ascolto, riceverà il messaggio e lo visualizzerà nel riquadro centrale.

<img style="object-fit:cover; width:100%" src="https://i.ibb.co/qxkDF5z/rete-01.png">

### Realsense-01
Questo programma sfrutta due [dll](https://en.wikipedia.org/wiki/Dynamic-link_library) create ad hoc per la [Intel Realsense D435](https://www.intelrealsense.com/depth-camera-d435/) e mostra contemporaneamente le 4 diverse modalità di visione del dispositivo.

<img style="object-fit:cover; width:100%" src="https://i.ibb.co/9GgSPpv/realsense-01.png">

### Point-drawer-01
In questo programma si fa uso della funzionalità DRAW delle immagini inserite in una GUI. L'interfaccia è composta da tre sezioni:
- Quella a destra è il pannello su cui vengono disegnati i punti
- Quella a sinistra è una grid con tutti i punti che sono stati creati
- La sezione in basso a sinistra rappresenta l'input: una casella per il colore in formato [HEX](https://en.wikipedia.org/wiki/Web_colors#Hex_triplet), una per la X del punto e una per la Y.

<img style="object-fit:cover; width:100%" src="https://i.ibb.co/gtcWqVr/point-drawer-01.png">

### Gui-02
Questo programma è composto da due diverse GUI, una è una modifica di quella del Point-drawer precedente, l'altra è dedicata esclusivamente alla selezione e alla creazione dei colori.

<img style="object-fit:cover; width:100%" src="https://i.ibb.co/f2HH44C/grid-02-1.png">
<img style="object-fit:cover; width:50%" src="https://i.ibb.co/ySWwvjZ/grid-02-2.png">

### File-transfer
Di questo programma sono state realizzate 3 vesioni diverse: file-transfer-02, file-transfer-03 e file-transfer-04. Tra il primo e il secondo c'è stato un redesign dell'interfaccia, mentre nel file-transfer-04 è stato introdotto il trasferimento di file a segmenti. Questo semplice programma gui permette di inviare dei file ad un host conoscendo il suo indirizzo ip; in una grid in basso è possibile visualizzare la cronologia dei trasferimenti.

<img style="object-fit:cover; width:100%" src="https://i.ibb.co/WWVx4tr/file-transfer-02.png">
<img style="object-fit:cover; width:100%" src="https://i.ibb.co/RGKC7rJ/file-transfer-04.png">

### Agenda-02
L'interfaccia del programma è identica a quella di agenda-01, ma al posto che utilizzare una table si fa uso di un database SQLite.

<img style="object-fit:cover; width:100%" src="https://i.ibb.co/WvB6KM2/agenda-01.png" >

### Web-01
Questo programma è un piccolo browser che sfrutta il componente Webfast di Power-KI per inserire un'interfaccia web in una gui.

<img style="object-fit:cover; width:100%" src="https://i.ibb.co/cvmJtpC/web-01.png">

### Native-cloud-01
Questo è un programma di test che abbiamo realizzato con l'obiettivo di imparare a utilizzare le remote gui, cioé delle gui hostate su un altra macchina rispetto a quella che si sta utilizzando, ma accessibili in modo remoto conoscendo l'ip della macchina esecutrice del package .pwk.

<img style="object-fit:cover; width:50%" src="https://i.ibb.co/nPTBTWM/native-cloud-01-1.png">
<img style="object-fit:cover; width:50%" src="https://i.ibb.co/4Fyp8V6/native-cloud-01-2.png">

### Server-remote-01
Questo è stato sicuramente il programma più complesso realizzato fino ad ora. E' un file explorer con le funzionalità di:
- Creazione cartelle
- Rinomina file/cartelle
- Eliminazione file/cartelle
- Upload file
- Download file
L'intero programma viene eseguito su una gui remota. Questo permette di avere uno scambio di file comodo e semplice da usare tra due o più macchine, idealmente un server e tanti client collegati al server su cui caricano dati.
