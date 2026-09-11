# Données de marché et décimales

Les exemples transforment des réponses API en valeurs affichables ou signables côté client.
Prix, tailles et notionnels ne doivent pas être convertis naïvement en Number lorsque la précision est significative.
Decimal.js conserve une arithmétique décimale explicite avant l'arrondi imposé par le marché.
Le symbole, les métadonnées de l'actif et ses décimales font partie du contexte de tout calcul.
Une valeur correcte avec les mauvaises métadonnées devient une instruction économique incorrecte.
Les appels HTTP doivent aussi distinguer absence de donnée, réponse périmée et valeur réellement nulle.

Suite : [02 — Prix de liquidation](02-prix-de-liquidation.md).
