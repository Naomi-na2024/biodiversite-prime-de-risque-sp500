# La biodiversité est-elle valorisée par les marchés financiers ?

La préservation de la biodiversité est devenue un enjeu majeur pour l'ensemble de la société. Ce projet étudie dans quelle mesure cette préoccupation se reflète dans les marchés financiers, à partir de 25 ans de données du S&P 500 (2000-2025).

**Données** : S&P 500 (Stooq), facteurs Fama-French (Kenneth French Data Library), indice d'attention à la biodiversité construit par NLP sur la presse américaine.

**Méthodes** :
- comparaison de modèles (OLS, Ridge, Random Forest, Gradient Boosting)
- régression Fama-French 5 facteurs
- Value-at-Risk et régression quantile
- étude d'événement autour de la COP15

**Outils** : Python, pandas, statsmodels, scikit-learn, matplotlib.

L'analyse complète se trouve dans le notebook.

## Parcourir le projet

- **Notebook** : [biodiversite_prime_de_risque_sp500.ipynb](https://nbviewer.org/github/Naomi-na2024/biodiversite-prime-de-risque-sp500/blob/main/biodiversite_prime_de_risque_sp500.ipynb)
- **Présentation** : [Presentation_Biodiv.pdf](Presentation_Biodiv.pdf) ([version PowerPoint](Presentation_Biodiv.pptx))
- **Site du projet** : [naomi-na2024.github.io/biodiversite-prime-de-risque-sp500](https://naomi-na2024.github.io/biodiversite-prime-de-risque-sp500/)
