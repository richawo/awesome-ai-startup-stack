# Free Compute & Credits for AI Builders [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> Where to get GPUs, LLM API access, hosting, databases, and cloud credits for free or near-free as you bootstrap your AI startup. Updated regularly — many of these offerings change.

[← Back to main list](../README.md) · See also: [Building tools](../building.md) · [Fundraising](../fundraising.md)

---

## Why this matters

A modern AI startup can run on free tiers far longer than people realize. A founder bootstrapping an MVP can plausibly pay **$0 for compute, $0 for LLM calls, $0 for hosting, and $0 for databases** in their first 90 days using nothing but the offerings on this list. The biggest unlock for early-stage AI work isn't raising money — it's knowing which $0 tools to combine.

Caveats:

- Free tiers shift constantly. Always check current limits before designing around one.
- "Free" usually means rate-limited, slower, or weaker hardware. Fine for prototyping; painful for production.
- Some "free trials" are time-limited; persistent free tiers are gold.

---

## Contents

- [Free GPU notebooks](#free-gpu-notebooks) — for prototyping, training small models, running demos
- [Free serverless compute](#free-serverless-compute) — for deploying inference and agents
- [Free LLM API credits](#free-llm-api-credits) — to test models without spending
- [Free hosting](#free-hosting) — for landing pages and full-stack apps
- [Free databases](#free-databases) — Postgres, Redis, vector DBs
- [Free analytics & infra](#free-analytics--infra) — events, errors, logs, queues
- [Startup credit programs](#startup-credit-programs) — bigger pots, usually require an LLC
- [Free datasets](#free-datasets) — for training, fine-tuning, evals
- [Open-model communities](#open-model-communities) — where the open weights live

---

## Free GPU notebooks

For prototyping, fine-tuning small models, and running demos. The fastest way to get a GPU under your hands without paying.

- **[Modal](https://modal.com)** — $30/month free compute credit, persistent. Python-first serverless GPU. Cold starts measured in seconds. The single best free-tier option for indie AI builders right now — better than Colab once you outgrow notebook UX.
- **[Kaggle Notebooks](https://www.kaggle.com/code)** — ~30 hours/week free P100 or T4 GPU; plus 20 hours/week of free **TPU v3-8** access. Persistent storage, dataset integration, free forever. Underrated.
- **[Google Colab](https://colab.research.google.com)** — Free T4 GPU with session limits. The most famous free GPU notebook. Colab Pro at $9.99/mo unlocks longer sessions and better hardware.
- **[Lightning AI Studios](https://lightning.ai)** — Free tier with monthly GPU credits (~22 hours/mo of T4 last we checked). Persistent VS Code-style environment, not a notebook.
- **[Hugging Face Spaces](https://huggingface.co/spaces)** — Free CPU-backed Spaces forever. **ZeroGPU** Spaces (shared A100) free for HF Pro users at $9/mo. Sometimes individual grants for ambitious projects.
- **[Saturn Cloud](https://saturncloud.io)** — Free Jupyter tier with monthly hours.
- **[Deepnote](https://deepnote.com)** — Free tier (CPU only), strong on collaboration.
- **[Paperspace Gradient (DigitalOcean)](https://www.paperspace.com/gradient)** — Has had free GPU tiers in the past; mostly paid now, but still cheap.

## Free serverless compute

For deploying models, agents, and backends without paying for idle infra.

- **[Modal](https://modal.com)** — $30/month free credit. The clear winner for AI workloads.
- **[Fly.io](https://fly.io)** — Free allotment of small VMs. Good for orchestration backends, not GPU.
- **[Cloudflare Workers](https://workers.cloudflare.com)** — 100k requests/day free. Edge runtime, no cold start.
- **[Vercel](https://vercel.com)** — Generous free Hobby tier: serverless functions, edge middleware, static hosting.
- **[Render](https://render.com)** — Free tier for web services (sleeps on inactivity).
- **[Railway](https://railway.app)** — $5/month free trial credit (was more historically).
- **[Deno Deploy](https://deno.com/deploy)** — Free tier for edge functions.
- **[Replit](https://replit.com)** — Free dev environment; "always-on" requires Core ($25/mo).
- **[GitHub Codespaces](https://github.com/features/codespaces)** — 60 hours/month free for personal accounts (more for Pro).
- **[Glitch](https://glitch.com)** — Free tier for small Node apps; good for quick demos.

## Free LLM API credits

Use these to A/B test models before committing to a vendor.

- **[Groq](https://groq.com)** — Free API tier with rate limits. Llama, Mixtral, Whisper at extreme speed (LPU hardware).
- **[Cerebras](https://cerebras.ai/inference)** — Free tier with very fast Llama inference (sometimes the fastest hosted Llama anywhere).
- **[Google AI Studio](https://aistudio.google.com)** — Generous free tier for Gemini API. Rate-limited per minute and per day.
- **[Together AI](https://www.together.ai)** — Signup credit + a few persistently-free open models.
- **[OpenRouter](https://openrouter.ai)** — Some open models are free (rate-limited). Single API across all providers.
- **[Hugging Face Inference API](https://huggingface.co/docs/api-inference)** — Free serverless inference for thousands of open models, rate-limited.
- **[Mistral Le Plateforme](https://console.mistral.ai)** — Free tier for evaluation.
- **[Cohere](https://cohere.com)** — Trial keys with limits.
- **[Anthropic Console](https://console.anthropic.com)** — Small initial free credit on signup. Pro/Max Claude.ai subscriptions don't include API access.
- **[OpenAI](https://platform.openai.com)** — Small initial credit on signup, then pay-as-you-go.
- **[Replicate](https://replicate.com)** — A small free credit on signup; pay-per-call afterwards.
- **[xAI](https://x.ai)** — Promotional credits available historically.

## Free hosting

For landing pages, marketing sites, full-stack apps.

- **[Vercel](https://vercel.com)** — Free Hobby tier. Best for Next.js, but supports any framework.
- **[Netlify](https://netlify.com)** — Free tier with generous build minutes and bandwidth.
- **[Cloudflare Pages](https://pages.cloudflare.com)** — Free, no bandwidth limits. Combine with Workers for full-stack.
- **[GitHub Pages](https://pages.github.com)** — Free static hosting from any repo.
- **[Render](https://render.com)** — Free tier for web services, static sites, databases.
- **[Fly.io](https://fly.io)** — Free tier for small apps + Postgres.
- **[Surge](https://surge.sh)** — Free static hosting deployed from a CLI in seconds.
- **[Cloudflare R2](https://developers.cloudflare.com/r2/)** — 10GB free storage, no egress fees. The cheapest place to host model weights or large media.

## Free databases

- **[Supabase](https://supabase.com)** — Free tier: 500MB Postgres, 1GB file storage, 2GB bandwidth, Auth, real-time. The default free tier for prototypes.
- **[Neon](https://neon.tech)** — Free Postgres with branching: 0.5GB storage, autoscaling.
- **[Turso](https://turso.tech)** — Free tier: 9GB storage, 1B row reads/mo. Edge-distributed SQLite.
- **[Convex](https://www.convex.dev)** — Generous free tier with reactive queries.
- **[MongoDB Atlas M0](https://www.mongodb.com/atlas)** — Free 512MB cluster forever.
- **[Firebase (Spark plan)](https://firebase.google.com/pricing)** — Free tier with Firestore, Auth, Functions.
- **[Cloudflare D1](https://developers.cloudflare.com/d1/)** — Free tier: 5GB storage, 5M reads/day.
- **[Upstash](https://upstash.com)** — Free tier for serverless Redis + Kafka + Vector.
- **[Xata](https://xata.io)** — Free tier with full-text search built in.
- **[Pinecone](https://pinecone.io)** — Free Starter tier for vector DB.
- **[Qdrant Cloud](https://cloud.qdrant.io)** — 1GB free vector DB.
- **[Chroma Cloud](https://www.trychroma.com)** — Free tier for hosted Chroma.

## Free analytics & infra

- **[PostHog](https://posthog.com)** — 1M free events/month, includes session replay + flags.
- **[Plausible](https://plausible.io)** — Self-hostable free; cloud is paid.
- **[Sentry](https://sentry.io)** — Free tier: 5k errors/mo.
- **[Better Stack](https://betterstack.com)** — Free uptime + log tier.
- **[Resend](https://resend.com)** — 3k emails/mo free, then $20/mo for 50k.
- **[Loops](https://loops.so)** — 1k contacts free.
- **[Hookdeck](https://hookdeck.com)** — Free webhook reliability tier.

## Startup credit programs

Bigger pots — usually require an LLC, a pitch, an accelerator affiliation, or a referral. Worth applying.

- **[AWS Activate](https://aws.amazon.com/activate/)** — $1k–$100k AWS credits depending on tier (Builders, Founders, Portfolio, Accelerator).
- **[Google for Startups Cloud Program](https://cloud.google.com/startup)** — Up to $200k in GCP credits over 2 years.
- **[Microsoft for Startups (Founders Hub)](https://www.microsoft.com/en-us/startups)** — Up to $150k in Azure credits + free OpenAI access.
- **[NVIDIA Inception](https://www.nvidia.com/en-us/startups/)** — GPU credits, hardware discounts, DGX Cloud access.
- **[Anthropic Startups](https://www.anthropic.com/news/announcing-our-startups-program)** — Claude API credits (varies by stage).
- **[OpenAI Converge / Startups](https://openai.com/for-startups)** — Credits + program access via select accelerators (YC, Neo, etc.).
- **[Mistral AI for Startups](https://mistral.ai/news/mistral-ai-for-startups)** — Credits + technical support.
- **[Hugging Face Startups](https://huggingface.co/startups)** — Inference API + Spaces credits.
- **[MongoDB for Startups](https://www.mongodb.com/startups)** — $5k Atlas credit.
- **[Stripe Atlas](https://stripe.com/atlas)** — Bundled credits for Notion, AWS, Mercury, Carta, Mixpanel, Segment, Linear, etc.
- **[Notion for Startups](https://www.notion.so/startups)** — 6 months free Plus plan + AI credits (typically up to $6k).
- **[Linear for Startups](https://linear.app/startups)** — 6 months free.
- **[GitHub for Startups](https://github.com/enterprise/startups)** — Discounts on GitHub Enterprise.
- **[Vercel for Startups](https://vercel.com/startups)** — Credits via partner accelerators.
- **[Pinecone for Startups](https://pinecone.io)** — Free Starter; growth program for funded startups.
- **[Supabase for Startups](https://supabase.com/startups)** — Credits for VC-backed teams.
- **[Brex Startups](https://www.brex.com/startups)** — Cards + credit packages bundled with banking.
- **[Mercury Raise](https://mercury.com/raise)** — Banking + community + warm investor intros.
- **[Y Combinator Deals](https://www.ycombinator.com/deals)** — Massive discount list available to YC alumni.
- **[On Deck Founder Fellowship](https://www.beondeck.com)** — Some perks bundled with fellowships.

## Free datasets

For training, fine-tuning, evals, and prototyping AI features.

- **[Hugging Face Datasets](https://huggingface.co/datasets)** — Tens of thousands of open datasets, with built-in streaming.
- **[Kaggle Datasets](https://www.kaggle.com/datasets)** — 250k+ public datasets, often paired with notebooks.
- **[Common Crawl](https://commoncrawl.org)** — Petabytes of web crawl data. Used to train every major LLM.
- **[The Pile (EleutherAI)](https://pile.eleuther.ai)** — 825GB curated text dataset (research use).
- **[LAION](https://laion.ai)** — Open image-text datasets.
- **[Papers With Code Datasets](https://paperswithcode.com/datasets)** — Papers + datasets cross-linked.
- **[OpenML](https://www.openml.org)** — Open ML datasets and benchmarks.
- **[Awesome Public Datasets](https://github.com/awesomedata/awesome-public-datasets)** — Comprehensive index across every domain.
- **[Data.gov](https://data.gov)** — US government open data (well-tagged).
- **[Google Dataset Search](https://datasetsearch.research.google.com)** — Google's metadata index across the open web.

## Open-model communities

The free models, weights, and tooling to use them locally.

- **[Hugging Face Hub](https://huggingface.co)** — The default for open weights. Llama, Mistral, Qwen, DeepSeek, Phi, Gemma, etc.
- **[Ollama](https://ollama.com)** — Run open models locally. One command to pull and run.
- **[LM Studio](https://lmstudio.ai)** — GUI for running local models. Easier than Ollama for non-CLI users.
- **[Replicate](https://replicate.com)** — Open models via API; pay-per-call but cheap.
- **[Together AI](https://www.together.ai)** — Hosted open models with free credits.
- **[r/LocalLLaMA](https://www.reddit.com/r/LocalLLaMA/)** — The most active community for local LLM enthusiasts.
- **[EleutherAI](https://www.eleuther.ai)** — Open-source ML research community + Discord.
- **[Open WebUI](https://github.com/open-webui/open-webui)** — Self-hosted ChatGPT-like UI for local models.

---

## How to actually stack these

A real bootstrapped AI startup runs on a stack like:

- **Compute:** Modal ($30/mo free) for inference + Kaggle for training notebooks
- **LLM calls:** Groq + Together (free tiers) for prototyping; Anthropic / OpenAI signup credits to validate quality
- **Hosting:** Vercel (free Hobby) for the frontend + Cloudflare Workers (100k req/day) for edge logic
- **Database:** Supabase (free Postgres + Auth) + Upstash (free Redis)
- **Vector DB:** Pinecone Starter or pgvector inside Supabase
- **Analytics:** PostHog (1M events/mo) for everything (events, replay, flags)
- **Email:** Resend (3k emails/mo)
- **Errors:** Sentry (5k errors/mo)

Once you incorporate, layer on top:

- AWS Activate ($5k+) or GCP Startup ($2k+) credits
- Notion for Startups ($6k+ in credits)
- NVIDIA Inception (GPU access + discounts)
- Stripe Atlas (bundled credits for ~$30k of services)

That's typically enough to get a real B2B or consumer AI product to its first 1,000 users without spending more than a few hundred dollars on infra.
