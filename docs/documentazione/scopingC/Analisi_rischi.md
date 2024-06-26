
<style type="text/css">
h2,h3 {
    margin:0px;
    padding:0px;
    color:#fff !important;
}

table {
    border-collapse: collapse;
    grid-template-columns: repeat(7, 1fr);
    table-layout: fixed;
    width: 100%;
}

td, th {
    width: 14.2857% !important;
    height: 100px !important;
    border: 1px solid #000;
    text-align: center;
}

.div{
    padding:10px;
    margin:10px;
}

.medium { background-color:rgba(252, 227, 3, 0.3);border-top-style: solid;
border-top-width: 2px;border-top-color: rgb(252, 227, 3);}

.medium_low { background-color:rgba(177, 252, 3, 0.3); border-top-color: rgb(177, 252, 3);border-top-style: solid;
border-top-width: 2px;}
.low { background-color:rgba(0, 175, 0, 0.3); border-top-color: rgb(0, 175, 0);border-top-style: solid;
border-top-width: 2px;}
.medium_high { background-color:rgba(252, 132, 3, 0.3);border-top-color: rgb(252, 132, 3);border-top-style: solid;
border-top-width: 2px;}
.high { background-color:rgba(250, 0, 0, 0.3);border-top-color: rgb(250, 0, 0);border-top-style: solid;
border-top-width: 2px;}
</style>

# Analisi dei rischi

La tabella dei rischi riportata di seguito è stata strutturata per rappresentare in modo chiaro e dettagliato la probabilità e l'impatto di ciascun rischio identificato nel progetto. Ogni cella della tabella contiene una stima numerica del rischio, che è il risultato della combinazione tra la probabilità di accadimento e l'impatto sul progetto. Alcuni rischi, data la loro natura, sono stati suddivisi in parti in modo da approfondire ogni aspetto singolarmente. 

- Probabilità: La colonna delle probabilità è suddivisa in cinque categorie: Irrilevante (1), Bassa (2), Moderata (3), Alta (4) ed Estrema (5).
- Impatto: La riga degli impatti è suddivisa in cinque livelli: Insignificante (1), Minore (2), Moderato (3), Maggiore (4) e Catastrofico (5).

Ogni cella della tabella contiene un numero che rappresenta la stima del rischio. Questo numero è ottenuto moltiplicando il valore assegnato alla probabilità per il valore assegnato all'impatto in modo da quantificare l'entità del rischio. 

## Livelli di rischio

<div class ="low div">
<strong>Rischio basso:</strong> I rischi in questa categoria sono di lieve entità e hanno un impatto minimo sugli obiettivi del progetto. Inoltre, è improbabile che si realizzino e, di conseguenza, che influenzino significativamente la tempistica, il budget o la qualità del progetto.
</div>

<div class ="medium_low div">
<strong>Rischio medio basso:</strong> Questi rischi possono avere un impatto o una probabilità di avvenire bassi, il che li rende gestibili. Solitamente richiedono un'attenzione più attiva per evitare che si trasformino in problemi più gravi, ma possono essere mitigati con azioni correttive standard.
</div>

<div class ="medium div">
<strong>Rischio medio:</strong> I rischi di livello medio rappresentano una minaccia che potrebbe avere un effetto tangibile sul progetto. La loro gestione richiede monitoraggio e l'implementazione di piani di mitigazione ben definiti.
</div>

<div class ="medium_high div">
<strong>Rischio medio alto:</strong> Questi rischi hanno probabilità di avvenire o impatto sul progetto alti. Necessitano di un'attenzione immediata e di piani di risposta ben strutturati per prevenire o minimizzare l'impatto negativo.
</div>

<div class ="high div">
<strong>Rischio alto:</strong> Rischi ad alto livello sono sia molto probabili che fortemente impattanti, possono dunque compromettere in modo significativo il successo del progetto. Richiedono un piano di gestione dei rischi ben dettagliato e l'impegno costante del management. Un elevato numero di rischi di tale natura può far desistere dall'intraprendere un progetto.
</div>



