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
   (Pokud používáš `/docs`, vyber `main` + `/docs`.)
5. Ulož. Po chvilce se zobrazí publikovaná URL (např. `https://uzivatel.github.io/repozitar`).

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
