**Servizi disponibili**
***********************

**Virtual Machine**: Il servizio di messa a disposizione di server
virtuali si basa su infrastrutture ridondate configurate in alta
affidabilità, bilanciamento di carico automatico e spazio storage
centralizzato configurabili combinando virtual CPU, Memoria Ram e spazio
Storage prestazionale. La funzionalità di High Availability (HA)
permette, in caso di fault/irraggiungibilità di un nodo fisico del
cluster, per i server virtuali attivi su questo, l’immediata accensione
sui restanti nodi ancora attivi.

La funzionalità di Distributed Resource Scheduler (DRS), nel caso si
utilizzi l’ambiente di virtualizzazione commerciale, bilancia
costantemente il carico dei server virtuali tra i nodi del cluster.

Il sistema di monitoraggio dei datastore mantiene costantemente sotto
controllo lo spazio occupato al fine di evitare disservizi dovuti
all’esaurimento dello spazio su uno specifico datastore dove sono
memorizzati uno o più server virtuali.

I server virtuali possono migrare da un nodo ad un altro, o da un
datastore ad un altro, senza subire il minimo disservizio.

I server virtuali sono in esecuzione sui seguenti hypervisor:

-  Vmware esxi (release 5.5 / 6.5 o sup.): in questo/i cluster si
   possono attestare tutti i server virtuali che necessitano di
   funzionalità di alta affidabilità offerta dall’hypervisor;

-  OpenStack (release Ocata o sup.): in questo/i cluster si possono
   attestare tutti i server virtuali che intendono sfruttare la maggiore
   economicità della piattaforma Open Source e che ospitano sistemi con
   meccanismi di alta affidabilità demandati allo strato applicativo.

I sistemi operativi di riferimento sono:

-  RedHat 6.x e successive

-  CentOS 6.x e successive

-  Oracle linux 5.x e successive

-  Microsoft Windows 2008 server e successive

*Tagli delle risorse*

Il Cliente può selezionare uno dei tagli disponibili:


.. table:: 

   +--------------+---------------+----------------+------------------+
   | **Taglio**   | **Risorse**   |                |                  |
   +==============+===============+================+==================+
   |              | **Core**      | **RAM (GB)**   | **Disco (TB)**   |
   +--------------+---------------+----------------+------------------+
   | Medium       | 40            | 1024           | 20               |
   +--------------+---------------+----------------+------------------+
   | Large        | 80            | 2048           | 40               |
   +--------------+---------------+----------------+------------------+

Su cui ha la possibilità di creare virtual machine con i seguenti
flavour:

.. table:: 

   +---------------+---------------+----------------+------------------+
   | **Flavour**   | **Risorse**   |                |                  |
   +===============+===============+================+==================+
   |               | **Core**      | **RAM (GB)**   | **Disco (GB)**   |
   +---------------+---------------+----------------+------------------+
   | m1.small      | 1             | 2              | 20               |
   +---------------+---------------+----------------+------------------+
   | m1.medium     | 2             | 4              | 40               |
   +---------------+---------------+----------------+------------------+
   | m1.large      | 4             | 8              | 80               |
   +---------------+---------------+----------------+------------------+
   | r4.2xlarge    | 2             | 8              | 80               |
   +---------------+---------------+----------------+------------------+
   | m1.2xlarge    | 8             | 24             | 140              |
   +---------------+---------------+----------------+------------------+
   | r4.4xlarge    | 2             | 16             | 100              |
   +---------------+---------------+----------------+------------------+
   | i3.4xlarge    | 8             | 32             | 140              |
   +---------------+---------------+----------------+------------------+
   | i3.8xlarge    | 8             | 48             | 140              |
   +---------------+---------------+----------------+------------------+
   | d2.8xlarge    | 16            | 64             | 140              |
   +---------------+---------------+----------------+------------------+

