# web-server-golang

Questo progetto è un semplice server web scritto in Go che serve file statici. 

## Struttura del Progetto

Il progetto è strutturato nel seguente modo:

*   **`web-server-golang/`**: La cartella principale del progetto.
    *   **`static/`**: Contiene i file statici che il server web serve.
        *   **`form.html`**: Un file HTML per la gestione di un form.
        *   **`index.html`**: Un file HTML che rappresenta la homepage del sito.
    *   **`main.go`**: Il file principale contenente il codice Go del server web.

## Come Eseguire il Progetto

Assicurati di avere Go installato nel tuo sistema. Puoi scaricare Go da [https://go.dev/dl/](https://go.dev/dl/).

1.  **Clona il repository:**
    ```bash
    git clone <URL_DEL_TUO_REPOSITORY>
    cd web-server-golang
    ```

2.  **Esegui il server:**
    ```bash
    go run main.go
    ```

3.  **Apri il browser:**
    Apri il tuo browser e vai all'indirizzo `http://localhost:8080`. (L'indirizzo e la porta possono essere modificati nel codice `main.go`).

## Funzionalità

*   Il server web serve i file statici dalla cartella `static/`.
*   La homepage del sito è `index.html`.
*   È presente un file `form.html` che potrebbe essere utilizzato per gestire input da parte dell'utente.
*   Il server web è sviluppato usando il package `net/http` di Go.

## Note per lo Sviluppo

*   Il file `main.go` contiene il codice principale del server web.
*   La cartella `static/` è quella che contiene i file statici da servire, se desideri aggiungere o modificare dei file html/css o altri file statici è qui che devi modificarli.
*   Per la gestione di richieste più complesse o per utilizzare framework web Go, sarebbe necessario aggiungere delle librerie e modificare il codice nel file `main.go`.

## Contributi

Se desideri contribuire a questo progetto, segui questi passi:

1.  Fai un fork del repository.
2.  Crea un branch per la tua funzionalità (`git checkout -b nome-funzionalita`).
3.  Fai le tue modifiche e committa (`git commit -m "Aggiunta funzionalità"`).
4.  Fai il push al tuo fork (`git push origin nome-funzionalita`).
5.  Crea una Pull Request.

