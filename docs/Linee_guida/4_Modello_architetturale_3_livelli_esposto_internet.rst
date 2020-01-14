.. _Modello_architetturale_3_livelli_esposto_internet:

**Modello architetturale 3 livelli esposto su internet**
********************************************************

Il modello riportato nella figura sottostante, rappresenta un esempio
di infrastruttura, disposta su 3 livelli, esposta su internet. Lo schema rappresenta
il paradigma consigliabile a fronte di risorse da proteggere e
in grado colloquiare attraverso reti diverse.
Il disegno riporta, istanze create all'interno di **tre security group** distinti
e attestati sulla rete di backend e su quella di frontend.
Il Security Group dedicato ai **Web Server**, esce su **internet** sfruttando un
**Load Balancer** protetto da un **firewall**.
La **rete di backend** è condivisa dal Security group del **DB as Service**
e da quello degli **Application Server**. In questo modo, l'istanza Dbaas, è
completamente separata e accessibile unicamente dalla rete di backend.
A cavallo delle reti invece, possono essere generate istanze dello
**storage as Service**. Nello schema, sono stati coolocati,  share
condivisi da macchine create su SG diversi oppure che rientrano nello stesso.


.. image:: img/Arch-3-livelli-internet.png

