# VelvetMotion (greger)

Static Candy.ai-style AI companion demo.

## Live now

- **8 companions** from the VelvetMotion cast (Maren, Liora, Tess, Isolde, Briony, Nadine, Vesper, Calla)
- Chat with personality-specific replies + moods
- **Image generation** via [Pollinations](https://pollinations.ai) (free, no key): portrait, lingerie, **nude**, **explicit**
- **Sex video** mode (cinematic still via Pollinations, or real video if you set a video API URL)
- Gallery, create companion, discover/swipe, coins

## How to use

1. Open `index.html` or deploy this repo to Vercel / Netlify / GitHub Pages (static, no build).
2. Enter (18+).
3. Open a companion → **Generate** → pick Nude / Explicit / Sex video.
4. Settings → default is Pollinations. Optional: custom SD API or video API URL.

## Limits

- Chat is local (no live LLM). For real AI chat, wire `/api/chat` in **velvetmotion-ai** with OpenAI/OpenRouter.
- True motion sex videos need a paid video API (fal, Runway, Comfy). Paste the endpoint in Settings → Video API.

## Related repos

- `velvetmotion-ai` — best characters + Next.js app (finish chat API there)
- `velvetmotionai` — video/monetization patterns

Adult fantasy. Fictional 21+ characters only.
