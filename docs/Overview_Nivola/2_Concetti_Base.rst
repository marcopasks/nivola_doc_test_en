.. _Concetti_Base:


**I concetti base**
********************

**Le availability zones**
=========================

Le zone di disponibilità (AZ) sono posizioni isolate all'interno delle
aree dei data center da cui sono forniti e operano i servizi cloud: sono
dunque aree geografiche in cui risiedono i data center dei fornitori di
servizi di cloud pubblico. Le aziende clienti scelgono una o più zone di
disponibilità per i loro servizi a seconda delle esigenze aziendali.

Le aziende clienti selezionano le zone di disponibilità per una serie di
motivi, tra cui la conformità e la vicinanza ai loro clienti finali. Gli
utenti amministratori delle risorse in cloud possono anche scegliere di
replicare i servizi su più zone di disponibilità per ridurre la latenza
o proteggere le risorse. Gli utenti amministratori possono spostare le
risorse in un'altra zona di disponibilità in caso di interruzione.
Alcuni servizi cloud possono anche essere limitati a determinate regioni
o AZ.

La piattaforma Nivola è dispiegata su un modello multi-region e multi
availability zone. Attualmente (2020) dispone di una unica region e di 3
AZ ospitate in 3 siti presso i data center del CSI Piemonte. I due siti
di Torino e il sito di Vercelli sono collegati tra loro tramite anello
in fibra ottica a bassissima latenza.


.. image:: img/Avaliability-zones.png


**La struttura organizzativa**
==============================


La struttura organizzativa è la suddivisione gerarchica che permette di
personalizzare i servizi, l'accesso o le impostazioni per diversi gruppi
di utenti o dispositivi. Nella piattaforma Nivola la struttura
organizzativa si articola su 3 livelli:

-  **Organizzazione**: è gerarchicamente l’entità organizzativa più
   elevata e può coincidere con il nome del cliente ad esempio “Regione
   Piemonte”, “Csi Piemonte” e così via. Nella piattaforma le risorse
   sono a disposizione di varie organizzazioni, che sono però dal punto
   di vista logico completamente separate e indipendenti;

-  **Divisione**: è il secondo livello organizzativo. Una organizzazione
   può avere più divisioni. Il concetto di Divisione rappresenta quindi
   una suddivisione logica dell’Organizzazione, e può riflettere dunque
   una divisione di tipo territoriale, organizzativa o di tipo di
   business; inoltre ogni Divisione ha associato un portafoglio chiamato
   Wallet che ne definisce il limite di spesa;

-  **Account**: è l’ultimo livello organizzativo e dipende dalla
   Divisione. Una Divisione può essere suddivisa in più account. La
   suddivisione in account può ad esempio riflettere una suddivisione di
   ambienti tra produzione , test e sviluppo oppure una suddivisione per
   prodotti/applicazioni oppure può seguire la logica più idonea per il
   cliente. Solo all’interno dell’account sono istanziati i servizi, che
   possono essere diversi da un account all’altro. Si ricorda che avere
   un ruolo di gestione sull’Account non significa puramente possedere
   un’utenza, ma anche avere la possibilità operativa di utilizzare i
   servizi per cui si è abilitati.

..

Per quanto riguarda l’organizzazione “CSI Piemonte” si è scelto che la
divisione corrisponde alla soluzione applicativa e l’account corrisponde
al prodotto.

Riportiamo schematicamente l’albero della struttura organizzativa.

.. image:: img/struttura-org.png

Si noti che tutte le risorse e i servizi sono associabili solo a livello
di Account. Non è possibile associare i servizi alle Divisioni o alle
Organizzazioni. L’Account rappresenta quindi il contenitore in cui
vengono implementati e resi disponibili tutti i servizi utente. La
gestione delle risorse utente avverrà quindi a livello di Account con
dei ruoli abilitati ad operare a questo livello.

.. image:: img/Org-ruoli.png



**Utenti, ruoli ed Account**
============================

Si possono distinguere più ruoli all’interno della piattaforma, che si
correlano alla struttura organizzativa definita. Ad ogni ruolo può
corrispondere almeno un utente, e quindi almeno una persona fisica che
svolge quella funzione. Una persona registrata sul sistema può essere
associata a più ruoli anche su strutture organizzative differenti. Ad
esempio un utente può avere ruoli differenti su account anche di
divisioni distinte.

Ad oggi all’interno del sistema sono implementati i seguenti ruoli
utente.

**Master di Organizzazione**: questo ruolo rappresenta gli utenti che
possono svolgere funzioni amministrative all’interno dell’Organizzazione
quali la creazione , sempre all’interno dell’organizzazione di
pertinenza, delle division e degli account; può inoltre profilare gli
utenti per renderli operativi all’interno della propria struttura ed
eventualmente registrare utenti non ancora presenti sulla piattaforma.
Il Master di Organizzazione può monitorare i costi e lo stato delle
risorse a tutti i livelli della propria struttura organizzativa
(divisioni e account) e visualizzarne i relativi report. Non ha però
accesso alle funzioni di gestione (creazione/modifica/cancellazione)
delle risorse associate agli account della propria organizzazione.

**Master di Divisione**: questo ruolo rappresenta gli utenti che possono
svolgere funzioni amministrative all’interno della Divisione quali la
creazione , sempre all’interno della divisione di pertinenza, degli
account; può inoltre profilare gli utenti per renderli operativi
all’interno della propria struttura ed eventualmente ha la possibilità
di registrare utenti non ancora presenti sulla piattaforma. Il Master di
Organizzazione può monitorare i costi e lo stato delle risorse a tutti i
livelli della propria struttura organizzativa (account) e visualizzarne
i relativi report. Non ha però accesso alle funzioni di gestione
(creazione/modifica/cancellazione) delle risorse associate agli account
della propria divisione.

**Amministratore di Back Office**: utente che all’interno del sistema ha
privilegi sulle funzioni di BackOffice (registrazione nuovi Utenti,
Accreditamento, creazione livelli organizzativi) e monitoraggio costi e
stato della piattaforma. L’Amministratore di BackOffice può profilare
utenti con ruoli a qualsiasi livello dello struttura organizzativa. Può
inoltre accedere ai report dei costi e consumi aggregati a qualsiasi
livello. Il ruolo è solitamente associato a utenti dei gruppi di
gestione e supporto Csi Piemonte.

**Master di Account**: utente che all’interno dell’Account può gestire
tutte le risorse, sulle quali ha quindi il massimo dei privilegi. Il
Master di Account può quindi creare/cancellare/modificare le risorse,
può anche gestire le risorse create da altri utenti nell’account. Il
Master di Account può visualizzare e accedere ai report dei costi e dei
consumi relativamente al proprio account. Il master di account non può
registrare nuovi utenti all’interno della propria piattaforma e non può
profilare altri utenti ad accedervi.

La fase di introduzione di un nuovo utente si articola in questo modo:
un master, nel limite dei privilegi del suo livello gerarchico, può
accreditare un utente registrato sulla piattaforma assegnandogli un
ruolo, in questo modo gli concede dei permessi per svolgere determinate
funzioni che faranno ricadere il nuovo utente in un determinato gruppo.

La stessa operazione può essere effettuata e delegata all’operatore di
Backoffice.

Riassumendo:

-  Un Master di Organizzazione può accreditare o revocare utenti
   all’interno delle proprie divisioni o account

-  Un Master di Divisione può accreditare o revocare utenti all’interno
   dei propri account.

-  L’Amministratore di Backoffice può accreditare o revocare ruoli agli
   utenti a qualsiasi livello della struttura gerarchica.



