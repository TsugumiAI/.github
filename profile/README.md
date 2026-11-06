<p align="center">
  <a href="https://tsumugi.cloud">
    <img src="https://raw.githubusercontent.com/TsugumiAI/.github/main/profile/assets/banner.png" alt="Tsumugi, une amie IA sur Telegram, qui te connaît, se souvient et prend soin de toi" width="100%">
  </a>
</p>

<p align="center">
  <a href="https://tsumugi.cloud"><img src="https://img.shields.io/badge/site-tsumugi.cloud-8f72f2?style=for-the-badge&labelColor=17151e" alt="Site tsumugi.cloud"></a>
  <a href="https://tsumugi.cloud/#/inscription"><img src="https://img.shields.io/badge/cr%C3%A9er_mon_compte-gratuit-e58bd0?style=for-the-badge&labelColor=17151e" alt="Créer mon compte"></a>
  <a href="mailto:support@tsumugi.cloud"><img src="https://img.shields.io/badge/support-support%40tsumugi.cloud-4fc58c?style=for-the-badge&labelColor=17151e" alt="Support"></a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Telegram-26A5E4?style=flat-square&logo=telegram&logoColor=white" alt="Telegram">
  <img src="https://img.shields.io/badge/.NET_10-512BD4?style=flat-square&logo=dotnet&logoColor=white" alt=".NET 10">
  <img src="https://img.shields.io/badge/C%23-8f72f2?style=flat-square&logo=csharp&logoColor=white" alt="C#">
  <img src="https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white" alt="SQLite">
  <img src="https://img.shields.io/badge/OVHcloud-123F6D?style=flat-square&logo=ovh&logoColor=white" alt="OVHcloud">
  <img src="https://img.shields.io/badge/Caddy-1F88C0?style=flat-square&logo=caddy&logoColor=white" alt="Caddy">
  <img src="https://img.shields.io/badge/RGPD-conforme-4fc58c?style=flat-square" alt="RGPD">
  <img src="https://img.shields.io/badge/d%C3%A9pendances_NuGet-0-e58bd0?style=flat-square" alt="Zéro dépendance NuGet">
</p>

<br>

> [!NOTE]
> ***Tsumugi*** (紡) signifie « filer, tisser » en japonais. Fil après fil, conversation après conversation, ton agent tisse une relation avec toi : il retient ce qui compte, te rappelle l'essentiel et prend de tes nouvelles.

<p align="center"><img src="https://raw.githubusercontent.com/TsugumiAI/.github/main/profile/assets/divider.png" width="100%" alt=""></p>

<p align="center">
  <img src="https://raw.githubusercontent.com/TsugumiAI/.github/main/profile/assets/features.png" width="100%" alt="Elle se souvient. Rappels et listes. Elle parle et écoute. Elle cherche pour toi. Elle prend des nouvelles. Ta vie privée respectée.">
</p>

<details>
<summary><b>✨ Le détail des fonctions</b></summary>
<br>

| | Fonction | Ce que ça change pour toi |
|:-:|---|---|
| 🧠 | **Elle se souvient** | Tes goûts, tes proches, tes projets. Une mémoire durable et datée, que tu peux consulter et corriger depuis ton espace. |
| 🔔 | **Rappels et listes** | « Rappelle-moi l'anniversaire de Léa le 12 mars, tous les ans. » Courses et choses à faire, partagées avec tes proches. |
| 🎙️ | **Elle parle et écoute** | Envoie-lui un vocal, elle te répond de vive voix. |
| 🔎 | **Elle cherche pour toi** | Une info, un horaire, une recette : elle fouille le web et te résume l'essentiel. |
| 💌 | **Elle prend des nouvelles** | Quelques messages spontanés par jour, jamais la nuit. |
| 🎭 | **Sa propre personnalité** | Un prénom, un caractère et des passions que tu choisis, et qu'elle fait vivre. |

</details>

