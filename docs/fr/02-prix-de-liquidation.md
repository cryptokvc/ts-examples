# Calcul du prix de liquidation

LiquidationPx illustre un calcul dérivé de la position, de la marge et des paramètres de risque.
Le résultat n'est fiable que si toutes les entrées correspondent au même instantané de compte et de marché.
Les signes des positions longues et courtes doivent rester cohérents à chaque étape.
Les arrondis ne doivent intervenir qu'à la frontière d'affichage ou selon les règles explicites du protocole.
Une estimation locale ne remplace pas le moteur de risque qui décide réellement de la liquidation.
L'interface doit donc présenter provenance, horodatage et caractère indicatif de la valeur.

Suite : [03 — Ordres](03-construction-des-ordres.md).
