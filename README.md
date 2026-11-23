# Offbound for Claude

Offbound coaches B2B founders (agencies, SaaS, consultants) on their offer, client acquisition and sales. This plugin brings the Offbound method into Claude: ask a business question and Claude answers from the full Offbound program (courses, live workshops, 1:1 coaching sessions), citing every source with a link to the exact moment in the video.

**Members only.** The plugin is free to install, but it needs a personal access token issued by Offbound to its members. Without a token it gives no content and tells you how to get one.

## What it includes
- `coach`: global diagnosis, finds which skill and which business type is at stake.
- 8 skills by competence: `offre` (offer and pricing), `prospection` (outbound), `setting` (LinkedIn conversations to meetings), `closing` (sales calls and objections), `contenu` (LinkedIn content and inbound), `recrutement` (hiring and team), `pilotage` (KPIs, organisation), `integration-ia` (AI in your agency).
- 7 skills by business type: AI agency, web agency, acquisition agency, content agency, B2B SaaS, e-commerce services, coach and consultant.
- A connection to the Offbound knowledge base (remote MCP server `knowledge`, read-only, HTTPS).

## Setup
1. Get your personal token from the Offbound team (members: https://www.skool.com/offbound-fr). It starts with `kk_off_`.
2. Install the plugin from the Claude plugin directory, or directly with:
   ```
   /plugin install offbound --marketplace offbound-fr/offbound-claude-plugin
   ```
   then paste your token when Claude Code asks for it. It is stored in your system's secure credential store, never in a file. To change it later: `/plugin`, choose offbound, configure.
3. Check with `/mcp` that the `knowledge` server is connected.

## Usage
Ask in plain words, for example "I run a web agency at 15k a month and don't get enough meetings, what should I do first?", or call a skill directly: `/offbound:closing`. Answers are in French, like the program.

## Privacy
Read-only access with your token. Only the search text written by Claude is sent to the Offbound server, never your whole conversation. Full policy: https://github.com/offbound-fr/offbound-claude-plugin/blob/main/PRIVACY.md

---

# Offbound pour Claude (FR)

Le plugin met la méthode Offbound dans Claude : tu poses ta question de business (offre, prospection, setting, closing, contenu LinkedIn, recrutement, pilotage, IA) et Claude répond à partir de toute la formation Offbound, sources citées avec le lien vers la vidéo au bon moment. Réservé aux membres : installation libre, mais un jeton personnel délivré par Offbound est nécessaire. Demande-le à l'équipe sur https://www.skool.com/offbound-fr, puis colle-le quand Claude Code le demande.
