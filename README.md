# Šablona projektů — SPSMotol

Tento repozitář slouží jako univerzální šablona pro studentské projekty. Všechny projekty budou veřejné a publikované přes GitHub Pages.

Jak vytvořit svůj repozitář
1. Klikni na **Use this template → Create a new repository**.  
2. Jako owner vyber organizaci **SPSMotol** (oprávnění ti dá učitel).  
3. Pojmenuj repozitář (`prijmeni`) a vytvoř ho.

## Co musí být v odevzdaném repozitáři
- `README.md` s těmito poli:
  - **Jméno:**  
  - **Třída / ročník:**  
  - **Název projektu:**  
  - **Krátký popis:** (max 1–2 věty)  
  - **URL GitHub Pages:**  
- Funkční web: `index.html` v kořeni nebo `/docs/index.html`.  
- Repozitář musí být **public**.  
- (Volitelně) `LICENSE`.

## Jak publikovat jednoduché HTML (jeden soubor)
1. Vytvoř soubor `index.html` v kořeni repozitáře (root).  
2. Commitni a pushni do větve `main` (nebo default branch).  
3. V repozitáři otevři **Settings → Pages**.  
4. V sekci „Source“ vyber:
   - **Branch:** `main`  
   - **Folder:** `/ (root)`  
5. Ulož. Po chvilce se zobrazí publikovaná URL (např. `https://uzivatel.github.io/repozitar`).

Ukázka GitHub Pages: <a href="https://spsmotol.github.io/template/" target="_blank" rel="noopener noreferrer">https://spsmotol.github.io/template</a>

Ukázkový index.html (zdroják)
```html
<!doctype html>
<html lang="cs">
<head>
  <meta charset="utf-8">
  <title>Moje práce</title>
</head>
<body>
  <h1>Jméno Příjmení — Název projektu</h1>
  <p>Krátký popis projektu.</p>
</body>
</html>
```
