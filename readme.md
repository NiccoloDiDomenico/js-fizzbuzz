Consegna:
Scrivi un programma che stampi i numeri da 1 a 100,
ma per i multipli di 3 stampi “Fizz” al posto del numero e per i multipli di 5 stampi Buzz.
Per i numeri che sono sia multipli di 3 che di 5 stampi FizzBuzz.
Prima di partire a scrivere codice poniamoci qualche domanda:
Come faccio a sapere se un numero è divisibile per?
Abbiamo visto qualcosa di particolare che possiamo usare?

Consigli del giorno:
1. scriviamo sempre prima dei commenti in italiano per capire cosa vogliamo fare
2. proviamo ad immaginare le operazioni che vogliamo far svolgere al nostro programma così come lo faremmo "a mano"

// DOMANDA
- per sapere se quel numero è divisibile per x utilizzero la formula: num % x === 0 


// ESECUZIONE LOGICA
inserisco un ciclo di numeri da 1 a 100:
    - for (let i=x; i <= y; i++) 

inserisco un istruzione condizionale all'interno del ciclo:
    - for (let i=x; i <= y; i++) {
        se (un num è divisibile per 3)
        quel num si chiamerà "Fizz"
    } altrimenti se (un num è divisibile per 5) {
        quel num si chiamerà "Buzz"
    } altrimenti (un numero è divisibile per 3 & per 5)
        quel num si chiamerà "FizzBuzz".
