# Construction des ordres

OrderExample assemble l'actif, le sens, le prix, la taille et les options avant signature.
Normaliser prix et taille selon les incréments admis évite de signer une intention rejetée ou différente de l'affichage.
L'adresse du compte, le réseau et l'environnement API doivent être vérifiés ensemble.
Les nonces ou horodatages protègent la fraîcheur mais exigent une stratégie lors des reprises et doubles clics.
Une nouvelle tentative ne doit pas créer deux ordres lorsque la première réponse est seulement retardée.
Le client doit réconcilier l'identifiant retourné avec l'état observé par l'API.

Suite : [04 — Signatures](04-signatures-et-domaines.md).
