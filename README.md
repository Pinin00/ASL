# **DRONE**
Lo scopo di quest'esperienza è capire il funzionamento di un drone e  studiarne i componenti di cui è costituito. 
Nella prima lezione di alternanza vi è stato illustrato e spiegato l'argomento dei droni, attraverso video e presentazione Power Point. Una volta terminato questo passaggio, vi è stata la formazione dei gruppi di lavoro composti da 7/8 alunni della classe 
3°A AUTOMAZIONE e 4 alunni della classe 3°A ELETTRONICA. Una volta terminata la composizione dei gruppi, sono stati esposti e assegnati i ruoli che ogni membro del gruppo dovrà svolgere. I ruoli sono: pilota(1), copilota(2), artigiano(1), mediatore(2), reporter(2), surfatore del web(2), nerd(2). Il drone su cui è stato assegnato il lavoro è il **EACHINE 250 RACER**.
![images](https://cloud.githubusercontent.com/assets/25583168/22731767/0fc5b062-edec-11e6-943b-b78b5dae44e2.jpg)

#Le caratteristiche di questo drone sono:

- MARCA: Eachine;
- MODELLO: Racer 250;
- DIMENSIONI: 1220 x 233 x 50;
- PESO:  400g;
- MOTORE: Brushless 2204 2300kV;
- DURATA BATTERIA: 10-14m;
- PREZZO: 93-262€;                                         

#I    TRUMUN                                                                                                                         ![copia di 2017-02-08-photo-00000248](https://cloud.githubusercontent.com/assets/25583168/22821436/57f63d76-ef7b-11e6-9fb5-ac0fe0f48a26.jpg)
    

La scadenza stabilita per terminare il lavoro assegnatoci è stata fissata per il  giorno VENERDI 18 FEBBRAIO 2017; inoltre è necessario seguire i seguenti obiettivi entro la data prestabilita:
- rientrare nell'investimento del budget economico;
- creare un drone di alto valore nel mercato dei droni da corsa.

# **PRIMA LEZIONE**
- **Il surfatore del web** aveva il compito di trovare delle risorse sui droni, commentarle e darle un voto.
    - ABC Droni -> VOTO 10/10. Sito completo, ti permette di acquistare droni e componenti, consultare recensioni con spiegazioni                                      approfondite su come fare volare un drone ed elenca le norme di sicurezza;
    - Rensioni droni -> VOTO 8/10. Sito specializzato in recensioni, test e prove sui migliori droni in commercio,propone dei tutorial                                      interessanti,però si occupa solo di droni professionali,quindi non adeguato per dilettanti; 
    - Video 3, "COSE CINESI" -> VOTO 8/10. Recensione completa di un drone,si possono migliorare le riprese.
- **L'artigiano** ha prodotto dei cartellini con scritto il nome del gruppo, il nome della persona ed il ruolo.
- **Il reporter** ha fatto una foto di gruppo ed ha creato delle slide di presentazione di esso. 
- **Il mediatore** ha organizzato la comunicazione con un gruppo Whatsapp, ed ha creato un gruppo su google Drive per far si che tutti i   membri possano avere a disposizione i lavori di ognuno.
- **Il nerd** ha creato account su Githup in cui ha scritto una presentazione iniziale del progetto ed ha caricato il tutto sul file       README.md.
- **Il pilota** ha recuperato un drone d'allenamento.
- **Il copilota** ha cercato i principali software di configurazione dei droni racer come "Drone Racer Setting Manager", "UgCS",           "Freerider", "Open Pilot" elencandone i pregi ed i difetti, ma è stato scelto "CLEANFLIGHT" perchè è un software più leggero e adatto   al drone da gara, a diferrenza di altri programmi che erano troppo pesanti e avevano troppe funzioni a noi inutili.

# **COMMENTO DEL CODICE SORGENTE DI CLEANFLIGHT**
![image](https://cloud.githubusercontent.com/assets/25583168/22732747/acb553c0-edef-11e6-988a-0221db9574cc.png)
Il codice sorgente in informatica è il testo di un algoritmo di un programma scritto in un linguaggio di programmazione. E' scritto con il linguaggio in C, e ci sono dichiarazioni delle variabili. Il file eseguibile del programma si converte in un alfabeto binario, composto da una lunga serie di 0 e 1. Guardando nelle "ISSUES" del sito si vede che ci sono delle discussioni chiamate "Volo autonomo senza alcun input", "dispendio di batteria" ed altri commenti su come far funzionare il programma.

# **SECONDA LEZIONE**
- **L'artigiano** ha smontato il drone ed ha conservato tutti i pezzi, queste sono le foto scattate dai reporter:
![20170208_092544](https://cloud.githubusercontent.com/assets/25583168/22821758/cf4fa938-ef7c-11e6-8fed-1604badf7ab5.jpg)
- **Il reporter** ha creato un tutorial in stile instructables e documentare con foto tutte le fasi di smontaggio del drone;
- **Il surfatore del web** ha cercato su internet i pezzi che compongono il drone con il loro prezzo ed ha calcolato il totale della spesa che non doveva superare i 250€;
- **Il mediatore** ha organizzato tutte le informazioni dei vari membri del gruppo e le hanno date ai nerd, hanno anche fatto riunioni di inizio e fine lavoro;
- **Il nerd** ha trovato il file sorgente del programma cleanflight e lo ha dato ai copiloti;
- **Il pilota** ha cercato le modalità di volo ed il funzionamento di un radiocomando;
- **Il copilota** ha cercato il software di volo ed ha cercato la sua documentazione ufficiale.

# **TERZA LEZIONE**
- **Il copilota** ha flashato il microcontrollore del drone e lo ha programmato;
- **Il pilota** ha fatto dei voli di prova ed ha settato il radiocomando;
- **Il nerd** ha aiutato i copiloti a flashare cleanflight ed ha creato una quarta repo in comune con tutti i gruppi;
- **L'artigiano** ha generato un segnale PWM ed ha preparato un campo di prova per la prossima lezione;
- **Il reporter** ha documentato il lavoro dell'artigiano ed ha caricato il tutto su instructables in inglese;
- **Il surfatore del web** ha cercato caratteristiche, prezzi e marche dei droni da corsa ed ha fatto delle slides sulle gare;
- **Il mediatore ha fatto delle riunioni di inizio e fine lavoro ed ha cominciato a fare delle slides di presentazione del lavoro finale.


Sono state fatte degli esperimenti con vari tipi di eliche, per vedere quella che usava più corrente e che erogava più forza. Qui sotto i dati dell'esperienza:
ELICA	        Kgf	        A	    f/A
Standardkit	    0.310	    9.1	    34.06
Rigida	        0.351   	9.6	    36.56
5040	        0.345	    9.4	    36.70
Piccola 	    0.189	    4.4	    42.95
Pala corta	    0.185	    5.4	    34.26
2° Pala lunga 	0.267	    8.9	    30.00
Tripala	        0.280	    9.0	    31.11