Nel caso le risorse necessarie non siano sufficienti la configurazione
passa al taglio successivo, e qualora non sia disponibile il Cliente
dovrà contattare il Team di Supporto.

**STaaS (Storage As a Service)**: Il servizio prevede la fornitura di
spazio disco prestazionale o lowrange raggiungibile via rete. La messa a
disposizione dei servizi di storage avviene su infrastrutture ridondate
e configurate in alta affidabilità. La principale caratteristica di tale
configurazione prevede che in caso di fault di una componente di
front-end o back-end degli apparati, intervengono meccanismi di
ridondanza che permettono di ottenere l’erogazione continua del
servizio. In caso, invece, di rottura di un disco, intervengono
meccanismi di protezione tipici della configurazione hardware RAID. La
configurazione RAID con dischi “hot spare” consente in caso di guasto di
un disco, la messa in fault dello stesso e la sua sostituzione con un
altro disco prelevato dal gruppo di dischi definiti “hot spare”.

**Backup as a Service**: Il servizio permette la salvaguardia dei propri
dati per porre rimedio ad eventuali guasti o malfunzionamenti. Il Backup
viene erogato attraverso piattaforme di mercato che permettono una
notevole affidabilità infrastrutturale, e attraverso la funzione di
“deduplica dei dati”, il raggiungimento di una elevata efficienza.

L’ambito di applicazione di questa soluzione di backup determina la
tecnologia con la quale è erogata la soluzione:

-  Hypervisor OpenSource – Tecnologia Trillio

-  Hypervisor Commerciale - Tecnologia Veeam

Sono previste tre modalità di erogazione: Cloud Backup con Agent per
Client distribuiti sul territorio; Backup gestito per clienti che hanno
infrastrutture gestite da CSI; Backup in Self Provisioning con un
servizio “agent-less” per i server del VPC.

L’infrastruttura si basa su prodotti che permettono la gestione, lato
utente, sia dei job di backup che dei propri restore.

Policy di backup standard:

1. Retention: 7 giorni, Fascia oraria: a partire dalle 21:00

2. Retention: 14 giorni, Fascia oraria: a partire dalle 21:00

3. Retention: 30 giorni, Fascia oraria: a partire dalle 21:00

4. A progetto

**DBaaS Managed (DataBase as a Service)**: servizio di messa a
disposizione di istanze Database open source (MySql, PostgreSql) non
gestite con backup incluso.

\ **MySql as a service:** Il servizio prevede la messa a disposizione di
database su tecnologia RDBMS MySql, articolato su uno o più servizi
accessibili da una o più applicazioni.

Il Servizio Database viene erogato a bordo delle virtual farm del CSI
Piemonte, istanziato su server virtuali con sistema operativo Linux in
edizioni eterogenee e versioni supportate dal vendor o dalla community,
e aggiornate sia dal punto di vista funzionale che di sicurezza.

Il servizio RDBMS MySql è disponibile nella versione 5.6 e superiori.
Sono escluse dalla configurazione standard le opzioni aggiuntive.

\ **PostgreSql as a service**: Il servizio prevede la messa a
disposizione di database su tecnologia RDBMS POSTGRESQL, articolato su
uno o più servizi accessibili da una o più applicazioni.

Il Servizio Database viene erogato a bordo delle virtual farm del CSI
Piemonte, istanziato su server virtuali con sistema operativo Linux in
edizioni eterogenee e versioni supportate dal vendor o dalla community,
e aggiornate sia dal punto di vista funzionale che di sicurezza.

Il servizio RDBMS POSTGRESQL è disponibile nella versione 9.2 e
superiori. Sono escluse dalla configurazione standard le opzioni
aggiuntive.

**Servizi di Gestione e Monitoraggio**: Rappresentano tutta una serie di
servizi aggiuntivi attivabili in aggiunta ai prodotti già descritti:

