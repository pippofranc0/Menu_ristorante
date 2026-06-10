# Installazione

Questa guida spiega come scaricare e avviare il progetto **Menu Ristorante** sul proprio computer.

Il progetto è un sito statico, quindi non richiede installazione di pacchetti o configurazioni particolari. Sono necessari solo un browser moderno, Git e una connessione a internet.

## Requisiti

Prima di iniziare assicurarsi di avere:

- Git installato sul computer
- un browser moderno, ad esempio Chrome, Firefox, Edge o Safari
- una connessione internet attiva

## Verificare Git

Aprire il terminale e digitare:

```bash
git --version
```

Se Git è installato correttamente, il terminale mostrerà la versione installata.

Se il comando non viene riconosciuto, installare Git dal sito ufficiale:

```text
https://git-scm.com/
```

## Clonare la repository

Dal terminale, scegliere la cartella in cui si vuole salvare il progetto e lanciare il comando:

```bash
git clone https://github.com/pippofranc0/Menu_ristorante
```

Entrare poi nella cartella del progetto:

```bash
cd Menu_ristorante
```

## Avviare il sito

Aprire il terminale nella cartella del progetto ed eseguire:

```bash
python -m http.server 8000
```

Poi aprire nel browser:

```text
http://localhost:8000
```

Per interrompere il server locale, tornare nel terminale e premere:

```text
CTRL + C
```

In alternativa è possibile usare l'estensione Live Server di Visual Studio Code.


Dalla homepage sarà possibile navigare verso:

- `menu.html`, per visualizzare il menu creato con l'API locale.
- `aprenotazioni.html`


## Struttura principale

I file principali del progetto sono:

```text
Menu_ristorante/
├── README.md
├── index.html
├── menu.html
├── prenotazioni.html
├── style.css
├── script.js
├── data.json
├── docs/
│   ├── installazione.md
│   ├── faq.md
│   └── api.md
└── assets/
    └── immagini/
```

## Aggiornare il progetto

Se il progetto è già stato clonato e si vogliono scaricare eventuali aggiornamenti dalla repository, entrare nella cartella del progetto e usare:

```bash
git pull
```
