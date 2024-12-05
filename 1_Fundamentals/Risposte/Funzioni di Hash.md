
Trasformano sequenze di bit di lunghezza arbitraria in sequenze di bit di lunghezza fissata.

Il risultato dell'applicazione di una funzione di hash è detto *impronta* o *digest* dell' argomento.

##### Caratteristiche #####

- Non iniettive (vanno da un dominio infinito a un codominio finito)
- Applicazione facile e rapida
- Difficili da invertire:
  Dati *z* e *h* è difficile trovare *x* tale che *h(x) = z*
- Difficile trovare collisioni:
  Difficile trovare *a* e *b* diversi tali che *h(a) = h(b)*
- Effetto valanga:
  Cambiare un solo bit nell'input causa variazioni radicali dell'output
  Difficile prevedere l'output con un input simile a quello corrente


Sono utilizzate nei protocolli di consenso [[Proof of work e Proof of Stake| Proof of Work]] e per [[Zero-Knowledge-Proof]]

L'effetto valanga è sfruttato dagli algoritmi proof of work per fare in modo che l'unico modo per poter ottenere un hash sotto la soglia sia quello di procedere per tentativi, senza possibilità di prevedere il comportamento della funzione in base ai risultati già ottenuti.

##### Utilizzo in blockchain #####

In blockchain le funzioni di hash sono usate per collegare tra loro i blocchi di transazioni in una catena ideale.

Ogni blocco contiene al suo interno l'*impronta* del blocco precedente, il quale a sua volta contiene l' impronta del blocco precedente.

La rapidità di calcolo delle funzioni di hash consente di risalire facilmente la catena.

##### Funzioni hash più utilizzate #####

- Ripetid160
- SHA (5 funzioni scritte dalla NSA)
- SHA1 (output di 160 bit)
- SHA2
	- SHA224
	- SHA256
	- SHA512
	- SHA384
- SHA3
	- Keccak250





