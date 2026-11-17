# greger — VelvetMotion

Candy.ai-style AI companion demo. Single-file HTML, client-side.

## Features

- Age gate (18+)
- 12 companions + create your own (with look description)
- Personality + mood system (soft, commanding, shy, etc.)
- Free unlimited chat with NSFW-aware replies
- **Media generation panel**: portrait, lingerie, nude, explicit, video concepts
- Prompt builder (girl look + pose + extras)
- Coins economy (generation costs 8–25 coins)
- Gallery with image/video filters
- Discover / swipe matching
- Settings: demo placeholders, Pollinations free API, or your own SD endpoint
- localStorage persistence

## Image generation

| Mode | Notes |
|------|--------|
| **Demo** | Stylized placeholders (default) |
| **Pollinations** | Free public image API — set in Settings. NSFW may be filtered by their service. |
| **Custom API** | Point at your Stable Diffusion / RunPod / ComfyUI endpoint |

Video is currently a **concept card** (no real video model wired). Plug a video API the same way if you have one.

## Local use

Open `index.html` in a browser.

## Deploy

Static site — Vercel, Netlify, or GitHub Pages. No build step.

## Notes

Chat is simulated (no LLM key required). For real conversation quality, wire an OpenAI-compatible API in a future backend version (see your other VelvetMotion repos).

Adult fantasy. Entertainment only.
