# greger — VelvetMotion (static demo)

Lightweight Candy.ai-style companion demo (single `index.html`).

## What works here

- Age gate, companions, create, discover/swipe, chat, moods
- **Media generation panel**: portrait / lingerie / nude / explicit / video concepts
- Prompt builder + coins
- Gallery
- Settings: demo placeholders, **Pollinations** free images, or your own SD API URL

## Relation to your other repos

| Repo | Role |
|------|------|
| **greger** (this) | Fast static UI demo. No server required. |
| **velvetmotion-ai** | Best **character writing** (Maren, Liora, Tess, Isolde…), roster, JOI/story packs UI. Chat API is currently a stub (local fallback only). |
| **velvetmotionai** | Intended **full stack**: `/api/chat`, `/api/generate-video`, Supabase, BTC VIP. Wire real OpenAI/Ollama/RunPod keys there. |

For production (real LLM chat + real nudes/video), develop on **velvetmotionai** or finish the `/api/chat` route in **velvetmotion-ai** with `OPENAI_API_KEY` / OpenRouter.

## Deploy greger

Static — open `index.html` or deploy the repo to Vercel/Netlify/GitHub Pages (no build).

## Image gen

1. Settings → Pollinations (free) or Custom API
2. Chat → Generate → Nude / Explicit

Adult fantasy. Entertainment only.