<table>
    <tr>
        <th colspan="2" rowspan="2"></th>
        <th colspan="5">Probabilità</th>
    </tr>
    <tr>
        <th >Irrilevante</th>
        <th >Bassa      </th>
        <th >Moderata   </th>
        <th >Alta       </th>
        <th >Estrema    </th>
    </tr>
    <tr>
        <th rowspan="5">Impatto</th>
        <th>Insignificante</th>
        <td class="low">1</td>
        <td class="low">2</td>
        <td class="medium_low">3</td>
        <td class="medium_low">4</td>
        <td class="medium">5</td>
    </tr>
    <tr>
        <th>Minore</th>
        <td class="low">2</td>
        <td class="medium_low">4</td>
        <td class="medium">6</td>
        <td class="medium">8</td>
        <td class="medium_high">10</td>
    </tr>
    <tr>
        <th>Moderato</th>
        <td class="medium_low">3</td>
        <td class="medium">6</td>
        <td class="medium">9</td>
        <td class="medium_high">12</td>
        <td class="medium_high">15</td>
    </tr>
    <tr>
        <th>Maggiore</th>
        <td class="medium_low">4</td>
        <td class="medium">8</td>
        <td class="medium_high">12</td>
        <td class="medium_high">16</td>
        <td class="high">20</td>
    </tr>
    <tr>
        <th>Catastrofico</th>
        <td class="medium">5</td>
        <td class="medium_high">10</td>
        <td class="medium_high">15</td>
        <td class="high">20</td>
        <td class="high">25</td>
    </tr>
</table>



<div class ="medium div">
<h3> 1.1 a</h3><br>
<strong> Rischio:</strong> Incontrare problemi di natura tecnologica che impediscano il rispetto dei tempi di consegna.<br>
<strong> Probabilità:</strong> Bassa 
<strong> Impatto:</strong> Maggiore 
<strong> Stima del rischio:</strong> 8<br>
<strong> Motivazione alla stima del rischio:</strong> La tecnologia è conosciuta, nonostante questo, vi è la possibilità che si verifichino problemi e i tempi di consegna rappresentano un requisito stringente.<br>
<strong> Gestione Rischio:</strong> Contingency Planning.  Conoscendo i nostri punti deboli riguardo alle tecnologie, si contatta un esperto nelle tecnologie più problematiche e si contratta un eventuale disponibilità. L'esperto sarà individuato all'interno della stessa Mintendo, in quanto maggiori esperti della console da loro prodotta.
</div>


<div class ="high div">
<h3> 1.1 b</h3><br>
<strong> Rischio:</strong> Incontrare problemi di natura organizzativa che impediscano il rispetto dei tempi di consegna.<br>
<strong> Probabilità:</strong> Alta 
<strong> Impatto:</strong> Catastrofico 
<strong> Stima del rischio:</strong> 20 <br>
<strong> Motivazione alla stima del rischio:</strong> Questo progetto è il più grande tra quelli intrapresi dall'azienda, impiegherà tutti i dipendenti per un lungo periodo di tempo e i tempi di consegna rappresentano un requisito alquanto stringente.<br>
<strong> Gestione Rischio:</strong> Mitigazione. Si effettuerà dalle fasi iniziali del progetto un'organizzazione dettagliata del lavoro, che comprenda un'attenta assegnazione dei compiti ai team, secondo le skill dei membri, nonché un'attenta valutazione delle priorità delle varie task e della loro possibile parallelizzazione.
</div>



<div class ="medium_high div">
<h3> 1.1 c</h3><br>
<strong> Rischio:</strong> Incontrare problemi dovuti all'aggiunta di nuove funzionalità che impediscano il rispetto dei tempi di consegna.<br>
<strong> Probabilità:</strong> Alta 
<strong> Impatto:</strong> Maggiore 
<strong> Stima del rischio:</strong> 16 <br>
<strong> Motivazione alla stima del rischio:</strong> Si è a conoscenza del fatto che i requisiti possono essere soggetti a cambiamenti dovuti sia al committente che ai desideri dell'utenza finale. Inoltre, i tempi di consegna sono molto stringenti.<br>
<strong> Gestione Rischio:</strong> Mitigazione. Fin dall'inizio del progetto si stabiliranno le date di meeting con il committente e con possibili suoi clienti, che avverranno in maniera frequente, in modo da individuare fin da subito eventuali problemi e le corrispondenti soluzioni.
</div>


