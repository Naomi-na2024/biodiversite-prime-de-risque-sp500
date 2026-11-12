# La biodiversité est-elle valorisée par les marchés financiers ?

La préservation de la biodiversité est devenue un enjeu majeur pour l'ensemble de la société. Ce projet étudie dans quelle mesure cette préoccupation se reflète dans les marchés financiers, à partir de 25 ans de données du S&P 500 (2000-2025).

**Données** : S&P 500 (**Stooq**), facteurs Fama-French (**Kenneth French Data Library**), indice d'attention à la biodiversité issu de la presse américaine (sur demande par mail).

**Méthodes** :
- comparaison de modèles (OLS, Ridge, Random Forest, Gradient Boosting)
- régression Fama-French 5 facteurs
- Value-at-Risk et régression quantile
- étude d'événement autour de la COP15

**Outils** : Python, pandas, statsmodels, scikit-learn, matplotlib.

**Mots-clés** : `python` `econometrics` `finance` `risk-management`

## Ce que montre l'analyse

**À ce jour, la biodiversité ne constitue pas un facteur de valorisation sur le marché américain.** L'information circule et l'attention monte, sans se traduire dans la rémunération du risque.

## Parcourir le projet

- **Notebook** : [biodiversite_prime_de_risque_sp500.ipynb](biodiversite_prime_de_risque_sp500.ipynb)
- **Présentation** : [Presentation_Biodiv.pdf](Presentation_Biodiv.pdf)
- **Données** :<br>
  &nbsp;&nbsp;&nbsp;&nbsp;\- S&P 500 (Stooq) : [télécharger](https://stooq.com/q/d/l/?s=%5Espx&i=d)<br>
  &nbsp;&nbsp;&nbsp;&nbsp;\- Facteurs Fama-French 5 facteurs (Kenneth French Data Library) : [télécharger](https://mba.tuck.dartmouth.edu/pages/faculty/ken.french/ftp/F-F_Research_Data_5_Factors_2x3_daily_CSV.zip)<br>
  &nbsp;&nbsp;&nbsp;&nbsp;\- Facteur Momentum (Kenneth French Data Library) : [télécharger](https://mba.tuck.dartmouth.edu/pages/faculty/ken.french/ftp/F-F_Momentum_Factor_daily_CSV.zip)<br>
  &nbsp;&nbsp;&nbsp;&nbsp;\- Biodiversité : sur demande par mail

---

Contact : [nandjuinaomi@gmail.com](mailto:nandjuinaomi@gmail.com)
