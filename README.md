# Benchmark quiz (Demo)

Demo benchmark quiz web app. Permette la scelta del livello di difficoltà e del numero di domande.
Mostra il punteggio e le risposte corrette. 

## Eseguire l'applicazione con Docker (consigliato)

- Se non hai Docker installato, segui le istruzioni dal sito ufficiale: [Docker](https://docs.docker.com/desktop/)
- Esegui `docker build . -t benchmark-app` per creare l'immagine dell'applicazione con tutte le dipendenze necessarie al suo funzionamento
- Esegui `docker -d --name benchmark-container -p 4200:4200 benchmark-app:latest` per creare ed eseguire il container per avviare l'applicazione
- Naviga `http://localhost:4200/`

## Eseguire l'applicazione sulla tua macchina locale

- Scaricare la repo
- Aprire index.html con il browser
- oppure, aprire la cartella con IDE (es. Visual Studio Code) ed avviare Live Server