<div class ="medium div">
<h3> 1.2</h3><br>
<strong> Rischio:</strong> Creare un videogioco troppo lontano dai moderni standard.<br>
<strong> Probabilità:</strong> Bassa 
<strong> Impatto:</strong> Maggiore 
<strong> Stima del rischio:</strong> 8 <br>
<strong> Motivazione alla stima del rischio:</strong> È cruciale attirare nuovi giocatori per mantenere attivo il brand, e come azienda abbiamo esperienza nel creare videogiochi che soddisfano l'utenza moderna.<br>
<strong> Gestione Rischio:</strong> Mitigazione. Fin dall'inizio del progetto si stabiliranno le date di meeting con possibili clienti target per effettuare usability test.
</div>



<div class ="medium div">
<h3> 1.3 </h3><br>
<strong> Rischio:</strong> Creare un prodotto non in linea con le aspettative degli appassionati di lunga data.<br>
<strong> Probabilità:</strong> Alta 
<strong> Impatto:</strong> Minore 
<strong> Stima del rischio:</strong> 8 <br>
<strong> Motivazione alla stima del rischio:</strong> I giocatori di lunga data hanno aspettative difficili da soddisfare, ma il brand non risente in modo particolare di un eventuale malcontento <br>
<strong> Gestione Rischio:</strong> Mitigazione/Contingency Plan. Fin dall'inizio del progetto si stabiliranno le date di meeting con possibili clienti target, sebbene con frequenza molto ridotta rispetto all'altra categoria di utenti. Nel caso emergano recensioni particolarmente negative dopo la release, si programma di far uscire una patch che migliori la situazione.
</div>



<div class ="low div">
<h3> 2.1</h3><br>
<strong> Rischio:</strong> Incapacità di bilanciare i contenuti nei trailer per stimolare la curiosità.<br>
<strong> Probabilità:</strong> Irrilevante 
<strong> Impatto:</strong> Minore 
<strong> Stima del rischio:</strong> 2 <br>
<strong> Motivazione alla stima del rischio:</strong> Abbiamo prodotto altri trailer; quindi, la probabilità di incorrere in errori di questo tipo è bassa, inoltre l'utenza del brand nutre un particolare interesse iniziale nei suoi confronti l'impatto è moderato per la stessa ragione. <br>
<strong> Gestione Rischio:</strong> Accettazione/Contingency Plan. Se un trailer dovesse ottenere delle reazioni particolarmente negative si potranno visionare i trailer del brand Dibimon che hanno avuto successo negli anni passati e si tenterà di produrre trailer più interessanti su questa base.
</div>



<div class ="medium div">
<h3> 2.2 </h3><br>
<strong> Rischio:</strong> 
Mostrare troppi contenuti nei trailer, rivelando eccessivamente le caratteristiche del videogioco.<br>
<strong> Probabilità:</strong> Moderata 
<strong> Impatto:</strong> Minore
<strong> Stima del rischio:</strong> 6 <br>
<strong> Motivazione alla stima del rischio:</strong> Essendo un remake, molte parti del videogioco sono ben note ai futuri utenti, inoltre le novità, per quanto presenti, sono nettamente inferiori in numero rispetto a quelle presenti in un nuovo videogioco. Ne consegue che risulta difficile mostrare delle feature nuove senza mostrarne troppe. <br>
<strong> Gestione Rischio:</strong> Mitigazione. Prima dell'ideazione del trailer si contatterà la Mintendo per decidere esattamente cosa mostrare e cosa no.
</div>


