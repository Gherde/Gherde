# Sito personale — Davide Gherdevich

Questo è uno scaffold minimale per pubblicare un sito statico su GitHub Pages.

Sostituisci i contenuti in `index.html` e `styles.css` con i tuoi testi e immagini.

Istruzioni rapide per pubblicare:

git add .
git commit -m "Initial commit"
git branch -M main
git remote add origin git@github.com:USERNAME/REPO.git
git push -u origin main
git remote add origin https://github.com/USERNAME/REPO.git
git push -u origin main
1. Ho preparato i comandi per creare il repository remoto `gherde` per l'utente `dgherdevich`.

2. In locale, dalla cartella del progetto esegui questi comandi (SSH):

```bash
cd "/Users/dgherdevich/SynologyDrive/Sito Davide/davide-gh-pages"
git init
git add .
git commit -m "Initial commit"
git branch -M main
# Se vuoi collegarti al repository che hai trovato su GitHub:
git remote add origin git@github.com:Gherde/Gherde.git
git push -u origin main
```

Se preferisci usare HTTPS, sostituisci la riga `git remote add` con:

```bash
git remote add origin https://github.com/Gherde/Gherde.git
git push -u origin main
```

3. Abilita GitHub Pages: vai nelle impostazioni del repository -> Pages e scegli il ramo `main` (cartella `/ (root)`), poi salva.

4. Dopo pochi minuti il sito sarà disponibile su `https://Gherde.github.io/Gherde` oppure, se il repository fosse chiamato `Gherde.github.io`, su `https://Gherde.github.io`.

Se preferisci, posso aggiornare il remote locale per te (sostituendo un remote esistente). Dimmi se vuoi i comandi per:

- aggiungere il remote (se non esiste) — già mostrato sopra
- sostituire il remote `origin` esistente con il nuovo URL (`git remote set-url origin <url>`)