**Servizio di Monitoraggio Server e apparati**: il servizio mette a
disposizione un’interfaccia web attraverso cui gli utenti con le
opportune abilitazioni possono verificare lo stato di utilizzo delle
risorse IaaS (CPU, RAM e Disco). Il servizio di monitoraggio specifico è
finalizzato al controllo di “oggetti” che possono risiedere presso
l’infrastruttura Nivola. Il servizio di monitoraggio viene svolto per il
controllo di raggiungibilità e lo stato di funzionamento di un server
raggiungibile mediante rete dati, dislocato presso uno dei Pod di
Nivola. L’alerting viene effettuato attraverso mail o altro secondo
quanto richiesto.

**Gestione Sistemistica della VM**: Il servizio di gestione sistemistica
server Cloud prevede l’erogazione della gestione delle VM Linux e
Windows installate sul Cloud del CSI-Piemonte.

Il servizio di gestione sistemistica server Cloud prevede l’esecuzione
di attività di installazione e configurazione delle componenti del
sistema operativo della VM a cui si applica il servizio. Le attività
sono concordate preventivamente da un lato con il cliente, e dall’altro
con gli eventuali fornitori terzi.

Di seguito vengono elencati i principali compiti dei sistemisti del CSI
Piemonte nello svolgimento del servizio:

-  L’aggiornamento del sistema operativo e dei software di base locali
   installati sui server;

-  L’installazione delle patch e degli aggiornamenti di sicurezza
   proposti da DPO, nell’ambito della versione e della release del
   sistema operativo installato;

-  Identificazione degli impatti e la ricerca della loro causa,
   attraverso un processo correttivo (troubleshooting), a fronte del
   presentarsi di malfunzionamenti legati ai sistemi operativi
   installati;

-  La gestione e l’aggiornamento del sistema locale antivirus dei server
   ai quali il servizio è applicato.

Nello svolgimento delle attività di gestione quotidiana, i sistemisti
curano il mantenimento del controllo degli accessi finalizzato a
proteggere e limitare gli interventi sui server solo agli utenti
autorizzati, in accordo con le indicazioni fornite dal Cliente. Sono
previste azioni giornaliere eseguite a bordo dei server oggetto del
servizio di gestione sistemistica server Cloud, il cui fine è quello di
garantire una buona e costante erogazione del servizio, una corretta
manutenzione, un monitoraggio delle risorse così da prevenire
disservizi.

**Gestione Istanza DB**: Servizi di gestione sistemistica in ambito
Database PostgreSql e MySql

**Gestione Tenant**: Il servizio è volto a garantire disponibilità,
integrità e riservatezza delle informazioni del Cliente nel contesto del
Virtual Data Center. Il Servizio prevede attività mirate a garantire la
protezione delle informazioni del Cliente per rispondere ai requisiti
previsti dalla normativa vigente in materia di protezione dei dati,
oltre alla gestione completa dell’Organization Unit dedicata al cliente.

Le attività previste dal servizio sono le seguenti:

-  gestione dell’ambiente Cloud;

-  creazione, modifica, eliminazione dei servizi e delle risorse
   all’interno del Tenant;

-  assistenza in presenza di segnalazioni di disservizi;

-  identificazione dei requisiti di sicurezza dei servizi applicativi e
   infrastrutturali;

-  verifica e validazione delle policy richieste dai clienti per
   accedere a servizi esterni al VPC.

La gestione della sicurezza prevede anche l’abilitazione delle utenze
dei sistemisti CSI Piemonte per l’erogazione della gestione operativa di
tutti gli aspetti legati al VPC.

*Perimetro tecnologico gestito*

La gestione degli ambienti e dei servizi viene operata all’interno del
Tenant definito e agisce sui servizi attivati dal Cliente e delegati in
gestione al CSI Piemonte.

Comprende la possibilità di gestire gli indirizzamenti di rete, le
policy di sicurezza, la creazione di VM e la loro gestione,
l’interfacciamento con reti esterne.
