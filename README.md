# Earnext AI Lead & Client Intelligence System

Sito statico pronto per GitHub Pages.

## Contenuto

- `index.html` — applicazione web del prototipo Earnext AI Lead & Client Intelligence System
- `.nojekyll` — file utile per pubblicazione corretta su GitHub Pages

## Come pubblicarlo su GitHub Pages

1. Crea un nuovo repository su GitHub.
2. Carica nella root del repository i file:
   - `index.html`
   - `.nojekyll`
3. Vai su **Settings → Pages**.
4. In **Build and deployment**, seleziona:
   - Source: `Deploy from a branch`
   - Branch: `main`
   - Folder: `/root`
5. Clicca **Save**.
6. Dopo qualche minuto GitHub pubblicherà il sito.

## Uso del tool

Il tool consente di:
- caricare un CSV generato dal modello CRM
- visualizzare lead intelligence
- consultare dashboard
- generare email AI
- generare report AI
- copiare il report testuale
- stampare/salvare il report in PDF

## Privacy

Il file è un sito statico lato browser: i dati caricati via CSV vengono elaborati localmente dal browser dell'utente e non vengono inviati a server esterni dall'applicazione.
Le librerie e i font sono caricati da CDN esterni come indicato nel codice HTML.
