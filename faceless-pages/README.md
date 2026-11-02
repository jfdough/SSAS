# Faceless Character Pages — Walt & Pops

Two AI-character wisdom pages. Built to run mostly on a home laptop (RTX 5050 Laptop, 8 GB VRAM, 16 GB RAM, Windows) using tools you already pay for (ChatGPT, Claude) plus free local models. **No new subscriptions.**

| Page | Character | Audience |
|---|---|---|
| Walt | Walt Haskins, 74, retired Maine lobsterman | 30–65, blue-collar, grandpa-wisdom crowd, wellness/calm |
| Pops | Raymond "Pops" Delgado, 72, Philly boxing coach | Men 18–45, self-improvement, discipline, fathers |

## Where Claude usage goes
- **Building the system (one time):** steps 1–4 below. Moderate usage, done in pieces.
- **Running it daily:** zero Claude usage. Scripts come from ChatGPT once a month, videos render on the laptop overnight, posting runs on a timer.

## The repeatable routine (once built)

| When | What | Who / tool | Your time |
|---|---|---|---|
| Once per character | Make face (master portrait) | ChatGPT image gen — prompt in `*/character.md` | 15 min |
| Once per character | Make the 8–10 s "idle" clip from the face (breathing, blinking, mouth closed) | Local: LivePortrait (free) | automated |
| Once per character | Pick a voice | Local TTS (Chatterbox / Kokoro, free) | 15 min |
| Monthly | 60 new scripts per character | ChatGPT — `prompts/monthly_script_batch.md` | 10 min |
| Nightly (auto) | Script → voice → lip-sync onto idle clip → captions → music → 1080x1920 MP4 | Laptop (MuseTalk 1.5 / LatentSync 1.5) | 0 |
| Daily (auto) | Post to Instagram (+ TikTok, YouTube Shorts, FB Reels by hand or later auto) | Instagram Graph API (free) | 0 |
| Weekly | Look at numbers, keep what works | You | 15 min |

**Post mix per page per day (to stay light on the laptop):**
- 2 talking-head videos (lip-synced)
- 2–3 "still portrait + slow zoom + voice + captions" videos (render in seconds)

## Build status
- [x] **Step 1 — Characters:** `walt/character.md`, `pops/character.md`, 20 starter scripts each in `*/scripts.json`, monthly ChatGPT prompt
- [ ] **Step 2 — Laptop setup:** needs the laptop connected via Claude desktop app → Settings → Claude Code → Remote Control
- [ ] **Step 3 — Render pipeline:** voice → lip-sync → captions → final video
- [ ] **Step 4 — Auto-posting:** Instagram Business accounts + Meta developer app

## Ground rules
- Turn on Instagram's **"AI-generated profile"** label on both accounts (unlabeled AI characters get reach-limited since Aug 31, 2026).
- New accounts: warm up 1–2 weeks (post 1/day, engage manually) before 4–5/day.
- Never change the face. Same master image forever.
- Post the same video to Instagram, TikTok, YouTube Shorts and Facebook Reels.
- After 3 weeks, compare: views per post, follows per 1,000 views, saves + shares. Double down on the winner.
