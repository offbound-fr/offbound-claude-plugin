# Privacy Policy / Politique de confidentialité : Offbound plugin for Claude

Last updated / Dernière mise à jour : 2026-11-19

## English

**Controller.** Offbound Kft. Contact: valentin@offbound.fr

**What the plugin does.** It gives Claude read-only access to the Offbound knowledge base (courses, live workshops, coaching sessions), reserved to Offbound members. Access requires a personal token issued by Offbound.

**Data processed.**
- *Your access token.* Entered in Claude Code and stored in your system's secure credential store. It is sent to the Offbound server with each search to check your access. The server stores only a hash of the token.
- *Your searches.* When Claude queries the knowledge base, it sends the search text (a few words written by Claude from your question) to the Offbound server, only to retrieve relevant passages.
- *Not received.* Your full Claude conversation, your files and your other tools are not sent to Offbound by this plugin.

**Service providers.** Cloudflare Workers (server), OpenRouter (turns the search text into an embedding, OpenAI text-embedding-3-small model), Supabase (knowledge base hosting). They process data on Offbound's behalf under their own terms.

**Retention.** The server code does not store the text of searches in the database. Cloudflare may keep short-lived technical request logs.

**Your rights.** Access, correction, deletion, or revoking your token: valentin@offbound.fr. You may also contact your data protection authority.

## Français

**Responsable.** Offbound Kft. Contact : valentin@offbound.fr

**Ce que fait le plugin.** Il donne à Claude un accès en lecture seule à la base de connaissance Offbound (cours, workshops, consultings), réservée aux membres d'Offbound. L'accès demande un jeton personnel délivré par Offbound.

**Données traitées.**
- *Ton jeton.* Saisi dans Claude Code et rangé dans le trousseau sécurisé de ton ordinateur. Il est envoyé au serveur Offbound à chaque recherche pour vérifier tes droits. Le serveur n'en garde qu'une empreinte (hachage).
- *Tes recherches.* Quand Claude interroge la base, il envoie le texte de la recherche (quelques mots rédigés par Claude à partir de ta question), uniquement pour trouver les passages utiles.
- *Ce que nous ne recevons pas.* Ta conversation complète avec Claude, tes fichiers et tes autres outils ne sont pas envoyés à Offbound par ce plugin.

**Prestataires.** Cloudflare Workers (serveur), OpenRouter (transforme le texte de la recherche en vecteur, modèle text-embedding-3-small d'OpenAI), Supabase (hébergement de la base). Ils traitent les données pour le compte d'Offbound, selon leurs propres conditions.

**Conservation.** Le code du serveur n'enregistre pas le texte des recherches en base. Cloudflare peut garder des journaux techniques de courte durée.

**Tes droits.** Accès, rectification, suppression ou révocation de ton jeton : valentin@offbound.fr. Tu peux aussi saisir l'autorité de protection des données de ton pays.
