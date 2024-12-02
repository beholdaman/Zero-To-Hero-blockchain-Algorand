
Una blockchain e' un libro mastro distribuito decentralizzato che registra dati di transazioni.
E' un registro immutabile: si possono aggiungere dati, ma non modificarli o eliminarli.

**Distribuito** perché è replicato su diversi nodi connessi in rete tra loro.

**Decentralizzato** perché non esiste una autorità centrale che propone e valida le aggiunte da fare al registro, ma tutti i nodi della rete possono proporre transazioni da aggiungere, e tutti gli altri nella rete ne fanno la validazione. 

Queste caratteristiche rendono la blockchain molto robusta agli attacchi e agli errori in buona fede: per corrompere la blockchain sarebbe necessario corromperne tutte le copie sui vari nodi oppure prendere il controllo di tutti i nodi validatori.


La validazione dei blocchi è effettuata automaticamente dai nodi secondo un protocollo comune, che varia tra diverse blockchain, detto *protocollo di consenso*



La parola **block** si riferisce a un insieme di transazioni proposte e verificate dai nodi della rete.

La parola **chain** si riferisce al fatto che ogni blocco contiene al suo interno un riferimento al blocco inserito precedentemente, sotto forma di un hash del contenuto del blocco precedente; ciò pone i blocchi di transazioni in una catena ideale dall' ultimo blocco inserito al primo (*nodo di genesi*).


