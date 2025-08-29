# Orario Primaria – GitHub Pages

Questa cartella è pronta per essere pubblicata su **GitHub Pages**.

## Passi (semplici)
1. Vai su GitHub e crea un nuovo repository (nome suggerito: `orario-primaria`).
2. Scarica questo pacchetto ZIP sul tuo computer e **scompattalo**.
3. Trascina i file (`index.html` e `.nojekyll`) dentro al repository su GitHub (puoi usare l'upload via web).
4. Vai su **Settings → Pages** e in **Build and deployment** imposta:
   - **Source**: `Deploy from a branch`
   - **Branch**: `main` (cartella `/root`), poi **Save**.
5. Torna su **Settings → Pages** e copia il link che appare (tipo: `https://tuo-utente.github.io/orario-primaria/`).

## Uso
- Apri il link di GitHub Pages.
- Clicca su **Scegli file** e carica `TAB ORARIO.xlsx` (o il tuo Excel con `GIORNO`/`ORARIO` e riga classi).
- Controlla/edita classi e slot.
- Compila la sezione **Assegna docenti** se vuoi l'export per docente.
- Usa i bottoni **Esporta Excel per classe** / **Esporta Excel per docente**.

## Note
- Il file `.nojekyll` dice a GitHub Pages di **non** usare Jekyll (evita problemi con percorsi/asset).
- Tutto gira **lato browser**: non serve backend.