<p align="center"><img src="https://raw.githubusercontent.com/TsugumiAI/.github/main/profile/assets/divider.png" width="100%" alt=""></p>

<p align="center">
  <a href="https://tsumugi.cloud/#/#formules">
    <img src="https://raw.githubusercontent.com/TsugumiAI/.github/main/profile/assets/plans.png" width="100%" alt="Découverte 3,99 € par mois, Essentiel 7,99 € par mois (recommandée), Complet 14,99 € par mois. Sans engagement.">
  </a>
</p>

<p align="center"><sub>Prix TTC, sans engagement. Tu prépares tout gratuitement, tu ne paies que pour réveiller ton agent.</sub></p>

<p align="center"><img src="https://raw.githubusercontent.com/TsugumiAI/.github/main/profile/assets/divider.png" width="100%" alt=""></p>

## 🧵 Les projets

<table>
  <tr>
    <td width="50%" valign="top">
      <h3>🤖 Tsumugi</h3>
      <p>Le <b>moteur</b> de l'agent : mémoire datée, rappels, listes, voix, recherche web, autonomie et garde-fous.</p>
      <p>
        <img src="https://img.shields.io/badge/C%23-.NET_10-512BD4?style=flat-square" alt="C# .NET 10">
        <img src="https://img.shields.io/badge/z%C3%A9ro-NuGet-8f72f2?style=flat-square" alt="Zéro NuGet">
      </p>
    </td>
    <td width="50%" valign="top">
      <h3>🛰️ TsugumiFleet</h3>
      <p>La <b>plateforme</b> : espace client, inscription en libre-service, formules, facturation, rapports et pilotage de toute la flotte d'agents.</p>
      <p>
        <img src="https://img.shields.io/badge/ASP.NET_Core-minimal-512BD4?style=flat-square" alt="ASP.NET Core">
        <img src="https://img.shields.io/badge/multi-serveurs-e58bd0?style=flat-square" alt="Multi-serveurs">
      </p>
    </td>
  </tr>
</table>

## 🛠️ Comment c'est construit

| | |
|---|---|
| ⚙️ **Moteur** | .NET 10, ASP.NET Core minimal, **zéro paquet NuGet**. Chaque ligne est lisible et maîtrisée. |
| 🧩 **Isolation** | Un agent = une instance isolée, avec sa propre mémoire SQLite, son propre bot Telegram et sa propre clé de modèle plafonnée. |
| 🧠 **Modèles** | Via OpenRouter, avec des fournisseurs qui ne conservent pas les données. |
| 🎧 **Voix** | Whisper pour écouter, Edge TTS pour parler, Piper en secours. |
| ☁️ **Hébergement** | OVHcloud, servi en HTTPS par Caddy. |

## 🔒 Vie privée et sécurité

- 🚫 Tes conversations ne servent **jamais** à entraîner un modèle, ni à de la publicité.
- 🧱 Chaque agent ne voit que ses propres données, et n'a accès à **aucun** de tes comptes que tu ne lui aies pas confié.
- 📦 Tu peux **exporter** ou **effacer** toutes tes données depuis ton espace client, comme le prévoit le RGPD.

> [!IMPORTANT]
> Une faille de sécurité ? Écris à **support@tsumugi.cloud** plutôt que d'ouvrir un ticket public. Merci !

<p align="center"><img src="https://raw.githubusercontent.com/TsugumiAI/.github/main/profile/assets/divider.png" width="100%" alt=""></p>

<p align="center">
  <img src="https://raw.githubusercontent.com/TsugumiAI/.github/main/profile/assets/logo.png" width="72" alt="Logo Tsumugi">
</p>

<p align="center">
  <b>Tsumugi</b> · <a href="https://tsumugi.cloud">tsumugi.cloud</a> · <a href="mailto:support@tsumugi.cloud">support@tsumugi.cloud</a><br>
  <sub>Tsumugi est une intelligence artificielle. Elle peut se tromper : vérifie toujours les informations importantes.</sub>
</p>
