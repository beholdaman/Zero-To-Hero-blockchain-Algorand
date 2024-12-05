
Una blockchain e' un libro mastro distribuito decentralizzato immutabile che registra dati di transazioni.


**Distribuito** perché è replicato su diversi nodi connessi in rete tra loro. Tutti i nodi hanno visibilità sull'intera blockchain.

**Decentralizzato** perché non esiste una autorità centrale che propone e valida le aggiunte da fare al registro, ma tutti i nodi della rete possono proporre transazioni da aggiungere, e tutti gli altri nella rete ne fanno la validazione. 

**Immutabile** perché si possono solo inserire e osservare dati, ma non modificarli o eliminarli

Queste caratteristiche rendono la blockchain molto robusta agli attacchi e agli errori in buona fede: per corrompere la blockchain sarebbe necessario corromperne tutte le copie sui vari nodi oppure prendere il controllo di tutti i nodi validatori.

##### Protocolli di consenso #####

La validazione dei blocchi è effettuata automaticamente dai nodi secondo un protocollo comune, che varia tra diverse blockchain, detto *protocollo di consenso*.

I protocolli di consenso garantiscono l'unicità della transazione avvenuta, introducendo così il concetto di **scarsità digitale**: una stessa valuta non può essere usata per più transazioni.
Questa è la vera innovazione introdotta dalla tecnologia blockchain.

##### Struttura #####


La parola **block** si riferisce a un insieme di transazioni proposte e verificate dai nodi della rete.

La parola **chain** si riferisce al fatto che ogni blocco contiene al suo interno un riferimento al blocco inserito precedentemente, sotto forma di un hash del contenuto del blocco precedente; ciò pone i blocchi di transazioni in una catena ideale dall' ultimo blocco inserito al primo (*nodo di genesi*).


##### Blockchain pubbliche e private #####

###### Public Permission-less ######

Chiunque può unirsi alla blockchain e partecipare alle attività della rete.

- Maggiore sicurezza per alto numero di partecipanti
- Pesante consumo energetico se c'è uso di protocolli di consenso [[Proof of work e Proof of Stake |Proof of Work ]]
- Mancanza di privacy e anonimato (risolvibile con crittografia)

Esempi: *Bitcoin*, *Ether*

###### Private permissioned ######

Blockchain accessibile a un gruppo ristretto di utenti e protetto da crittografia
Struttura distribuita ma non decentralizzata

- Blockchain sovrascrivibile (vulnerabile a errori e violazioni)
- Priorità all' efficienza a discapito dell' immutabilità
- Pensate per applicazioni aziendali

Esempi: *Hyperledger Fabric*, *R3 Corda*

###### Public Permissioned ######

Chiunque può unirsi alla blockchain, ma solo dopo verifica di identità.

- Permettono il concetto di blockchain as a service
- Varia combinazioni di caratteristiche di public e private

Esempi: *Ripple*



