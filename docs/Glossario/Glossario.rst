.. _howto-glossario:

Glossario
==============

​1​ Termini ed acronimi
===========================


Nella tabella seguente, raggruppati in ordine alfabetico, si riportano i termini e gli acronimi frequentemente
utilizzati su Nivola, allo scopo di far acquisire la necessaria e graduale familiarità.

    1.1 [A]_

    1.2 [B]_

    1.3 [C]_

    1.4 [D]_

    1.5 [E]_

    1.6 [F]_

    1.7 [G]_

    1.8 [H]_

    1.9 [I]_

    1.10 [J]_

    1.11 [K]_

    1.12 [L]_

    1.13 [M]_

    1.14 [N]_

    1.15 [O]_

    1.16 [P]_

    1.17 [Q]_

    1.18 [R]_

    1.19 [S]_

    1.20 [T]_

    1.21 [U]_

    1.22 [V]_

    1.23 [W]_

    1.24 [X]_

    1.25 [Y]_

    1.26 [Z]_

--------

.. [A]

​1.1 A
--------

+--------------------------------------+--------------------------------------+
|            Acronimo/Termine          |            Significato               |
+--------------------------------------+--------------------------------------+
| ACCOUNT                              | Contenitore di istanze di servizio   |
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
+--------------------------------------+--------------------------------------+
|                                      |                                      |
| APP Engine                           | Template preconfigurato composto da  |
|                                      | risorse elaborative, database,       |
|                                      | storage, reti e sicurezza che        |
|                                      | implementa una particolare funzione  |
+--------------------------------------+--------------------------------------+
| Availability Zone (AZ)               | Aggregato di uno o più Site. l’AZ è  |
|                                      | caratterizzata da una sua completa   |
|                                      | autonomia infrastrutturale e         |
|                                      | indipendenza                         |
+--------------------------------------+--------------------------------------+

-----------------------

.. [B]
​1.2​ B
--------------------

+--------------------------------------+--------------------------------------+
|            Acronimo/Termine          |            Significato               |
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

------------------------------


.. [C]

​1.3​ C
---------------


+--------------------------------------+--------------------------------------+
|            Acronimo/Termine          |            Significato               |
+--------------------------------------+--------------------------------------+
| Capability                           | Attributo essenziale dell'account per|
|                                      | istanziare i servizi. E' assegnato   |
|                                      | all'account in fase di creazione.    |
|                                      | A fronte di un account è possibile   |
|                                      | avere più capabilities.              |
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
| Consumer                             | User utilizzare della piattaforma    |
|                                      | Nivola                               |
+--------------------------------------+--------------------------------------+

-------

.. [D]

​
​1.4​ D

-------

+--------------------------------------+--------------------------------------+
|            Acronimo/Termine          |            Significato               |
+--------------------------------------+--------------------------------------+
| Divisione                            | E' il secondo livello organizzativo. |
|                                      | Una organizzazione può avere più     |
|                                      | divisioni. Ogni Divisione ha         |
|                                      | ha associato un portafoglio chiamato |
|                                      | Wallet che ne definisce il limite    |
|                                      | di spesa. Per un Cliente esterno     |
|                                      | può coincidere con il valore della   |
|                                      | determina o con una pòarte di essa.  |
|                                      | Non può esserci una Divisione senza  |
|                                      | un Organizzazione da cui dipendere.  |
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


-----------

.. [E]

​1.5​ E
----------------------

+--------------------------------------+--------------------------------------+
|            Acronimo/Termine          |            Significato               |
+--------------------------------------+--------------------------------------+


-------------

.. [F]


​1.6​ F
-------------------
+--------------------------------------+--------------------------------------+
|            Acronimo/Termine          |            Significato               |
+--------------------------------------+--------------------------------------+
| FLAVOUR                              | Identificano le differenti tipologie |
|                                      | di VM le cui caratteristiche         |
|                                      | differiscono per la quantità di      |
|                                      | risorse CPU, RAM e DISCO. L’utente   |
|                                      | può scegliere tra diversi flavour in |
|                                      | base delle proprie esigenze.         |
+--------------------------------------+--------------------------------------+


----------------------


.. [G]

​1.7​ G
----------------------


+--------------------------------------+--------------------------------------+
|            Acronimo/Termine          |            Significato               |
+--------------------------------------+--------------------------------------+

