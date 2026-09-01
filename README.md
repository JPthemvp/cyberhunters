# ⚔️ Cyber Hunters

An educational cybersecurity game built on **CSA Cyber Essentials (AI Edition)** for Singapore SMEs.

## Modes

| Mode | File | Description |
|---|---|---|
| 🏠 Hub | `index.html` | Landing page — pick Story or Tournament |
| 🗺️ Story Mode | `cyber-hunters.html` | Solo RPG — explore 5 CE pillar zones, battle virus monsters |
| 🏎️ Tournament | `cyber-racers.html` | Multiplayer kart racing with live quiz hazards |

## Play

Open `index.html` in a browser, or deploy to any static host (Vercel, Netlify, GitHub Pages).

**Live URL:** `/games` → hub landing page

## Features

- 37 multiple-choice questions across all 5 CE pillars (Assets, Secure, Update, Backup, Respond)
- Real multiplayer via Supabase Realtime (4-letter room codes, up to 150 concurrent players)
- Gacha loot system, XP/levelling, boss battles
- Mobile-friendly with touch D-pad and swipe controls
- Fully self-contained HTML — no build step required

## CE Pillars Covered

| Pillar | Zone (Story) | Topics |
|---|---|---|
| 🗂️ Assets | Asset Atoll | Social engineering, deepfakes, shadow IT, data protection |
| 🛡️ Secure & Protect | Security Sanctum | MFA, passphrases, malware, secure config, AI security |
| 🔄 Update | Patch Plains | Patch timelines, EOL software, zero-day threats |
| 💾 Backup | Backup Bastion | Offline backups, cloud SRM, ransomware recovery |
| 🚨 Respond | Response HQ | Incident response, PDPA obligations, SingCERT reporting |

## Multiplayer Capacity (Supabase Free Tier)

Broadcasts throttled to 500ms intervals (~2 updates/sec per player).  
Free tier 2M message quota supports **~110 minutes** of play with 150 participants in rooms of 4–8.

## Source

Content based on: *Cyber Essentials in Action — AI Edition*, Cyber Security Agency of Singapore (CSA).
