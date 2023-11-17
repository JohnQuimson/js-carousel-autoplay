# JS Carousel autoplay

### Aggiungere la funzionalità di autoplay, ovvero: ogni 3 secondi l'immagine cambierà alla successiva

Per fare ciò utilizzerò le timing functions, più nello specifico:

- setInterval, al quale darò una funzione che verrà eseguita dopo 3 secondi (3000ms), all'infinito. Quindi procedo così:

1. creo la funzione per far si che mi mostri l'immagine successiva e mi nasconda quella corrente
2. Creo una variabile e ci metto setInterval, con la funzione precedentemente creata e il timer di 3 secondi
