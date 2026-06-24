# KAINDLY · The Agent Atelier

A self-contained web app that helps anyone build their own personal AI **writing agent** — a ghostwriter that turns raw ideas into LinkedIn posts and long-form newsletter articles in their own voice.

Each person names their agent, answers a short interview (typing or speaking), and the app generates a finished **master prompt**, a fun shareable "agent reveal" card for LinkedIn, plus step-by-step instructions to deploy it in a Claude Project, a ChatGPT Custom GPT, or a Copilot agent.

## What's in this repo
```
index.html      ← the entire app (one file, no build step, no server)
README.md       ← this file
vercel.json     ← optional config so Vercel serves the app cleanly
```

The app is 100% static — all logic runs in the browser, nothing is sent anywhere, and answers are saved locally on each person's own device.

## Deploy (GitHub → Vercel)
1. Create a new GitHub repository and upload index.html, README.md, vercel.json.
2. Go to vercel.com, sign in with GitHub, import the repository.
3. Click Deploy. Vercel gives you a live link to share.

---
KAINDLY · *Lead AI. Don't Chase It.™*
