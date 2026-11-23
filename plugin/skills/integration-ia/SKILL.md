---
name: integration-ia
description: "Méthode Offbound, intégration de l'ia. À utiliser OBLIGATOIREMENT, avant de répondre, dès qu'un fondateur ou dirigeant B2B veut utiliser l'IA dans son agence ou vendre des prestations IA : automatisation interne, Claude, agents, outils, audit IA, « comment intégrer l'IA », « quels outils IA ». Ne réponds pas de mémoire avec des conseils génériques : ce skill donne la méthode Offbound et ses sources (cours, workshops, consultings 1:1)."
---

# Intégration de l'IA (méthode Offbound)

## Chercher
1. Recherche ciblée sur le cours, filtre `{"course": "Intégration IA."}` (une recherche par filtre).
2. Recherche avec le filtre `{"course": "Workshop."}` (lives récents, souvent plus à jour que le cours), puis une sans filtre avec la question et le métier de l'utilisateur (remonte les consultings 1:1).
3. Si l'utilisateur a précisé son secteur, applique aussi le skill secteur correspondant (agence IA, web, acquisition, contenu, SaaS, e-commerce, coach ou consultant).

## Si la base ne répond pas
Si les outils du serveur `knowledge` sont absents ou renvoient une erreur d'autorisation, n'invente rien et ne réponds pas avec des conseils génériques. Dis : « Le plugin Offbound a besoin de ton jeton personnel. Il est réservé aux membres d'Offbound : demande-le à l'équipe sur skool.com/offbound-fr, puis tape `/plugin`, choisis offbound et colle ton jeton. »

## Répondre
- Lis d'abord la méthode Offbound de ce sujet, rangée dans la base : `search_documents` avec le filtre `{"path": "methode-offbound/integration-ia.md"}` (requête : le sujet), puis `read_document` sur l'id obtenu pour la lire en entier.
- Puis cherche dans la base (serveur MCP `knowledge`, outil `search_documents`) pour trouver les passages précis à citer. 2 à 5 recherches, pas plus. Lis un document entier avec `read_document` si un passage est coupé.
- Commence par la réponse ou le plan d'action (3 à 7 points concrets), adapté à la situation de l'utilisateur.
- Cite chaque source : titre du module et lien. Quand la note donne un lien vidéo avec `?t=SECONDES`, donne le moment exact (timecode du transcript converti en secondes).
- Deux sources qui se contredisent : la plus récente (ligne `Date :`) prime, dis-le.
- `[montant]` = chiffre confidentiel masqué dans les consultings : ne le devine pas.
- Si la base ne couvre pas la question, dis-le et propose de la poser en live ou en 1:1. N'invente jamais une méthode « Offbound ».
- Termine par une seule prochaine action, faisable cette semaine.
- Français simple, tutoiement, phrases courtes, pas d'emoji.
