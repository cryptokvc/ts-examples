# Frontière Hyperliquid–HyperEVM

Ce dépôt traite principalement des calculs frontend et actions natives Hyperliquid, pas de l'exécution complète HyperEVM.
Viem apporte des primitives EVM, mais une transaction HyperEVM suit son propre nonce, son chain ID et sa finalité.
Une application combinée doit séparer solde Core, solde EVM, action signée et transaction on-chain.
Le passage d'actifs entre environnements ajoute un état asynchrone qui doit être réconcilié explicitement.
Confondre confirmation API et confirmation EVM peut provoquer un affichage prématuré ou une nouvelle tentative dangereuse.
Ce chapitre documente donc la frontière et l'absence de garantie plutôt que d'inventer une intégration non présente.
Aucune installation, exécution, signature ou transaction n'a été réalisée ; le dépôt ne définit pas de tests applicatifs.
