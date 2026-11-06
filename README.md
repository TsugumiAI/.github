<div align="center">
# 紡 Tsumugi
 
**Une amie IA sur Telegram, qui te connaît, se souvient et prend soin de toi.**
 
[tsumugi.cloud](https://tsumugi.cloud) · [Formules](https://tsumugi.cloud/#/#formules) · [support@tsumugi.cloud](mailto:support@tsumugi.cloud)
 
</div>
---
 
*Tsumugi* (紡) signifie « filer, tisser » en japonais. Fil après fil, conversation après conversation, ton agent tisse une relation avec toi : il retient ce qui compte, te rappelle l'essentiel et prend de tes nouvelles.
 
## Ce que fait Tsumugi
 
| | |
|---|---|
| **Elle se souvient** | Tes goûts, tes proches, tes projets. Une mémoire durable, datée, que tu peux consulter et corriger à tout moment. |
| **Rappels et listes** | « Rappelle-moi l'anniversaire de Léa le 12 mars, tous les ans. » Courses, choses à faire, idées, partagées avec tes proches. |
| **Elle parle et écoute** | Envoie-lui un vocal, elle te répond de vive voix. |
| **Elle cherche pour toi** | Une information, un horaire, une recette : elle fouille le web et te résume l'essentiel. |
| **Elle prend des nouvelles** | Quelques messages spontanés par jour, jamais la nuit. |
| **Sa propre personnalité** | Un prénom, un caractère et des passions que tu choisis, et qu'elle fait vivre. |
 
## Les projets
 
| Dépôt | Rôle |
|---|---|
| **Tsumugi** | Le moteur de l'agent : mémoire, outils, voix, autonomie, garde-fous. C# / .NET 10, sans aucune dépendance externe. |
| **TsugumiFleet** | La plateforme : panel d'administration, espace client, inscription en libre-service, formules, facturation, rapports, multi-serveurs. |
 
## Comment c'est construit
 
- **.NET 10**, ASP.NET Core minimal, **zéro paquet NuGet**. Chaque ligne est lisible et maîtrisée.
- **Un agent = une instance isolée** (systemd), avec sa propre mémoire SQLite, son propre bot Telegram et sa propre clé de modèle plafonnée.
- **Modèles de langage** via OpenRouter, avec des fournisseurs qui ne conservent pas les données.
- **Voix** locale et gratuite : Whisper pour écouter, Edge TTS pour parler, Piper en secours.
- **Hébergé en France et au Canada** chez OVHcloud, servi en HTTPS par Caddy.
## Vie privée et sécurité
 
- Tes conversations ne servent jamais à entraîner un modèle, et ne sont ni revendues ni exploitées à des fins publicitaires.
- Chaque agent ne voit que ses propres données. Il n'a accès à aucun de tes comptes (mails, agenda…) que tu ne lui aies pas confié.
- Tu peux **exporter** toutes tes données ou **les faire effacer** depuis ton espace client, comme le prévoit le RGPD.
- Une faille de sécurité ? Écris à [support@tsumugi.cloud](mailto:support@tsumugi.cloud) plutôt que d'ouvrir un ticket public.
## Nous contacter
 
- Site : [tsumugi.cloud](https://tsumugi.cloud)
- Support : [support@tsumugi.cloud](mailto:support@tsumugi.cloud)
<div align="center"><sub>Tsumugi est une intelligence artificielle. Elle peut se tromper : vérifie toujours les informations importantes.</sub></div>
