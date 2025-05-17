# GliderAI - YouTube Video Uploader

**GliderAI** è un'app Python creata per caricare automaticamente video su YouTube. È pensata per l'uso personale, con la possibilità di caricare video, aggiungere descrizioni, tag e miniature personalizzate. 

Questa applicazione utilizza l'API di YouTube per automatizzare il processo di caricamento dei video su un account YouTube specifico.

## Funzionalità principali
- Caricamento di video su YouTube
- Aggiunta di descrizioni, titoli e tag ai video
- Programmazione della pubblicazione dei video
- Aggiunta di miniature personalizzate ai video
- Gestione di più playlist YouTube

## Come funziona

1. **Autenticazione**: Quando l'app viene eseguita per la prima volta, si autentica con l'API di YouTube tramite OAuth2, richiedendo l'accesso al tuo account YouTube.
2. **Caricamento Video**: Dopo l'autenticazione, puoi scegliere un video e un file di descrizione da caricare su YouTube. L'app gestisce anche la selezione di tag e la pubblicazione programmata.
3. **Programmazione**: L'app ti permette di programmare i video per essere pubblicati in orari ottimali, scegliendo tra le opzioni di pubblicazione settimanale.

## Prerequisiti
- Python 3.6 o superiore
- Le seguenti librerie Python:
  - `google-auth`
  - `google-auth-oauthlib`
  - `google-auth-httplib2`
  - `google-api-python-client`
  - `pytz`
  
Puoi installarle eseguendo:
pip install -r requirements.txt

Configurazione
Ottieni le credenziali di Google API: Vai alla Google Cloud Console e crea un progetto. Abilita l'API YouTube Data v3 e ottieni il file client_secrets.json.

Configura il progetto: Inserisci il file client_secrets.json nella cartella del progetto.

Esegui lo script: Avvia lo script Python per caricare i video. La prima volta dovrai autenticarti nel tuo account Google tramite un browser.

Autore
Glideraiscript (https://glideraiscript.github.io/ytapp/)

App utilizzata a scopo personale per automatizzare l'upload di contenuti su YouTube.

Licenza
Distribuito sotto la licenza MIT. Vedi LICENSE per maggiori dettagli
