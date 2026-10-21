# System Design Atlas

An interactive, animated reference for 111 system design concepts — rate limiting, caching, sharding, consensus, deployments, observability, security and more.

**Live site:** https://abhxym.github.io/system-design-atlas/

## What's inside

- **The wall** — every concept as a live canvas animation, grouped into 16 domains. Click a tile for an analogy, how it works step by step, a real-world example, gains and costs, when to use it, pitfalls, and an interview question with what a strong answer covers.
- **Where to use what** — 10 classic systems (URL shortener, chat, payments, news feed, ride sharing, flash sale, video streaming, notifications, collaborative editor, metrics platform) built up step by step, plus a problem → concept finder.
- **Compare** — side-by-side trade-off tables (WebSockets vs SSE vs long polling, saga vs 2PC, blue-green vs canary vs rolling, and more).
- **Interview prep** — a 45-minute framework, latency numbers, 16 common prompts with follow-ups, flashcards and a reference shelf.

## Run locally

It's a single static file with no build step. Open `index.html` in a browser, or serve the folder:

```bash
python -m http.server 8000
```