<div class ="medium div">
<h3> 2.3 </h3><br>
<strong> Rischio:</strong> Mancata approvazione del trailer da parte di Mintendo e mancanza di tempo per effettuare le modifiche necessarie.<br>
<strong> Probabilità:</strong> Moderata 
<strong> Impatto:</strong> Moderato 
<strong> Stima del rischio:</strong> 9 <br>
<strong> Motivazione alla stima del rischio:</strong> Sebbene non sia improbabile che un problema simile si verifichi, un ritardo nell'uscita del trailer non sarà particolarmente impattante. <br>
<strong> Gestione Rischio:</strong> Mitigazione. Prima dell'ideazione del trailer si contatterà la Mintendo per ottenere linee guida chiare.
</div>

<div class ="medium_high div">
<h3> 2.4 </h3><br>
<strong> Rischio:</strong> Inesperienza nella realizzazione di trailer cinematici, portando a un prodotto di bassa qualità.<br>
<strong> Probabilità:</strong> Alta 
<strong> Impatto:</strong> Moderato 
<strong> Stima del rischio:</strong> 12 <br>
<strong> Motivazione alla stima del rischio:</strong> Non abbiamo all'interno del nostro organico nessun esperto di realizzazione di trailer cinematici, conseguentemente la probabilità che il rischio si verifichi è alta portando a un primo trailer carente dal punto di vista grafico danneggiando la campagna marketing. <br>
<strong> Gestione Rischio:</strong> Evitare assegnando la realizzazione delle cinematiche in outsurcing. 
</div>

<div class ="medium_high div">
<h3> 3.1 </h3><br>
<strong> Rischio:</strong> Data mining sul contenuto del gioco.<br>
<strong> Probabilità:</strong> Estrema 
<strong> Impatto:</strong> Moderato 
<strong> Stima del rischio:</strong> 15 <br>
<strong> Motivazione alla stima del rischio:</strong> Basandoci su esperienze passate, è noto che verrà effettuato data mining sulla demo nella speranza di ottenere informazioni aggiuntive sul videogioco prima della data di uscita. L'impatto è moderato poiché ciò non influenzerà significativamente il numero di copie vendute. <br>
<strong> Gestione Rischio:</strong> Mitigazione. Conoscendo il problema, si presterà particolare attenzione nell'eliminazione di parti di codice sensibili dalla demo.
</div>

<div class ="medium_low div">
<h3> 3.2 </h3><br>
<strong> Rischio:</strong> La demo potrebbe non essere abbastanza coinvolgente o interessante da convincere i giocatori a comprare il videogioco completo.<br>
<strong> Probabilità:</strong> Irrilevante 
<strong> Impatto:</strong> Maggiore 
<strong> Stima del rischio:</strong> 4 <br>
<strong> Motivazione alla stima del rischio:</strong> Abbiamo prodotto altre demo; quindi, la probabilità di incorrere in errori di questo tipo è bassa. Tuttavia, poiché la demo ha una rilevanza significativa nella decisione di acquisto, l'impatto è maggiore.<br>
<strong> Gestione Rischio:</strong> Mitigazione. Durante la creazione della demo, si contatteranno la Mintendo e suoi potenziali clienti per ottenere pareri correttivi.
</div>

<div class ="medium_low div">
<h3> 3.3 </h3><br>
<strong> Rischio:</strong> 
La demo potrebbe rivelare troppi dettagli della trama o dei contenuti del gioco, riducendo l'interesse dei giocatori per il videogioco completo.<br>
<strong> Probabilità:</strong> Moderata 
<strong> Impatto:</strong> Insignificante
<strong> Stima del rischio:</strong> 3 <br>
<strong> Motivazione alla stima del rischio:</strong> Sebbene sia difficile mostrare nuove caratteristiche senza mostrarne troppe, l'utenza è più propensa a comprare il gioco se la demo è stata gradita, anche se mostra meccaniche che non dovevano ancora apparire. <br>
<strong> Gestione Rischio:</strong> Mitigazione. prima dell'ideazione della demo, si contatterà la Mintendo per decidere esattamente cosa mostrare e cosa no. Verrà posta particolare attenzione su cosa possa influire in modo positivo e negativo sulle vendite del videogioco.
</div>

