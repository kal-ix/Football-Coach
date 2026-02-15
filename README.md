# Football Coach - Sito Web (GitHub Pages)

Questo è il sito web per l'app **Football Coach**, progettato per essere pubblicato su GitHub Pages.

## Contenuto del sito

| File | Descrizione |
|------|-------------|
| `index.html` | Landing page in italiano |
| `index-en.html` | Landing page in inglese |
| `privacy-it.html` | Privacy Policy completa in italiano |
| `privacy-en.html` | Privacy Policy completa in inglese |
| `app-ads.txt` | File AdMob per la verifica app-ads.txt |
| `css/style.css` | Foglio di stile principale |

---

## Istruzioni per la pubblicazione su GitHub Pages

### Passo 1: Crea un account GitHub
1. Vai su [github.com](https://github.com) e crea un account (se non ne hai uno)
2. Scegli un username (es. `kalix-dev`)

### Passo 2: Crea un nuovo repository
1. Clicca su **"New repository"** (pulsante verde "+" in alto a destra)
2. Nome del repository: **`kalix-dev.github.io`** (sostituisci `kalix-dev` con il tuo username)
   - **IMPORTANTE:** Il nome DEVE essere `tuousername.github.io`
3. Seleziona **Public**
4. Clicca **Create repository**

### Passo 3: Carica i file
1. Nella pagina del nuovo repository, clicca **"uploading an existing file"**
2. Trascina **TUTTI** i file e le cartelle dentro la cartella `docs/`:
   - `index.html`
   - `index-en.html`
   - `privacy-it.html`
   - `privacy-en.html`
   - `app-ads.txt`
   - `css/style.css` (crea prima la cartella `css`)
3. Scrivi un messaggio di commit (es. "Initial website upload")
4. Clicca **Commit changes**

### Passo 4: Abilita GitHub Pages
1. Vai su **Settings** (Impostazioni) del repository
2. Nel menu laterale, clicca **Pages**
3. Sotto "Source", seleziona:
   - **Branch:** `main`
   - **Folder:** `/ (root)`
4. Clicca **Save**
5. Attendi 1-2 minuti

### Passo 5: Verifica il sito
Il tuo sito sarà ora accessibile su:
- **`https://tuousername.github.io`** (home page)
- **`https://tuousername.github.io/app-ads.txt`** (file AdMob)
- **`https://tuousername.github.io/privacy-it.html`** (Privacy IT)
- **`https://tuousername.github.io/privacy-en.html`** (Privacy EN)

### Passo 6: Configura Google Play Console
1. Vai su [Google Play Console](https://play.google.com/console)
2. Vai su **Impostazioni** → **Profilo sviluppatore**
3. Nel campo **"Sito web"**, inserisci: `https://tuousername.github.io`
4. Salva le modifiche

### Passo 7: Verifica su AdMob
1. Vai su [AdMob](https://admob.google.com)
2. Controlla la sezione app-ads.txt
3. Clicca **"Verifica la disponibilità di aggiornamenti"**
4. La verifica potrebbe richiedere da pochi secondi a 24 ore

---

## Alternativa: Upload via Git (opzionale - per utenti avanzati)

```bash
# 1. Installa Git se non ce l'hai
# 2. Clona il repository
git clone https://github.com/tuousername/tuousername.github.io.git

# 3. Copia i file della cartella docs/ nella root del repo clonato
# 4. Fai il commit e push
cd tuousername.github.io
git add .
git commit -m "Initial website"
git push origin main
```

---

## Note importanti

- Il file `app-ads.txt` **DEVE** essere accessibile alla root del dominio: `https://tuodominio/app-ads.txt`
- Il dominio inserito su Google Play **DEVE** corrispondere esattamente all'URL del sito
- La propagazione DNS e la verifica AdMob possono richiedere fino a **24 ore**
- GitHub Pages è **gratuito** per repository pubblici
