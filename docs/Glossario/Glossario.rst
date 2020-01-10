.. _Glossario:

Glossario
==========

Nella tabella seguente sono riportati i termini e gli acronimi comunemente
usati nella piattaforma **Nivola**.

+--------------------------------------+--------------------------------------+
| **Acronimo/Termine**                 | **Significato**                      |
+--------------------------------------+--------------------------------------+
| Nivola                               | Ci si riferisce al complesso di      |
|                                      | tutte le componenti della            |
|                                      | piattaforma: Service Portal, CMP,    |
|                                      | back-end .                           |
|                                      |                                      |
+--------------------------------------+--------------------------------------+
| Service Portal                       | È il portale di servizio a cui       |
|                                      | consumer e provider accedono per il  |
|                                      | governo dei servizi esposti da       |
|                                      | Nivola. L’interfaccia è in grado     |
|                                      | cooperare con le API di business     |
|                                      | esposte dalla CMP.                   |
|                                      |                                      |
|                                      | Il Service Portal espone inoltre     |
|                                      | funzioni proprie come l’accesso alla |
|                                      | documentazione, ai video tutorial,   |
|                                      | alla chat e al Servizio di           |
|                                      | assistenza tramite il Team di        |
|                                      | Supporto Nivola per supportare       |
|                                      | l’utente in caso di problemi,        |
|                                      | malfunzionamenti o semplici          |
|                                      | how-to-use.                          |
|                                      |                                      |
+--------------------------------------+--------------------------------------+
| Compute Services                     | Categoria di servizi che permette di |
|                                      | fruire di  risorse elaborative       |
|                                      | (espresse in CPU, RAM e spazio       |
|                                      | disco) in differenti flavour e       |
|                                      | template, corredate da servizi di    |
|                                      | networking e security.               |
|                                      |                                      |
|                                      | Sulla base del perimetro delle       |
|                                      | risorse presenti, gli utilizzatori   |
|                                      | saranno in grado di realizzare i     |
|                                      | propri tenant, istanziare le         |
|                                      | macchine virtuali selezionandole da  |
|                                      | un ampio catalogo di template e di   |
|                                      | gestirle in modo autonomo e          |
|                                      | integrato con gli altri servizi      |
|                                      | disponibili.                         |
|                                      |                                      |
+--------------------------------------+--------------------------------------+
| DBaaS                                | “Data Base as a Service” sono        |
|                                      | servizi gestiti  costituiti da       |
|                                      | ambienti virtuali dedicati  in       |
|                                      | differenti configurazioni e          |
|                                      | tecnologie, con differenti livelli   |
|                                      | di affidabilità e ridondanza in      |
|                                      | funzione delle esigenze del Cliente. |
|                                      | Sono inclusi i servizi di backup,    |
|                                      | restore, monitoraggio, aggiornamento |
|                                      | e patching.                          |
+--------------------------------------+--------------------------------------+
| STaaS                                | Il servizio prevede la fornitura di  |
|                                      | spazio disco prestazionale           |
|                                      | raggiungibile via rete con           |
|                                      | protocolli NFS e CIFS esclusivamente |
|                                      | dalle macchine virtuali Nivola  La   |
|                                      | messa a disposizione dei servizi di  |
|                                      | storage avviene su infrastrutture    |
|                                      | ridondate e configurate in alta      |
|                                      | affidabilità.                        |
|                                      |                                      |
+--------------------------------------+--------------------------------------+
| BCKaaS                               | Il servizio di backup as a service è |
|                                      | un’opzione attivabile dall’utente    |
|                                      | per il backup delle macchine         |
|                                      | virtuali attivate in Nivola. Il      |
|                                      | Cliente può scegliere se attivare il |
|                                      | backup sulle risorse selezionate e   |
|                                      | scegliere i livelli di retention più |
|                                      | appropriati per il proprio servizio. |
|                                      |                                      |
|                                      | Il servizio viene erogato attraverso |
|                                      | piattaforme che permettono una       |
|                                      | notevole affidabilità                |
|                                      | infrastrutturale, e attraverso la    |
|                                      | funzione di “deduplica dei dati”,    |
|                                      | per  il raggiungimento di una        |
|                                      | elevata efficienza. I backup sono    |
|                                      | depositati su apparati storage       |
|                                      | differenti da quelli che ospitano    |
|                                      | dati e servizi .                     |
|                                      |                                      |
+--------------------------------------+--------------------------------------+
| CMP                                  | Cloud Management Platform -          |
|                                      | piattaforma di integrazione ed       |
|                                      | automazione che espone tutti i       |
|                                      | servizi di business attraverso API   |
|                                      | (Application programming Interface)  |
|                                      | richiamabili dall’utente o           |
|                                      | attraverso l’uso del Service Portal. |
|                                      | Include i servizi di accounting,     |
|                                      | profilazione, security.              |
|                                      |                                      |
+--------------------------------------+--------------------------------------+
| API                                  | Application Programming              |
|                                      | Interface (in italiano traducibile   |
|                                      | come Interfaccia di programmazione   |
|                                      | di un'applicazione), le API sono     |
|                                      | strumenti di programmazione messi a  |
|                                      | disposizione degli sviluppatori per  |
|                                      | facilitare il loro compito nella     |
|                                      | realizzazione di applicazioni        |
|                                      | integrate.                           |
|                                      |                                      |
+--------------------------------------+--------------------------------------+
| NSC                                  | Nivola Support Center - Single Point |
|                                      | of Contact per tutti i servizi cloud |
|                                      | (Nivola, NMSF, POSC)                 |
|                                      |                                      |
+--------------------------------------+--------------------------------------+
| CLI                                  | Command Line Interface - nel         |
|                                      | progetto Nivola trattasi di command  |
|                                      | interface dedicata alla gestione di  |
|                                      | tutte le risorse della CMP.          |
|                                      | L’utilizzo è possibile anche per gli |
|                                      | utenti accreditati e i propri        |
|                                      | fornitori attraverso opportuna       |
|                                      | profilazione.                        |
|                                      |                                      |
+--------------------------------------+--------------------------------------+
| APP Engine                           | Template preconfigurato composto da  |
|                                      | risorse elaborative, database,       |
|                                      | storage, reti e sicurezza che        |
|                                      | implementa una particolare funzione  |
+--------------------------------------+--------------------------------------+
| Consumer                             | User utilizzatore della piattaforma    |
|                                      | Nivola                               |
+--------------------------------------+--------------------------------------+
| Provider                             | CSI Piemonte, nella sua veste di     |
|                                      | Cloud provider                       |
+--------------------------------------+--------------------------------------+
| NMSF                                 | Nuovo Modello Server Farm            |
+--------------------------------------+--------------------------------------+
| Region                               | Aggregato di una o più Availability  |
|                                      | Zone                                 |
+--------------------------------------+--------------------------------------+
| Availability Zone                    | Aggregato di uno o più Site. l’AZ è  |
|                                      | caratterizzata da una sua completa   |
|                                      | autonomia infrastrutturale e         |
|                                      | indipendenza                         |
+--------------------------------------+--------------------------------------+
| Site                                 | Aggregato di uno o più POD           |
+--------------------------------------+--------------------------------------+
| POD                                  | Point Of Delivery - aggregato di     |
|                                      | infrastrutture elaborative, storage, |
|                                      | rete e sicurezza autoconsistenti     |
+--------------------------------------+--------------------------------------+
| Utente/User                          | Persona fisica accreditata           |
|                                      | all’accesso ai servizi Nivola        |
+--------------------------------------+--------------------------------------+
| Account                              | Contenitore di istanze di servizio   |
+--------------------------------------+--------------------------------------+

--------------
