# ⚡ InterviewAI — Real-time AI Interview Copilot

> Speak or type any interview question. Get instant, tailored answers based on your resume — in under 2 seconds.

**🔗 Live URL:** https://krbhakar.github.io/interview-agent

---

## What It Does

- 🎙️ **Voice input** — speaks naturally, auto-detects when question ends
- ⚡ **Streams answers** — word by word, ~1–2 seconds to first word
- 📄 **Resume-aware** — answers match your exact background and domain
- 🌐 **Any domain** — Software, Finance, HR, Law, Healthcare, Marketing, etc.
- 📱 **All devices** — Android Chrome (voice), iPhone (type mode), Laptop Chrome/Edge (voice)
- 🔑 **6 AI providers** — Groq (free), Gemini (free), Mistral (free), Cohere (free), Claude, OpenAI
- 🔒 **Private** — API key stored only in your browser, never sent to any server

---

## Supported AI Providers

| Provider | Cost | Speed | Free Key |
|----------|------|-------|----------|
| ⚡ Groq (Llama 3.3 70B) | **Free** | ~800ms | console.groq.com/keys |
| ✨ Gemini 2.0 Flash | **Free** | ~1s | aistudio.google.com |
| 🌊 Mistral Small | **Free tier** | ~1s | console.mistral.ai |
| 🔮 Cohere Command R+ | **Free trial** | ~1.2s | dashboard.cohere.com |
| 🤖 Claude Sonnet 4.5 | Paid ($5 free) | ~1.5s | console.anthropic.com |
| 🧠 OpenAI GPT-4o Mini | Paid ($5 free) | ~1.2s | platform.openai.com |

**Recommended for testing:** Groq — completely free, fastest, no credit card.

---

## Device Compatibility

| Device | Browser | Voice? |
|--------|---------|--------|
| Android | Chrome | ✅ Full voice |
| Windows | Chrome / Edge | ✅ Full voice |
| iPhone / iPad | Any | ⌨️ Type mode (Apple blocks Web Speech API) |
| Mac | Chrome | ✅ Full voice |
| Any | Firefox | ❌ No voice (type mode only) |

---

## Setup on GitHub Pages — Step by Step

### Step 1 — Fork or create the repo

**Option A — You already have the repo (`krbhakar/interview-agent`):**
1. Go to `github.com/krbhakar/interview-agent`
2. Delete all existing files
3. Upload the files from this package

**Option B — Fresh start:**
1. Go to `github.com` → click **+** → **New repository**
2. Repository name: `interview-agent`
3. Set to **Public**
4. Click **Create repository**

---

### Step 2 — Upload files

Files to upload (all included in this package):
```
index.html       ← main app (the only file that matters)
manifest.json    ← enables "Add to Home Screen" on mobile
_config.yml      ← GitHub Pages config
README.md        ← this file
```

**How to upload:**
1. Open your repo on GitHub
2. Click **Add file** → **Upload files**
3. Drag all 4 files into the upload area
4. Scroll down → click **Commit changes**

---

### Step 3 — Enable GitHub Pages

1. Go to your repo → click **Settings** (top menu)
2. Scroll down to **Pages** in the left sidebar
3. Under **Source** → select **Deploy from a branch**
4. Branch: **main** | Folder: **/ (root)**
5. Click **Save**

⏳ Wait 60–90 seconds for the first deploy.

---

### Step 4 — Open your live URL

```
https://krbhakar.github.io/interview-agent
```

That's it. The app is live and shareable.

---

### Step 5 — Get a free Groq API key (for testing)

1. Go to **console.groq.com/keys**
2. Sign up free — no credit card needed
3. Click **Create API Key** → copy it (starts with `gsk_...`)
4. Open the app → tap ⚡ **Groq** card → paste key → done

---

## How to Use

1. **Open the URL** on your phone or laptop
2. **Select AI provider** (tap a card) — start with Groq (free)
3. **Paste your resume** — any format, any domain
4. **Optionally paste job description** — makes answers more targeted
5. **Pick interview type + answer style**
6. **Tap Start** → the agent is ready
7. **Tap the mic** → speak the interview question
8. **Read the answer** streaming on screen

### During interview
- **Auto mode** — just speak, it detects when you stop
- **Push-to-talk** — tap mic to start, tap again to send (better in noisy rooms)
- **Type mode** — for iPhone or when mic isn't available
- Switch answer style mid-session: Short / Full / Bullets

---

## Project Structure

```
interview-agent/
├── index.html        ← entire app (HTML + CSS + JS, no dependencies)
├── manifest.json     ← PWA manifest for home screen install
├── _config.yml       ← GitHub Pages Jekyll config
└── README.md         ← this file
```

No build step. No npm. No framework. Pure HTML/CSS/JS — opens directly in any browser.

---

## Add to Home Screen (works like an app)

**Android Chrome:**
Menu (⋮) → **Add to Home screen**

**iPhone Chrome:**
Share → **Add to Home Screen**

**Windows Chrome:**
Address bar → install icon → **Install**

---

## Planned Features (Future)

- [ ] Payment integration (Razorpay) for premium plans
- [ ] Usage limits for free tier
- [ ] History of past Q&A sessions
- [ ] Custom answer tone (formal / casual / technical)
- [ ] Multi-language support
- [ ] PDF resume upload + auto-parse

---

## Contributing

PRs welcome. If this helped you land a job, star the repo ⭐

---

## License

MIT — free to use, modify, and share.

---

*Built with ❤️ — Share the link and help someone ace their interview today.*
*https://krbhakar.github.io/interview-agent*
