# CarouselForge

**CarouselForge** is a free, 100% client-side carousel designer for creators, coaches, and founders on LinkedIn and Instagram. Paste a topic or a list of talking points, pick a two-color "press" theme, and it sets your ideas in a magazine-grade editorial type system — cover, numbered point slides, and a punchy CTA — then exports every slide as a high-resolution PNG (square 1080×1080 or portrait 1080×1350), bundled into a single `.zip` or downloaded one at a time. No signup, no backend, no watermark, no tracking.

**Live → (set on deploy)**

## How it works

1. **Write** your handle, cover hook, and one point per block in the textarea (blank line between points; first line is the slide headline, the rest is supporting copy).
2. **Forge** — slides render live on HTML canvas as you type. Pick a press theme, square or portrait format, and toggle print/registration marks.
3. **Ship** — download the whole deck as a `.zip` or grab individual slides as PNGs. Everything happens in your browser; your text never leaves your device.

### Free vs Pro
- **Free (keyless, forever):** the entire designer — type/paste your own copy, design, and export. 100% client-side.
- **Pro (bring your own key):** paste your own **GLM (z.ai)** API key and the AI drafts sharp hooks and slide copy from a single topic. The key is stored only in the page and is sent directly to the official z.ai API — never to us, never to a server.

## Affiliate disclosure

The "Get a GLM key" link ([z.ai](https://z.ai/subscribe?ic=BWTG6TRYYQ), 5% off) is a referral link — if you subscribe through it, it supports CarouselForge at no extra cost to you. The free tier works fully without any key or purchase.

## Tech

Single self-contained `index.html` — inline CSS/JS, Google Fonts (Bricolage Grotesque / Inter / Space Mono), HTML canvas rendering, and a dependency-free in-browser ZIP writer. Deploys as a static page (GitHub Pages, Cloudflare Pages, etc.).
