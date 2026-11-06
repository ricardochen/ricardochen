# Ricardo Chen

**Forward-deployed engineer — AI and computer vision for field operations.**
I build systems that get used in the real world: computer vision in supermarket aisles, voice kiosks in showrooms, and assistants with guardrails inside banks and law firms.

Ten years co-founding and running engineering at Wisy (retail execution), two years deploying into enterprise operations across Panama, Germany, Italy, Portugal, Spain and Chile. Now independent, in Panama.

### Public work

| Project | What it demonstrates | Stack |
|---|---|---|
| [amy-demo](https://github.com/ricardochen/amy-demo) · [live](https://ricardochen.github.io/amy-demo/) | Voice kiosk: speech in, retrieval over 1,357 Q&A pairs, speech out. BM25 chosen over embeddings because `torch` didn't fit a serverless budget — a deployment constraint driving the architecture. | TypeScript · Deno · Supabase · ElevenLabs |
| [kramer-demo-intake](https://github.com/ricardochen/kramer-demo-intake) · [live](https://ricardochen.github.io/kramer-demo-intake/) | Legal intake agent in English, Spanish and German. Progressive qualification, and a hard guardrail: it never gives legal advice, never quotes fees, never predicts outcomes. | TypeScript · Supabase · LLM |
| [banco-demo-credito](https://github.com/ricardochen/banco-demo-credito) · [live](https://ricardochen.github.io/banco-demo-credito/) | Internal credit assistant for bank staff. Every number comes with the rule that backs it, so the answer can be checked rather than trusted. | TypeScript · Supabase Edge Functions |

### A note on what's public

Most of my production work — Wisy's computer-vision platform, client deployments, and the POS system I built for my own restaurant — is proprietary or under NDA, so it isn't here. The repositories above are working demos built with fictional data to show the patterns: retrieval grounded in a source of truth, guardrails that refuse, and architectures chosen around deployment constraints.

### Elsewhere

- LinkedIn: [linkedin.com/in/ricardochen](https://linkedin.com/in/ricardochen)
- Panama City, Panama · Spanish / English / Cantonese
