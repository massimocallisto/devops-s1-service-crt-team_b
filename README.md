# Servizio della PA - Gestione Pratiche

## Descrizione

Gestire le pratiche degli utenti per permettere l'inserimento, la revisione e la firma digitale della pratica.

---

## Struttura del Progetto

Esempio di organizzazione delle cartelle:

```
📦 nome-progetto
 ┣ 📂 src/              # codice sorgente
 ┣ 📂 profiles/         # profili dei partecipanti
 ┣ 📂 docs/             # documentazione e materiali
 ┣ 📄 README.md         # questo file
 ┗ 📄 LICENSE           # licenza del progetto
```

---

## Contributi

1. Crea un branch di sviluppo:
   ```bash
   git checkout -b feature/<nome-feature>
   ```
2. Effettua le modifiche e il commit:
   ```bash
   git commit -m "Aggiunge nuova funzionalità"
   ```
3. Esegui il push e apri una Pull Request su GitHub.

---

## Autori

- [Mario Rossi](profiles/mario.profile.md)
- [Lucia Bianchi](profiles/lucia.profile.md)
- [Giovanni Verdi](profiles/giovanni.profile.md)
- [Walter Naldoni](profiles/Walshiny.profile.md)
- [Giampiero Starnino](profiles/giampiero.profile.md)
- [Roberto Monai](profiles/robext68.profile.md)
- [KB3268](profiles/KB3268.profile.md)

---

## Licenza

Questo progetto è distribuito sotto licenza MIT.  
Consulta il file [LICENSE](LICENSE) per maggiori dettagli.

## Docker Instructions

### Building and Running with Docker

You can run this application using Docker in two ways: using Docker directly or using Docker Compose.

#### Using Docker directly

1. Build the Docker image:

    docker build -t fastapi-status .

2. Run the container:

    docker run -p 8000:8000 --name fastapi-status fastapi-status

### Testing the API

Once the container is running (using either method), you can test the API check http://localhost:8000/status



