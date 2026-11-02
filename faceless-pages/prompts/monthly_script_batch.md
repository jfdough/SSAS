# Monthly script batch (paste into ChatGPT — no Claude usage)

1. Open a new ChatGPT chat.
2. Attach (or paste) the character's `character.md` and the last month's `scripts.json`.
3. Paste the prompt below. Change `[CHARACTER]` and the starting id number.
4. Save the output as `scripts-YYYY-MM.json` in that character's folder.

---

```
You are the head writer for an Instagram/TikTok page starring [CHARACTER], an AI-generated character described in the attached character sheet. Stay 100% in his voice, backstory, and recurring details. Never break character, never use internet slang, never mention AI, followers, or "this page."

Write 60 NEW short video scripts. Do not reuse any hook, story, or core lesson from the attached past scripts.

Rules for every script:
- 70–100 spoken words (25–40 seconds at his speaking pace).
- Line 1 is the hook: a specific, curiosity-driven claim or story opener that makes a scroller stop. Use numbers, a specific memory, or a contrarian statement. No questions like "Have you ever...?"
- Middle: ONE concrete story or image from his life (a person, a place, a day), then the lesson.
- End: a short, punchy line that lands the lesson. Optionally one of his sign-offs.
- Short sentences. Written to be spoken aloud. No emojis, no hashtags, no stage directions inside the script.
- Spread across his themes evenly. Include 5 heavier emotional scripts (grief, regret, family) and 10 practical-life ones (money, work, relationships).

For each script also write:
- "hook": the on-screen text for the first 2 seconds (max 9 words).
- "caption": one short line + max 1 emoji. No hashtags.
- "theme": one or two words.

Before writing, brainstorm 100 hooks silently, then keep only the 60 strongest.

Output ONLY a valid JSON array, no commentary, in exactly this format:
[
  {"id": "[prefix]-[number, starting at NNN]", "theme": "...", "hook": "...", "script": "...", "caption": "..."}
]
```

Id prefixes: Walt = `walt`, Pops = `pops`. First batch after the starter set starts at `021`.
