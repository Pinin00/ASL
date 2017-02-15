# Drone

### Durante questa esperienza cercheremo di capire come è fatto un drone e come assemblarlo. 
### Per fare ciò abbiamo diviso le classi 3A Automazione e 3 A Elettronica in tre gruppi di ricerca: ogni gruppo ha al suo interno 7/8 persone della classe di Automazione e 4/5 della classe di Elettronica.
### Ogni persona all'interno del gruppo ha un ruolo e dei compiti diversi, ad esempio abbiamo il Surfatore del web, l'artigiano, il mediatiore, il reporter, il nerd, il pilota e il copilota.


![foto da fabio spinelli](https://cloud.githubusercontent.com/assets/25582920/22729449/120326ba-ede3-11e6-807d-0c6e17827b5c.jpg)
### Questi siamo noi poco prima di iniziare il primo vero giorno di lavoro.


# **Principali lavori dei componenti del gruppo:**

## **Surfatori:** hanno stilato una lista relativa ai migliori siti e/o canali di Youtube:

### - [Helipal](https://www.youtube.com/channel/UCGrIvupoLcFCW3CIKvfNfow)

#### Canale Youtube che tratta dell'argomento dei droni in generale. Uno dei più importanti in questo ambito, grazie al fatto che carica anche video di programmazione e perché è uno dei pochi canali Youtube che trattano solo quest'argomento.
### Voto: 8.5
---

### - [BaroneRosso.it](http://www.baronerosso.it/forum/multirotori-droni-principianti/)

#### Forum specializzato nel modellismo, ha anche una sezione dedicata al mondo dei droni. 
#### Come in tutti i forum la gente pone domande e degli esperti che prontamente rispondono al fine di aiutare gente che ha preso un drone ma che ha qualche problema nel farlo funzionare. 
### Voto: 9
---

### - [RCgroups](https://www.rcgroups.com/fpv-racing-926/)

Forum inglese specializzato sui droni. Sembra quasi la versione in inglese di BaroneRosso.it, anche se sembrebbe avere qualche particolare in meno. 
### Voto: 9
---

## **Copiloti:** hanno cercato e trovato alcuni Software per la configurazaione dei droni. Ecco qua riportato il più significativo:


### **UGC** 
![blup](https://cloud.githubusercontent.com/assets/25582920/22690611/f99f771a-ed36-11e6-93f1-a988c5dda5e8.jpg)

#### **UGC** è un software multipiattaforma per la programmazione dei droni. L'obiettivo di **SPH** Engineer, i ragazzi che hanno sviluppato questo programma era proprio quello di creare un Software che potesse funzionare con ogni tipo di veicolo a pilotaggio remoto e con ogni tipo di drone, visto che fino a quel momento ogni veicolo aveva un proprio Software di controllo, completamente diverso da tutti gli altri. Questo Software può essere utilizzato su diverse piattaforme **UAV**.

![hahahhahahahjajajajja](https://cloud.githubusercontent.com/assets/25582920/22690918/3a118b5c-ed38-11e6-8961-29055bf8bb54.jpg)

#### I velivoli a pilotaggio remoto,(*RPAS** in inglese o **SAPR** in italiano) meglio noti come droni, possono eseguire lavori ripetitivi, di precisione per attività di monitoraggio, rilievi fotogrammetrici o agricoltura di precisione, ma ogni piattaforma necessita del proprio software di controllo. Una azienda lettone propone una opzione alternativa.
#### Dentro alle **GroundStation** girano diversi software, alcuni specifici e proprietari come quelli **DJI** per le loro piattaforme, altri **Open Source** per prodotti **APM, PixAwk** e in genere. Questi programmi sia per Windows che per Linux e in alcuni casi anche per Mac hanno i loro equivalenti per Android e **IOS.**
#### In un contesto poliedrico come quello attuale, spesso gli operatori professionali, ma anche gli hobbysti, si trovano a dover installare e soprattutto imparare molteplici programmi diversi a seconda del tipo di drone utilizzato. L'azienda sopra citata presenta una interessante soluzione multipiattaforma che dovrebbe bypassare questo antipatico inconveniente.
#### Il programma si chiama **UGS** acronimo di **Universal Ground Control**, ed è prodotto da **SPH** Engineering, situata a Riga, in Lettonia, ma  dal 15 luglio u.s. con sede anche in Cina.
#### Al momento compatibile con **Microdrones, Mikrokopter** e grazie al protocollo open **MavLink** a tutti i progetti compatibili con **ArduCopter**; espandibile in futuro ad altri protocolli grazie a librerie e tool **SDK**.
#### Il software sulla carta si presenta come i concorrenti gestendo tranquillamente missioni, pianificazioni di rotte, azioni da svolgere su singolo waypoint e sopratutto gestire diversi tipi di veicoli o velivoli in questo caso.



### **Pregi** e **difetti** di questo Software:

#### Sicuramente un dei maggiori pregi di UGC è la semplicità con cui si può applicare velocemente i propri cambiamenti, anche se in questo ultimo periodo stanno cercamdo un modo per poter programmare il volo del drone con un unico programma, riducendo il tempo impiegato e aumentando la facilità di modifica alle stringhe.
#### D'altro canto ha un unico difetto, comune a tutti i droni da corsa: non si può elaborare con un solo programma tutta la programmazione del drone, ma necessita di alcuni programmi, diversi a seconda del tipo del drone.



# SOURCE FILE DI CLEANFLIGHT 
#### questi sono il file di sistema del nuovo programma 
![cattura di schermata 7](https://cloud.githubusercontent.com/assets/25582920/22817379/33fe80b8-ef67-11e6-8fd5-e38700fc5fb4.png)

#### Abbiamo dovuto utilizzare il software CleanFlight poiché UGC non può essere utilizzato con il nostro drone perché non è compatibile. Questo programma è abbastanza semplice, i file sono scritti in JavaScript, in html, scable vector,ruby.

![screenshot 2](https://cloud.githubusercontent.com/assets/25582271/22919278/3a638720-f28f-11e6-8ca4-761e0b492d1c.png)

#### Questo è uno screenshot di una discussione su [baronerosso.it``](http://www.baronerosso.it/forum/flight-controller-schede-di-volo-motori-e-regolatori/332346-cleanflight-speedyflight-aka-baseflight-multiwii.html)  in cui si discute e gli esperti cercano di spiegare in particolare la differenza dei vari Flight.



![screenshot 3](https://cloud.githubusercontent.com/assets/25582271/22919600/085fb378-f291-11e6-8818-a753af58fbd5.png)

#### Tramite questo link si accede ad un sito, [thrustworx.com](http://thrustworx.com/how-to-install-cleanflight-cc3d-guide/), che fornisce un introduzione base sul programma.



https://github.com/cleanflight/cleanflight-configurator

#### Link al codice sorgente del programma.



https://github.com/cleanflight/cleanflight/blob/master/docs/Getting%20Started.md

#### Spiegazione su come flashare il flight controller



http://www.4-drone.net/community/threads/guida-in-italiano-alla-naze32-rev5.26/

#### Spiegazione passo per passo di programmare un drone con il Software CleanFlight.



https://github.com/cleanflight/cleanflight/blob/master/docs/Failsafe.md

#### Link ad una fase failsafe per la programmazione.



https://github.com/cleanflight/cleanflight/blob/master/docs/PID%20tuning.md

#### Link ad una fase pid tunning per la programmazione.



https://github.com/cleanflight/cleanflight/blob/master/docs/Modes.md

#### Scheda "Modes" per la programmazione
