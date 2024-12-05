
La **crittografia simmetrica** si basa sulla condivisione di una chiave di cifratura identica per mittente e destinatario dei messaggi.

Il limite di questo metodo è la grande quantità di chiavi necessarie (una per ogni coppia di utenti)
e la difficoltà di comunicare la chiave stessa in modo sicuro.


La **crittografia a chiave pubblica** (crittografia asimmetrica)  è stata ideata per superare i limiti della crittografia simmetrica: richiede l'uso di meno chiavi ed è più sicura.

Ogni utente ha una chiave pubblica e una chiave privata.
Esse sono legate in modo tale che risalire alla chiave pubblica a partire da quella privata sia semplice, ma sia difficile ottenere la chiave privata dalla chiave pubblica.

La chiave pubblica di un utente *A* è visibile a tutti gli  altri utenti, ed è utilizzata da essi per cifrare i messaggi diretti ad *A*.
La chiave privata di *A* è visibile solo ad *A*, e viene usata da *A* per decifrare tutti i messaggi ricevuti.

La cifratura a chiave pubblica è lenta, e viene usata di solito solo per come mezzo per scambiare chiavi per cifratura simmetrica tra gli utenti.