-----------------

.. [H]


​1.8​ H
------------------


+--------------------------------------+--------------------------------------+
|            Acronimo/Termine          |            Significato               |
+--------------------------------------+--------------------------------------+

-----------------

.. [I]


​1.9​ I
--------------------------


+--------------------------------------+--------------------------------------+
|            Acronimo/Termine          |            Significato               |
+--------------------------------------+--------------------------------------+
| Immagine                             | Parametro che determina l'OS della VM|
|                                      | da istanziare eventualmente          |
|                                      | arricchito del software per          |
|                                      | l'automazione come p.e. ansible o    |
|                                      | heat                                 |
+--------------------------------------+--------------------------------------+

-----------------


.. [J]


​1.10​ J
------------------


+--------------------------------------+--------------------------------------+
|            Acronimo/Termine          |            Significato               |
+--------------------------------------+--------------------------------------+

-----------------

.. [K]



​1.11 K
--------------
+--------------------------------------+--------------------------------------+
|            Acronimo/Termine          |            Significato               |
+--------------------------------------+--------------------------------------+
| KEY                                  | Chiave ssh usata al momento della    |
|                                      | creazione della VM abilitando la     |
|                                      | connessione da remoto.               |
+--------------------------------------+--------------------------------------+


-------------------------

.. [L]


​1.12 L
--------
+--------------------------------------+--------------------------------------+
|            Acronimo/Termine          |            Significato               |
+--------------------------------------+--------------------------------------+

-----------------

.. [M]


​1.1​3 M
--------------------
+--------------------------------------+--------------------------------------+
|            Acronimo/Termine          |            Significato               |
+--------------------------------------+--------------------------------------+

-------------------------


.. [N]


​1.14 N
----------------
+--------------------------------------+--------------------------------------+
|            Acronimo/Termine          |            Significato               |
+--------------------------------------+--------------------------------------+
| Nivola                               | Ci si riferisce al complesso di      |
|                                      | tutte le componenti della            |
|                                      | piattaforma: Service Portal, CMP,    |
|                                      | back-end .                           |
|                                      |                                      |
+--------------------------------------+--------------------------------------+
| NMSF                                 | Nuovo Modello Server Farm            |
+--------------------------------------+--------------------------------------+
| NSC                                  | Nivola Support Center - Single Point |
|                                      | of Contact per tutti i servizi cloud |
|                                      | (Nivola, NMSF, POSC)                 |
|                                      |                                      |
+--------------------------------------+--------------------------------------+

-------------------------

.. [O]


​1.1​5 O
------------------

+--------------------------------------+--------------------------------------+
|            Acronimo/Termine          |            Significato               |
+--------------------------------------+--------------------------------------+
| Organizzazione                       | E’ gerarchicamente il massimo livello|
|                                      | organizzativo. Dall'Organizzazione   |
|                                      | possono dipendere 1 o più Divisioni. |
|                                      | Ad un organizzazione può coincidere  |
|                                      | un Ente.                             |
+--------------------------------------+--------------------------------------+

-------------------------

.. [P]


​1.1​6 P
--------

+--------------------------------------+--------------------------------------+
|            Acronimo/Termine          |            Significato               |
+--------------------------------------+--------------------------------------+
| Provider                             | CSI Piemonte, nella sua veste di     |
|                                      | Cloud provider                       |
+--------------------------------------+--------------------------------------+
| POD                                  | Point Of Delivery - aggregato di     |
|                                      | infrastrutture elaborative, storage, |
|                                      | rete e sicurezza autoconsistenti     |
+--------------------------------------+--------------------------------------+

-------------------------


.. [Q]



​1.17​ Q
----------------


+--------------------------------------+--------------------------------------+
|            Acronimo/Termine          |            Significato               |
+--------------------------------------+--------------------------------------+

-----------------


.. [R]


1.18 R
--------

+--------------------------------------+--------------------------------------+
|            Acronimo/Termine          |            Significato               |
+--------------------------------------+--------------------------------------+
| Region                               | Aggregato di una o più Availability  |
|                                      | Zone                                 |
+--------------------------------------+--------------------------------------+

-------------------------


.. [S]


1.19 S
--------

