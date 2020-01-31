.. _Concetti_Base:


**I concetti base**
********************

**Le availability zones**
--------------------------

Le zone di disponibilità (AZ) sono posizioni isolate all'interno delle aree dei data center da cui provengono e operano i servizi cloud: sono dunque aree geografiche in cui risiedono i data center dei fornitori di servizi di cloud pubblico. Le aziende clienti scelgono una o più zone di disponibilità per i loro servizi a seconda delle esigenze aziendali.
Le aziende selezionano le zone di disponibilità per una serie di motivi, tra cui la conformità e la vicinanza ai clienti finali. Gli amministratori cloud possono anche scegliere di replicare i servizi su più zone di disponibilità per ridurre la latenza o proteggere le risorse. Gli amministratori possono spostare le risorse in un'altra zona di disponibilità in caso di interruzione. Alcuni servizi cloud possono anche essere limitati a determinate regioni o AZ.
La piattaforma Nivola è dispiegata su un modello multi-region e multi availability zone. Attualmente (2020) dispone di una unica region e di 3 AZ ospitate in 3 Site presso i datacenter del CSI Piemonte presso Torino e Vercelli collegate tra loro tramite anello in fibra ottica a bassissima latenza.


.. image:: img/Avaliability-zones.png


**La struttura organizzativa**
------------------------------

La struttura organizzativa è una suddivisione gerarchica che permette di personalizzare i servizi, l'accesso o le impostazioni per diversi gruppi di utenti o dispositivi. Nella piattaforma Nivola la struttura organizzativa si articola su 3 livelli:
•	**Organizzazione**: è gerarchicamente l’entità organizzativa più elevata e può coincidere con il nome del cliente. Nella piattaforma le risorse sono a disposizione di varie organizzazioni, che sono però dal punto di vista logico completamente separate e indipendenti;

•	**Divisione**: è il secondo livello organizzativo. Una organizzazione può avere più divisioni. Il concetto di Divisione combacia quindi come una suddivisione logica dell’Organizzazione, e può riflettere dunque una divisione di tipo territoriale o di tipo business; inoltre ogni Divisione ha associato un portafoglio chiamato Wallet che ne definisce il limite di spesa;

•	**Account**: è l’ultimo livello organizzativo e dipende dalla Divisione. Una Divisione può avere più account. All’interno dell’account sono istanziati i servizi, che possono essere diversi da un account all’altro. Si ricorda che il termine Account non significa puramente possedere un’utenza, ma avere la possibilità operativa di utilizzare tutti i servizi per cui si è abilitato.




**Utenti, ruoli ed Account**
----------------------------
Da rivedere le bozze 31/01/2020


.. image:: img/Org-ruoli.png
