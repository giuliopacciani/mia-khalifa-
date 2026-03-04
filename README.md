# mia-khalifa-

Sito statico contenente audio e immagini.

## Deploy su GitHub Pages

Per pubblicare automaticamente il contenuto su GitHub Pages:

1. Assicurati che il repository sia su GitHub (`origin`) e che il branch `main` sia aggiornato.
2. Crea (o aggiorna) il file di workflow qui sotto e committalo.
3. Vai nelle impostazioni del repository su GitHub: **Settings > Pages**.
   - Scegli il branch `gh-pages` (l'action lo genera automaticamente) o `main` con la cartella `/`.
4. Dopo il primo push, GitHub Pages creerà un sito all'URL `https://<tuo-username>.github.io/mia-khalifa-/`.

Il workflow di esempio (`.github/workflows/pages.yml`) costruisce e pubblica il contenuto su `gh-pages` ogni volta che si esegue un push su `main`.
