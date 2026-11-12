<h1 align="center">La biodiversité est-elle valorisée par les marchés financiers ?</h1>

<p align="center">
  <em>Analyse économétrique et prédictive de la prime de risque du S&amp;P 500 (2000–2025)</em><br>
  Mémoire de fin d'études · Master 2 Data Science · Naomi Blesson Nandjui
</p>

---

## Contexte

La préservation de la biodiversité est devenue un enjeu majeur pour l'ensemble de la société. La dégradation des écosystèmes peut affecter la production, fragiliser les chaînes d'approvisionnement et, à terme, peser sur la valeur des actifs.

Ce projet étudie dans quelle mesure cette préoccupation se reflète dans les marchés financiers, à partir de 25 ans de données journalières du S&P 500.

> **Question de recherche** : l'attention portée à la biodiversité est-elle associée à la prime de risque du S&P 500, au-delà des facteurs financiers traditionnels ?

## Parcourir le projet

| | |
|---|---|
| **Notebook** | [biodiversite_prime_de_risque_sp500.ipynb](https://nbviewer.org/github/Naomi-na2024/biodiversite-prime-de-risque-sp500/blob/main/biodiversite_prime_de_risque_sp500.ipynb) |
| **Présentation** | [Presentation_Biodiv.pdf](Presentation_Biodiv.pdf) · [version PowerPoint](Presentation_Biodiv.pptx) |
| **Site du projet** | [naomi-na2024.github.io/biodiversite-prime-de-risque-sp500](https://naomi-na2024.github.io/biodiversite-prime-de-risque-sp500/) |

## Données

- **S&P 500** : cours journaliers (Stooq)
- **Facteurs Fama-French** : Kenneth French Data Library
- **Indice d'attention à la biodiversité** : construit par NLP sur la presse américaine

4 020 observations communes sur la période 2000–2025.

## Méthodologie

1. Comparaison de modèles prédictifs : OLS, Ridge, Random Forest, Gradient Boosting
2. Régression Fama-French à 5 facteurs
3. Value-at-Risk et régression quantile
4. Étude d'événement autour de la COP15

## Outils

Python · pandas · statsmodels · scikit-learn · matplotlib
