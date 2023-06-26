# Xplab-Stage

Questa è la raccolta dei progetti realizzati durante le tre settimane di stage presso [Xplab S.a.s.](http://xplab.net/), dal 12/06/2023 al 30/06/2023
L'obiettivo era di realizzare un piccolo programma per ogni nuova libreria imparata, in modo da prendere dimestichezza con la stessa. Sono tutti realizzati nel linguaggio proprietario della Xplab, [Power-KI](http://power-ki.com/) ed il mio livello di conoscenza del linguaggio all'arrivo in azienda era nullo.
---
### Ciao-01 e Ciao-02
I primi due programmi realizzati nel primo giorno di stage, ciao-01 è un programma da riga di comando(CLI), invece ciao-02 sfrutta le funzionalità GUI di Power-KI. Questi due esercizi fanno parte della rivista [Fast.Track-01](https://issuu.com/xplab/docs/pwk-ft-01-it) e servono come punto di partenza per conoscere l'ambiente Power-KI.

![ciao-01](https://github.com/Ale-Ceresa/XPLab-Stage/assets/92877764/abaf4a35-ec50-437d-bfe9-95d29cc903bb)
![ciao-02](https://github.com/Ale-Ceresa/XPLab-Stage/assets/92877764/e61c133f-1a92-45d8-b13b-cb0d72357f90)
---
### Agenda-01
Questo programma non è stato realizzato da noi ma abbiamo assistito uno degli sviluppatori della XpLab che, programmando e spiegando, ci illustrava alcune funzionalità del linguaggio, in particolare ci ha introdotto alla struttura dati "Table".

![agenda-01](https://github.com/Ale-Ceresa/XPLab-Stage/assets/92877764/5e6128fd-a8e1-4050-9f0a-3d217690bba8)
---
### Scherzo-01
Questo programma è una versione modificata del "Ciao-02", che rende impossibile per l'utente cliccare il tasto INVIA spostandolo e cambiandogli dimensione.

![scherzo-01](https://github.com/Ale-Ceresa/XPLab-Stage/assets/92877764/8ac762cd-018f-4c56-b6bb-02969a1968aa)
---
### Rete-01
Questo programma sfrutta il protocollo UDP per creare uno scambio di messaggi tra due o più host sfruttando la libreria SOK per le operazioni con le socket. Nella casella di input in alto basta inserire l'ip del destinatario e, se esso è in ascolto, riceverà il messaggio e lo visualizzerà nel riquadro centrale.

![rete-01](https://github.com/Ale-Ceresa/XPLab-Stage/assets/92877764/e781d573-125b-4179-840b-4f7999c3de1c)
---
### Realsense-01
Questo programma sfrutta due [dll](https://en.wikipedia.org/wiki/Dynamic-link_library) create ad hoc per la [Intel Realsense D435](https://www.intelrealsense.com/depth-camera-d435/) e mostra contemporaneamente le 4 diverse modalità di visione del dispositivo.

![realsense-01](https://github.com/Ale-Ceresa/XPLab-Stage/assets/92877764/6beb69e5-8a28-4e52-a733-a166c7180909)
---
### Point-drawer-01
In questo programma si fa uso della funzionalità DRAW delle immagini inserite in una GUI. L'interfaccia è composta da tre sezioni:
- Quella a destra è il pannello su cui vengono disegnati i punti
- Quella a sinistra è una grid con tutti i punti che sono stati creati
- La sezione in basso a sinistra rappresenta l'input: una casella per il colore in formato [HEX](https://en.wikipedia.org/wiki/Web_colors#Hex_triplet), una per la X del punto e una per la Y.

![point-drawer-01](https://github.com/Ale-Ceresa/XPLab-Stage/assets/92877764/b70cf02a-e737-49a1-994c-96ba405d1096)
---
### Grid-02
Questo programma è composto da due diverse GUI, una è una modifica di quella del Point-drawer precedente, l'altra è dedicata esclusivamente alla selezione e alla creazione dei colori.

![grid-02(1)](https://github.com/Ale-Ceresa/XPLab-Stage/assets/92877764/7f8714fb-b1c1-4a47-a2ac-bf8c98fcc1b5)
![grid-02(2)](https://github.com/Ale-Ceresa/XPLab-Stage/assets/92877764/9af39d35-8219-4f85-84c4-187f2ced3501)
---
### File-transfer
Di questo programma sono state realizzate 3 vesioni diverse: file-transfer-02, file-transfer-03 e file-transfer-04. Tra il primo e il secondo c'è stato un redesign dell'interfaccia, mentre nel file-transfer-04 è stato introdotto il trasferimento di file a segmenti. Questo semplice programma gui permette di inviare dei file ad un host conoscendo il suo indirizzo ip; in una grid in basso è possibile visualizzare la cronologia dei trasferimenti.

![file-transfer-02](https://github.com/Ale-Ceresa/XPLab-Stage/assets/92877764/fa5726bb-e809-4552-8255-ddbb8dca71b3)
![file-transfer-04](https://github.com/Ale-Ceresa/XPLab-Stage/assets/92877764/d8a8f021-7e19-4cae-8395-ace3cac48a50)
---
### Agenda-02
L'interfaccia del programma è identica a quella di agenda-01, ma al posto che utilizzare una table si fa uso di un database SQLite.

![agenda-02](https://github.com/Ale-Ceresa/XPLab-Stage/assets/92877764/5e6128fd-a8e1-4050-9f0a-3d217690bba8)
---
### Web-01
Questo programma è un piccolo browser che sfrutta il componente Webfast di Power-KI per inserire un'interfaccia web in una gui.

![web-01](https://github.com/Ale-Ceresa/XPLab-Stage/assets/92877764/c64fb9c5-0c57-48f5-a6d9-8a7013838595)
---
### Native-cloud-01
Questo è un programma di test che abbiamo realizzato con l'obiettivo di imparare a utilizzare le remote gui, cioé delle gui hostate su un altra macchina rispetto a quella che si sta utilizzando, ma accessibili in modo remoto conoscendo l'ip della macchina esecutrice del package .pwk.

![native-cloud-01(1)](https://github.com/Ale-Ceresa/XPLab-Stage/assets/92877764/d2a24c07-440e-429b-aa42-4941200c39cf)
![native-cloud-01(2)](https://github.com/Ale-Ceresa/XPLab-Stage/assets/92877764/7a77be01-41c7-4e59-be2a-3cd0f874f03d)
---
### Server-remote-01
Questo è stato sicuramente il programma più complesso realizzato fino ad ora. E' un file explorer con le funzionalità di:
- Creazione cartelle
- Rinomina file/cartelle
- Eliminazione file/cartelle
- Upload file
- Download file

L'intero programma viene eseguito su una gui remota. Questo permette di avere uno scambio di file comodo e semplice da usare tra due o più macchine, idealmente un server e tanti client collegati al server su cui caricano dati.

![server-remote-01(1)](https://github.com/Ale-Ceresa/XPLab-Stage/assets/92877764/48220ff8-60c2-4d4c-900f-840f3741f2f1)
![server-remote-01(2)](https://github.com/Ale-Ceresa/XPLab-Stage/assets/92877764/4dbb1d68-2069-4b22-a289-cd94366ab480)
![server-remote-01(3)](https://github.com/Ale-Ceresa/XPLab-Stage/assets/92877764/7539013c-11e5-4107-8c82-79b25b544285)
