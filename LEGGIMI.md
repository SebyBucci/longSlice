# longSlice

Consegna dell'esercizio longslice:
Data una stringa formata solo da cifre, calcolare il prodotto più grande per una sua sottostringa contigua di cifre di lunghezza N.

Commento del codice:
Abbiamo utilizzato il metodo GetLargestProduct che verifica se lo span è uguale a zero o maggiore della lunghezza della stringa di cifre o se è un valore negativo, 
in tal caso lancia un'eccezione ArgumentException.
Successivamente, il metodo esegue un ciclo for che scorre la stringa di cifre e per ogni sequenza di cifre consecutive di lunghezza span,
calcola il prodotto e lo confronta con il prodotto massimo trovato finora, alla fine restituisce il valore del prodotto massimo trovato.
