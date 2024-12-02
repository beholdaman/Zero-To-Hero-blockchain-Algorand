
Sono **protocolli di consenso**: protocolli condivisi eseguiti su una rete in cui non tutti i nodi sono affidabili e non c'è fiducia tra i nodi.

#### Proof of Work ####

I **protocolli Proof of Work** richiedono la dimostrazione di aver compiuto un certo lavoro per poter proporre un nuovo blocco.

Dato un testo comune, ogni nodo deve aggiungervi una stringa di caratteri casuali (*nonce*) e calcolarne l'[[Funzioni di hash| hash]], con l'obiettivo di ottenere un hash sotto una certa soglia )(*target*)
Per natura delle [[Funzioni di hash | funzioni di hash]] l'unico modo per raggiungere tale scopo è procedere per tentativi, cosa che richiede una certa potenza di calcolo.

Il primo nodo che risolve con successo il criptopuzzle può proporre un blocco da inserire sulla blockchain, che dovrà poi essere validato.
Per natura delle [[Funzioni di hash | funzioni di hash]] verificare la correttezza della soluzione è immediato.

Il *target* deve essere scelto in modo oculato: 
 - se troppo alto (problema più facile) più nodi potrebbero risolvere il problema contemporaneamente, rendendo difficile stabilire il vincitore, 
- se troppo basso (problema più difficile) si rischia di rallentare troppo la produzione di nodi

Data una certa potenza di calcolo, c'è una relazione tra *target* e tempo di calcolo, dunque si può scegliere il *target* in funzione del ritmo di produzione desiderato 
(ad esempio in Bitcoin si scelgono target in modo che un problema sia risolvibile in 10 minuti)

I protocolli Proof of Work sono vulnerabili ad [[ Attacchi 50% + 1 |attacchi 50%+1]]: 
se un attaccante possiede la maggioranza della potenza computazionale della rete, può avere il potere di impedire gli aggiornamenti o di sovrascriverli.

#### Proof of Stake ####

Nei **protocolli Proof of Stake** ha maggiore probabilità di creare blocchi possiede più criptovaluta o chi congela più criptovaluta nativa o token registrati sulla blockchain.

- **Soluzione casuale**: 
  Possedere più criptovaluta aumenta la probabilità di diventare un nodo validatore
  
- **Soluzione su base di antichità**:
  Le criptovalute possedute da più aumentano le probabilità di diventare un nodo validatore
  L'antichità si azzera quando una valuta permette al possessore di diventare validatore oppure quando la sua antichità supera una soglia (nessuna partecipazione al consenso da molto tempo)

##### Vantaggi Proof of Stake #####

- Consumo energetico inferiore
- Produzione più rapida dei blocchi, il che garantisce
- Tempo di inserimento dei blocchi costante
- Maggior coinvolgimento dei minatori