<div class ="medium_high div">
<h3> 3.4 </h3><br>
<strong> Rischio:</strong> Mancata approvazione della demo da parte di Mintendo e mancanza di tempo per effettuare le modifiche necessarie.<br>
<strong> Probabilità:</strong> Moderata 
<strong> Impatto:</strong> Maggiore 
<strong> Stima del rischio:</strong> 12 <br>
<strong> Motivazione alla stima del rischio:</strong> È plausibile che un problema simile si verifichi, e sebbene un piccolo ritardo nell'uscita della demo non sia particolarmente impattante, un ritardo maggiore può provocare problemi di marketing. <br>
<strong> Gestione Rischio:</strong> Mitigazione. Durante la fase di ideazione della demo ogni elemento verrà prima approvato da Mintendo per garantirne l'approvazione.
</div>

<div class ="medium_high div">
<h3> 4.1 </h3><br>
<strong> Rischio:</strong> Formato dati non compatibile e conseguente necessità di conversione per l'interazione con altri dispositivi.<br>
<strong> Probabilità:</strong> Moderata 
<strong> Impatto:</strong> Maggiore 
<strong> Stima del rischio:</strong> 12 <br>
<strong> Motivazione alla stima del rischio:</strong> Considerando la complessità del dominio applicativo è plausibile che un problema simile si verifichi, l'impatto in tal caso sarebbe considerevole poiché specifiche funzionalità potrebbero non funzionare o richiedere molto tempo per essere corrette. <br>
<strong> Gestione Rischio:</strong> Contingency Plan. Conoscendo il problema, si contatta un esperto nelle conversioni dati di questa tipologia, possibilmente un dipendente di Mintendo stessa, e si contratta un eventuale disponibilità per la risoluzione.
</div>

<div class ="medium_high div">
<h3> 5.1 </h3><br>
<strong> Rischio:</strong> Gli errori critici rilevati dopo il lancio sono di grande portata e non correggibili in tempi brevi.<br>
<strong> Probabilità:</strong> Bassa 
<strong> Impatto:</strong> Catastrofico 
<strong> Stima del rischio:</strong> 10 <br>
<strong> Motivazione alla stima del rischio:</strong> Se presenti, gli errori critici non correggibili in tempi brevi, possono avere un forte impatto sulla giocabilità del prodotto e quindi sulla soddisfazione del cliente finale. Nonostante ciò, la probabilità che ciò si verifichi è fortunatamente bassa. <br>
<strong> Gestione Rischio:</strong> Mitigazione. Si provvederà a svolgere numerose e frequenti sessioni di testing, anche con utenti finali, specialmente nel periodo che intercorre tra il completamento del software e il suo rilascio. 
</div>


<div class ="medium div">
<h3> 5.2 a </h3><br>
<strong> Rischio:</strong> Le nuove funzionalità online aggiunte dopo il lancio non suscitano l'interesse sperato.<br>
<strong> Probabilità:</strong> Bassa 
<strong> Impatto:</strong> Moderato 
<strong> Stima del rischio:</strong> 6 <br>
<strong> Motivazione alla stima del rischio:</strong> L'impatto sull'aggiunta di nuove funzionalità che non suscitano particolare interesse è moderato in quanto ciò non impatta particolarmente le categorie di giocatori che non giocano online.<br>
<strong> Gestione Rischio:</strong> Acceptance/Contingency Plan. Se una funzionalità non suscita l'interesse sperato, prima di produrre la successiva si effettueranno maggiori survey con gli utenti per identificare cosa potrebbe riscuotere un maggiore successo.
</div>

<div class ="medium div">
<h3> 5.2 b </h3><br>
<strong> Rischio:</strong> e nuove funzionalità online aggiunte dopo il lancio introducono errori.<br>
<strong> Probabilità:</strong> Bassa 
<strong> Impatto:</strong> Maggiore 
<strong> Stima del rischio:</strong> 8 <br>
<strong> Motivazione alla stima del rischio:</strong> l'impatto sull'aggiunta di nuove funzionalità che introducono errori è maggiore poiché potrebbe impattare funzionalità precedentemente gradite.<br>
<strong> Gestione Rischio:</strong> Contingency Plan, se una funzionalità introduce errori, si tenterà di rilasciare quanto prima una patch correttiva.
</div>
 