+--------------------------------------+--------------------------------------+
|            Acronimo/Termine          |            Significato               |
+--------------------------------------+--------------------------------------+
| Site                                 | Aggregato di uno o più POD           |
+--------------------------------------+--------------------------------------+
| SG Security Group                    | E' il firewall della istanze di      |
|                                      | Nivola.                              |
|                                      | Configurabile dall'utente e in grado |
|                                      | di controllare il traffico in entrata|
|                                      | e in uscita da e verso le istanze.   |
|                                      | Il SG protegge ogni singola istanza  |
|                                      | al suo interno per far colloquiare le|
|                                      | istanze al suo interno è necessario  |
|                                      | agire sulle regole di ingresso e     |
|                                      | uscita.                              |
+--------------------------------------+--------------------------------------+
| STAAS                                | Il servizio prevede la fornitura di  |
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
| SUBNET                               | E’ un range di IP utilizzabile       |
|                                      | all’interno del VpC. E’ possibile    |
|                                      | usare delle risorse di Nivola        |
|                                      | all’interno di una specifica subnet. |
|                                      | E’ possibile usare una subnet per    |
|                                      | risorse che devono connettersi ad    |
|                                      | Internet ed una privata, per risorse |
|                                      | che invece non hanno necessità di    |
|                                      | connettersi ad Internet.             |
|                                      | Per proteggere le risorse di Nivola  |
|                                      | in ciascuna sottorete, è possibile   |
|                                      | utilizzare più security groups.      |
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

-------------------------

.. [T]


1.20 T
-----------------


+--------------------------------------+--------------------------------------+
|            Acronimo/Termine          |            Significato               |
+--------------------------------------+--------------------------------------+
| Tagli                                | Definiscono le dimensioni            |
|                                      | massime complessive delle risorse    |
|                                      | della Virtual Machine.               |
+--------------------------------------+--------------------------------------+
| Tags                                 | Attraverso i TAGS la piattaforma     |
|                                      | mette a disposizione                 |
|                                      | la possibilità di etichettare le     |
|                                      | proprie risorse in modo da facilitare|
|                                      | di individuarle e ricercarle con     |
|                                      | chiavi personalizzabili.             |
+--------------------------------------+--------------------------------------+
| Template                             | Sono le tipologie e le versioni del  |
|                                      | OS utilizzati per la creazione della |
|                                      | Virtual Machine.                     |
+--------------------------------------+--------------------------------------+

----------

.. [U]
​

1.21 U
----------

+--------------------------------------+--------------------------------------+
|            Acronimo/Termine          |            Significato               |
+--------------------------------------+--------------------------------------+
| Utente/User                          | Persona fisica accreditata           |
|                                      | all’accesso ai servizi Nivola        |
+--------------------------------------+--------------------------------------+

---------------


.. [V]



1.22 V
----------


+--------------------------------------+--------------------------------------+
|            Acronimo/Termine          |            Significato               |
+--------------------------------------+--------------------------------------+
| VM: Virtual Machine                  | Server in grado di ospitare servizi. |
+--------------------------------------+--------------------------------------+
| VPC: Virtual Private Cloud           | E' una rete virtuale dedicata        |
|                                      | all’account Nivola, logicamente      |
|                                      | isolata dalle altre reti di Nivola.  |
|                                      | L’istanza è utilizzabie all’interno  |
|                                      | del proprio Vpc. Il Vpc è            |
|                                      | configurabile modificando il range   |
|                                      | degli indirizzi IP. Possibile creare |
|                                      | sottoreti, indicando route tables,   |
|                                      | network gateways e security settings.|
+--------------------------------------+--------------------------------------+

------------

.. [W]



1.23 W
----------

+--------------------------------------+--------------------------------------+
|            Acronimo/Termine          |            Significato               |
+--------------------------------------+--------------------------------------+

-------------


.. [X]


1.24 X
----------

+--------------------------------------+--------------------------------------+
|            Acronimo/Termine          |            Significato               |
+--------------------------------------+--------------------------------------+

-------------------


.. [Y]


1.25 Y
----------

+--------------------------------------+--------------------------------------+
|            Acronimo/Termine          |            Significato               |
+--------------------------------------+--------------------------------------+

-------------------------

.. [Z]


1.26 Z
----------

+--------------------------------------+--------------------------------------+
|            Acronimo/Termine          |            Significato               |
+--------------------------------------+--------------------------------------+

-------------------------

================================
