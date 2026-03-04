# Pipeline Accidents (2010–2016) – Počítačová analýza dát / Computer Data Analysis

## Slovensky
Projekt z predmetu **Počítačová analýza dát**. Cieľom bolo vybrať si ľubovoľný dataset a spraviť nad ním analýzu.  
V tomto projekte analyzujem dataset **Pipeline Accidents (2010–2016)** (PHMSA / US DOT), ktorý obsahuje incidenty ropných potrubí vrátane lokality, príčin, uniknutého množstva a nákladov.

### Ciele projektu
- Exploračná analýza dát (**EDA**) – základný prehľad, rozdelenia, top štáty, príčiny
- Skúmanie vzťahov medzi premennými pomocou štatistických metód

### Použité metódy
- Vizualizácie (bar/pie grafy, boxploty, distribúcie)
- Pivot tabuľky (náklady/úniky podľa typu potrubia)
- **Welchov t-test**: porovnanie priemerných nákladov ABOVEGROUND vs UNDERGROUND
- **Pearson korelácia**:
  - Liquid Ignition vs Liquid Explosion
  - All Costs vs Net Loss (Barrels)

### Hlavné zistenia (stručne)
- Najviac incidentov je v roku 2015 (v rámci analyzovaného obdobia).
- Incidenty sú koncentrované v niektorých štátoch (Texas patrí medzi najvýraznejšie).
- Najčastejšia príčina: **MATERIAL/WELD/EQUIP FAILURE**.
- Takmer všetky incidenty sú **ONSHORE**.
- Priemerné náklady sa štatisticky líšia medzi ABOVEGROUND a UNDERGROUND (p < 0.05).
- Ignition a Explosion majú stredne silný kladný vzťah (r ≈ 0.39, veľmi malé p).

### Tech / nástroje
Python (`pandas`, `numpy`, `matplotlib`, `seaborn`, `scipy`), Jupyter Notebook.

### Súbory
- `Molnar_projekt.ipynb` – notebook s analýzou
- `Molnar_Projekt.pdf` – exportovaný report
- `Molnar_projekt.stw` – Statistica workspace s výstupom

### Dataset
Kaggle – “Pipeline Accidents” (PHMSA / US DOT).

---

## English
Course project for **Computer Data Analysis**. The goal was to choose any dataset and analyze it.  
This project analyzes the **Pipeline Accidents (2010–2016)** dataset (PHMSA / US DOT), covering oil pipeline incidents including location, cause categories, released volume, and costs.

### Project goals
- **EDA** (overview, distributions, top states, main causes)
- Explore relationships using statistical methods

### Methods used
- Visualizations (bar/pie charts, boxplots, distributions)
- Pivot tables (costs/releases by pipeline type)
- **Welch’s t-test**: average cost comparison (ABOVEGROUND vs UNDERGROUND)
- **Pearson correlation**:
  - Liquid Ignition vs Liquid Explosion
  - All Costs vs Net Loss (Barrels)

### Key findings (short)
- 2015 has the highest incident count within the analyzed period.
- Incidents are concentrated in certain states (Texas is among the top).
- Most common cause: **MATERIAL/WELD/EQUIP FAILURE**.
- Almost all incidents are **ONSHORE**.
- Average costs differ significantly between ABOVEGROUND and UNDERGROUND (p < 0.05).
- Ignition and explosion show a moderate positive relationship (r ≈ 0.39, extremely small p-value).

### Tech / tools
Python (`pandas`, `numpy`, `matplotlib`, `seaborn`, `scipy`), Jupyter Notebook.

### Files
- `Molnar_projekt.ipynb` – analysis notebook
- `Molnar_Projekt.pdf` – exported report
- `Molnar_projekt.stw` – Statistica workspace

### Dataset
Kaggle – “Pipeline Accidents” (PHMSA / US DOT).

---

## Autor / Author
Martin Molnár
