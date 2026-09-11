# Signatures et séparation de domaines

Signing montre que la sérialisation exacte précède toute signature Hyperliquid.
L'ordre des champs, les types, le chain ID et le domaine doivent être identiques entre client et vérificateur.
Une signature valide ne prouve pas que l'utilisateur a compris une charge utile transformée après l'affichage.
Le frontend doit afficher les paramètres économiques issus du même objet finalement signé.
Les clés privées ne doivent jamais entrer dans des exemples, journaux ou variables suivies par Git.
Les signatures EIP-712 utilisées autour de HyperEVM doivent rester séparées des actions natives Hyperliquid.

Suite : [05 — Frontière HyperEVM](05-frontiere-hyperevm.md).
