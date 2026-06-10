# FAQ

Questa pagina raccoglie le domande frequenti relative al progetto **Menu ristorante**.

## Non riesco ad aprire il sito, come posso fare?

Assicurarsi che la repository sia stata clonata correttamente e che si stia aprendo il file `index.html` con un browser moderno.

In alternativa è possibile avviare un server locale dalla cartella del progetto:

```bash
python3 -m http.server 8000
```

Poi aprire nel browser:

```text
http://localhost:8000
```

## Il progetto richiede installazione di pacchetti?

No. Il progetto è un sito statico realizzato con HTML, CSS e JavaScript.

Non è necessario installare dipendenze con `npm` o altri package manager.

## Serve una connessione internet?

Sì. La connessione internet è necessaria per:

- caricare Bootstrap tramite CDN
- clonare la repository


## Quali API vengono utilizzate?

Il progetto utilizza un'API locale.


```text
data.json
```

Il file script.js carica i dati con:

```text
fetch("data.json")
```

I menu vengono mostrati nella pagina `menu.html`, mentre le prenotazioni vengono mostrate nella pagina `prenotazioni.html`.

## I dati del menu sono reali?

No. I dati sono fittizi.

Sono utili per simulare un sito dinamico senza dover creare un database reale.


## Dove si trova il codice JavaScript?

Il codice JavaScript si trova nel file:

```text
script.js
```

## Dove si modifica lo stile del sito?

Lo stile personalizzato del sito si trova nel file:

```text
style.css
```

Il progetto utilizza anche Bootstrap per migliorare il layout e la responsività.

## Quali sono le pagine principali?

Le pagine principali del progetto sono:

- `index.html`, homepage del sito
- `menu.html`, pagina con i menu
- `prenotazioni.html`, pagina con le prenotazioni

## Il sito è responsive?

Sì. Il sito utilizza Bootstrap e alcune regole CSS personalizzate per adattarsi anche a dispositivi mobili.

## Posso modificare i contenuti del sito?

Sì. È possibile modificare:

- i testi nelle pagine HTML
- lo stile nel file `style.css`
- la logica di caricamento dati nel file `script.js`

## Come posso aggiornare il progetto dopo averlo clonato?

Entrare nella cartella del progetto e usare:

```bash
git pull
```

Questo comando scarica eventuali aggiornamenti dalla repository remota.

## Posso usare il progetto senza Git?

Sì, è possibile scaricare la repository come file ZIP da GitHub.

Tuttavia Git è consigliato perché permette di clonare e aggiornare più facilmente il progetto.

## Che licenza usa il progetto?

Il progetto utilizza una licenza MIT.

Per maggiori informazioni consultare il file:

```text
LICENSE
```
