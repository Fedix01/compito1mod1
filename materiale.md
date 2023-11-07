## Cos'è un algoritmo?

Un algoritmo è una sequenza di istruzioni per risolvere un problema o raggiungere un determinato obiettivo.
L'algoritmo si differenzia dai programmi perchè non è scritto in un linguaggio di programmazione ma in pseudocodice, un esempio è la ricetta per cucinare dei biscotti composta dalla lista degli ingredienti che attraverso vari step porterà a un risultato ovvero il prodotto finito.

## Cos'è una variabile?

Una variabile è un contenitore per dati parzialmente elaborati, è situata in una porzione di memoria  (una o più locazioni di memoria) destinata a contenere valori che possono essere modificati nel corso dell'esecuzione del programma.
Hanno diverse caratteristiche:
1) Nomi unici (ogni variabile ha un nome univoco che la distingue da tutte le altre.
L'operazione per dare un nome a una variabile è detta "dichiarazione".).
2) Totale riutilizzabilità (possiamo sostituire il loro contenuto successivamente nel codice)
3) "Scope" limitato (esistono solo tra la loro dichiarazione e il completamento del relativo blocco di codice)

## undefined e null sono la stessa cosa?

undefined viene impiegato per rappresentare il fatto che una variabile non è stata dichiarata; quest'ultima, inoltre, potrebbe essere stata dichiarata ma non ancora assegnata ad un valore specifico.
null è invece un'assegnazione di valore che significa "nessun valore".
Esempi:

let myFirstVar   
console.log(myFirstVar);  
Il risultato in console sarà undefined.
***
let mySecondVar = 7  
mySecondVar = null;
console.log(mySecondVar);  
Il risultato in console sarà null.