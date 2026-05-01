# Building [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> Tools and infrastructure to ship AI products faster — from your IDE to your inference layer.

[← Back to main list](README.md)

## Contents

- [AI Coding Assistants](#ai-coding-assistants)
- [LLM APIs & Foundation Models](#llm-apis--foundation-models)
- [LLM Frameworks & Orchestration](#llm-frameworks--orchestration)
- [Agent Frameworks](#agent-frameworks)
- [Vector Databases](#vector-databases)
- [RAG & Embeddings](#rag--embeddings)
- [Inference & Hosting](#inference--hosting)
- [Fine-tuning & Training](#fine-tuning--training)
- [Evaluation & Observability](#evaluation--observability)
- [Voice & Speech](#voice--speech)
- [Computer Vision](#computer-vision)
- [Backend Infrastructure](#backend-infrastructure)
- [Databases](#databases)
- [Auth & User Management](#auth--user-management)
- [Payments & Billing](#payments--billing)
- [Frontend Frameworks](#frontend-frameworks)
- [UI Component Libraries](#ui-component-libraries)
- [Mobile Development](#mobile-development)
- [Desktop Development](#desktop-development)
- [DevTools & CLI](#devtools--cli)
- [Hosting & Deployment](#hosting--deployment)
- [Boilerplates & Starter Kits](#boilerplates--starter-kits)

## AI Coding Assistants

- [Claude Code](https://www.anthropic.com/claude-code) — Anthropic's terminal-first agentic coder.
- [Cursor](https://cursor.com) — VS Code fork built around AI. The category leader.
- [Windsurf](https://windsurf.com) — Codeium's IDE, also forked from VS Code.
- [Zed](https://zed.dev) — Native, multiplayer editor with first-class AI.
- [GitHub Copilot](https://github.com/features/copilot) — The original AI pair programmer.
- [Cody](https://sourcegraph.com/cody) — Sourcegraph's coding assistant, strong on code search.
- [Cline](https://cline.bot) — Open-source autonomous coding agent for VS Code.
- [Aider](https://aider.chat) — Terminal-based pair programmer with git integration.
- [Continue](https://continue.dev) — Open-source Copilot alternative.
- [Tabnine](https://www.tabnine.com) — One of the original AI completion tools.
- [Codeium](https://codeium.com) — Free Copilot alternative.
- [Replit Agent](https://replit.com) — Cloud IDE + AI agent for full-stack apps.
- [Bolt.new](https://bolt.new) — Browser-based AI app builder.
- [Lovable](https://lovable.dev) — Browser-based full-stack AI builder.
- [v0](https://v0.dev) — Vercel's AI UI generator.
- [Claude Design](https://claude.ai/design/) — Anthropic Labs' visual prototyping tool that ships real HTML/CSS/JS, built on top of a design system extracted from your codebase.
- [Roo Code](https://roocode.com) — Open-source autonomous coder.

## LLM APIs & Foundation Models

- [Anthropic / Claude](https://www.anthropic.com) — Opus, Sonnet, Haiku. Strong at reasoning, writing, long context.
- [OpenAI](https://openai.com) — GPT-4o, o-series, GPT-5. The category default.
- [Google / Gemini](https://ai.google.dev) — Gemini Pro, Flash. Best free tier, huge context.
- [xAI / Grok](https://x.ai) — Grok models, integrated with X.
- [Mistral](https://mistral.ai) — French open-weight provider, Le Chat consumer app.
- [Meta / Llama](https://llama.meta.com) — Open-weight models, hosted on multiple inference providers.
- [Cohere](https://cohere.com) — Enterprise-focused, strong embeddings and rerank.
- [DeepSeek](https://deepseek.com) — Open-weight Chinese provider, strong reasoning models.
- [Qwen](https://qwen.ai) — Alibaba's open-weight family.
- [Together AI](https://www.together.ai) — Open-model inference at scale.
- [Replicate](https://replicate.com) — Run open models with one API call.
- [OpenRouter](https://openrouter.ai) — Single API to access dozens of models from one billing account.
- [Groq](https://groq.com) — Custom LPU inference at extreme speed.
- [Cerebras](https://cerebras.ai) — Wafer-scale inference, fastest hosted Llama.
- [Fireworks](https://fireworks.ai) — Fast OSS-model inference.
- [Hugging Face Inference](https://huggingface.co/inference) — Inference for any model on the Hub.

## LLM Frameworks & Orchestration

- [LangChain](https://www.langchain.com) — The most-used LLM framework. Big, batteries-included.
- [LlamaIndex](https://www.llamaindex.ai) — RAG-first framework.
- [LangGraph](https://www.langchain.com/langgraph) — Stateful agent graphs from the LangChain team.
- [DSPy](https://dspy.ai) — Stanford's prompt-as-program framework.
- [Vercel AI SDK](https://sdk.vercel.ai) — TypeScript-first SDK for streaming + tool use.
- [Mastra](https://mastra.ai) — TypeScript framework for agents and workflows.
- [Semantic Kernel](https://learn.microsoft.com/en-us/semantic-kernel/) — Microsoft's LLM framework.
- [Haystack](https://haystack.deepset.ai) — Production-grade NLP / LLM pipelines.
- [BAML](https://www.boundaryml.com) — Programming language for LLM functions.
- [Guidance](https://github.com/guidance-ai/guidance) — Constrained generation framework.

## Agent Frameworks

- [Claude Agent SDK](https://docs.anthropic.com) — Anthropic's first-party agent SDK.
- [OpenAI Agents SDK](https://openai.github.io/openai-agents-python/) — OpenAI's official agent framework.
- [LangGraph](https://www.langchain.com/langgraph) — Stateful agent orchestration.
- [CrewAI](https://www.crewai.com) — Multi-agent orchestration.
- [AutoGen](https://microsoft.github.io/autogen/) — Microsoft's multi-agent framework.
- [Pydantic AI](https://ai.pydantic.dev) — Python-typed agent framework.
- [Mastra](https://mastra.ai) — TypeScript agent framework.
- [SmolAgents](https://huggingface.co/blog/smolagents) — Hugging Face's lightweight agent framework.
- [Vercel AI SDK Agents](https://sdk.vercel.ai) — TS-first agent primitives.
- [LangFlow](https://www.langflow.org) — Visual builder for agent workflows.
- [Flowise](https://flowiseai.com) — Open-source visual LLM builder.

## Vector Databases

- [Pinecone](https://pinecone.io) — Hosted vector DB, the category default for production.
- [Weaviate](https://weaviate.io) — Open-source vector DB with built-in modules.
- [Qdrant](https://qdrant.tech) — Open-source, written in Rust. Self-hostable.
- [Chroma](https://www.trychroma.com) — Lightweight, open-source, popular for prototypes.
- [Milvus](https://milvus.io) — Open-source vector DB at scale.
- [pgvector](https://github.com/pgvector/pgvector) — Vector extension for Postgres. Often the right answer.
- [Turbopuffer](https://turbopuffer.com) — Serverless vector search on object storage.
- [LanceDB](https://lancedb.com) — Embedded vector DB built on Lance.
- [Vespa](https://vespa.ai) — Yahoo's open-source search/vector engine at scale.
- [Vald](https://vald.vdaas.org) — Cloud-native vector search.
- [Marqo](https://www.marqo.ai) — End-to-end search with built-in embeddings.

## RAG & Embeddings

- [OpenAI embeddings](https://platform.openai.com/docs/guides/embeddings) — `text-embedding-3` family.
- [Cohere embeddings](https://cohere.com/embed) — Enterprise-focused embeddings + rerank.
- [Voyage AI](https://www.voyageai.com) — Specialized embedding models, often best-in-class on benchmarks.
- [Nomic](https://nomic.ai) — Open-weight embeddings + Atlas viz.
- [BGE / BAAI](https://huggingface.co/BAAI) — Top open-weight embeddings.
- [Jina](https://jina.ai) — Multimodal embeddings.
- [LlamaIndex](https://www.llamaindex.ai) — End-to-end RAG framework.
- [Haystack](https://haystack.deepset.ai) — Open RAG pipelines.
- [Ragas](https://docs.ragas.io) — RAG evaluation framework.
- [LlamaParse](https://www.llamaindex.ai/llamaparse) — PDF parser tuned for RAG.
- [Unstructured](https://unstructured.io) — Document parsing for retrieval.
- [Reducto](https://reducto.ai) — High-accuracy document parsing.

## Inference & Hosting

- [Replicate](https://replicate.com) — One-line model hosting + API.
- [Together AI](https://www.together.ai) — OSS-model inference, fast.
- [Fireworks](https://fireworks.ai) — Fast OSS-model inference, fine-tuning included.
- [Modal](https://modal.com) — Python-first serverless GPU runtime. **$30/month free compute credit** makes it the best free-tier option for indie AI builders.
- [Beam](https://www.beam.cloud) — Serverless GPU inference.
- [Anyscale](https://www.anyscale.com) — Ray-based scalable AI compute.
- [Baseten](https://www.baseten.co) — Model deployment platform.
- [Hugging Face Inference](https://huggingface.co/inference-endpoints) — Click-to-deploy any model on the Hub.
- [Banana](https://www.banana.dev) — Serverless GPU inference.
- [Runpod](https://runpod.io) — Cheap on-demand GPU instances.
- [Groq](https://groq.com) — LPU inference, extreme speed.
- [Cerebras](https://cerebras.ai) — Wafer-scale inference.
- [SambaNova](https://sambanova.ai) — Specialized AI hardware + inference.
- [Inferless](https://inferless.com) — Serverless model hosting with cold-start optimization.

## Fine-tuning & Training

- [OpenAI Fine-tuning](https://platform.openai.com/docs/guides/fine-tuning) — Fine-tune GPT models.
- [Anthropic Fine-tuning](https://www.anthropic.com) — Available for select customers.
- [Together Fine-tuning](https://docs.together.ai/docs/fine-tuning-overview) — Fine-tune OSS models on demand.
- [Hugging Face AutoTrain](https://huggingface.co/autotrain) — Click-to-fine-tune.
- [Predibase](https://predibase.com) — Fine-tune + serve with LoRAs.
- [Modal Fine-tuning](https://modal.com) — Custom training pipelines on serverless GPUs.
- [Replicate Training](https://replicate.com/train) — Fine-tune image and language models.
- [Axolotl](https://axolotl.ai) — Open-source fine-tuning toolkit.
- [unsloth](https://github.com/unslothai/unsloth) — Fast, memory-efficient fine-tuning.
- [TRL](https://huggingface.co/docs/trl) — Hugging Face's RLHF / SFT library.
- [Hugging Face Jobs](https://huggingface.co/docs/jobs) — Run training as managed jobs.

## Evaluation & Observability

- [LangSmith](https://www.langchain.com/langsmith) — LangChain's eval + tracing platform.
- [LangFuse](https://langfuse.com) — Open-source LLM observability.
- [Helicone](https://helicone.ai) — Drop-in proxy for LLM observability.
- [Phoenix (Arize)](https://phoenix.arize.com) — Open-source LLM tracing + evals.
- [Braintrust](https://braintrust.dev) — Eval-first LLM platform.
- [PromptLayer](https://promptlayer.com) — Prompt versioning + observability.
- [Weights & Biases](https://wandb.ai) — Experiment tracking, also for LLM workflows.
- [Galileo](https://www.galileo.ai) — Eval-driven LLM development.
- [Patronus](https://patronus.ai) — Automated evals for production LLMs.
- [Confident AI](https://www.confident-ai.com) — Open-source DeepEval framework.
- [Comet Opik](https://www.comet.com/site/products/opik/) — Open-source LLM evaluation.

## Voice & Speech

- [Whisper (OpenAI)](https://github.com/openai/whisper) — Open-source ASR. Foundation for most.
- [Deepgram](https://deepgram.com) — Real-time and batch ASR API.
- [AssemblyAI](https://www.assemblyai.com) — ASR + speech intelligence.
- [ElevenLabs](https://elevenlabs.io) — Best-in-class TTS and voice cloning.
- [Cartesia](https://cartesia.ai) — Low-latency TTS for real-time apps.
- [Play.HT](https://play.ht) — TTS with strong voice library.
- [Resemble](https://www.resemble.ai) — Voice cloning + TTS.
- [Hume](https://www.hume.ai) — Empathic voice AI.
- [Sesame](https://www.sesame.com) — Conversational voice AI.
- [Azure Speech](https://azure.microsoft.com/en-us/products/ai-services/ai-speech) — Microsoft's enterprise speech stack.
- [Google Speech-to-Text](https://cloud.google.com/speech-to-text) — Google's ASR.
- [Sieve](https://www.sievedata.com) — End-to-end audio/video processing API.
- [LiveKit](https://livekit.io) — Real-time audio/video infrastructure.
- [Daily](https://www.daily.co) — Real-time audio/video API.

## Computer Vision

- [OpenAI Vision](https://platform.openai.com/docs/guides/vision) — Vision in GPT-4o.
- [Anthropic Vision](https://docs.anthropic.com) — Vision in Claude.
- [Google Gemini Vision](https://ai.google.dev) — Strong on long-form video understanding.
- [Roboflow](https://roboflow.com) — End-to-end computer vision platform.
- [Ultralytics (YOLO)](https://www.ultralytics.com) — Object detection, the open-source workhorse.
- [Replicate (vision models)](https://replicate.com) — Run SAM, BLIP, CLIP, etc. via API.
- [Segment Anything (Meta)](https://segment-anything.com) — Open-source segmentation.
- [Modal](https://modal.com) — Serverless GPU for custom CV workloads.

## Backend Infrastructure

- [Vercel](https://vercel.com) — Frontend hosting + serverless. Made for Next.js.
- [Railway](https://railway.app) — Heroku for the modern era.
- [Render](https://render.com) — Heroku alternative with cleaner UX.
- [Fly.io](https://fly.io) — Apps run close to users on edge.
- [Cloudflare Workers](https://workers.cloudflare.com) — Edge compute, fast cold starts.
- [Cloudflare Pages](https://pages.cloudflare.com) — Static + serverless hosting.
- [Netlify](https://www.netlify.com) — Original Jamstack host.
- [AWS](https://aws.amazon.com) — Still the cloud incumbent.
- [GCP](https://cloud.google.com) — Strong on ML / data infra.
- [Azure](https://azure.microsoft.com) — Best for Microsoft-shop integrations.
- [DigitalOcean](https://www.digitalocean.com) — Simpler IaaS, fairer pricing.
- [Hetzner](https://www.hetzner.com) — Cheap European bare metal + cloud.
- [Linode (Akamai)](https://www.linode.com) — Reliable VPS provider.
- [Heroku](https://heroku.com) — The original PaaS, still used.

## Databases

- [Supabase](https://supabase.com) — Open-source Firebase. Postgres + auth + storage.
- [Neon](https://neon.tech) — Serverless Postgres with branching.
- [PlanetScale](https://planetscale.com) — Serverless MySQL with branching.
- [Turso](https://turso.tech) — Edge-distributed SQLite (libSQL).
- [Convex](https://www.convex.dev) — Reactive backend platform.
- [MongoDB Atlas](https://www.mongodb.com/atlas) — Hosted MongoDB.
- [PostgreSQL](https://www.postgresql.org) — The relational DB. Boring is good.
- [Cloudflare D1](https://developers.cloudflare.com/d1/) — Edge SQLite at the worker tier.
- [DynamoDB](https://aws.amazon.com/dynamodb/) — AWS's serverless NoSQL.
- [Firestore](https://firebase.google.com/products/firestore) — Google's reactive document DB.
- [Redis](https://redis.io) — In-memory cache and key-value.
- [Upstash](https://upstash.com) — Serverless Redis + Kafka.
- [Xata](https://xata.io) — Serverless DB with built-in search.
- [Tigris](https://www.tigrisdata.com) — Globally distributed object storage.
- [ClickHouse](https://clickhouse.com) — Best-in-class OLAP database.
- [DuckDB](https://duckdb.org) — In-process analytical DB.
- [MotherDuck](https://motherduck.com) — Hosted DuckDB.

## Auth & User Management

- [Clerk](https://clerk.com) — Modern auth with great DX. The current default.
- [Auth0](https://auth0.com) — Enterprise auth incumbent (Okta-owned).
- [Stytch](https://stytch.com) — Passwordless-first.
- [Supabase Auth](https://supabase.com/auth) — Free with Supabase.
- [Firebase Auth](https://firebase.google.com/products/auth) — Free with Firebase.
- [WorkOS](https://workos.com) — Enterprise SSO/SCIM as a service.
- [Kinde](https://kinde.com) — Auth + billing for SaaS.
- [Better Auth](https://www.better-auth.com) — Open-source TypeScript auth library.
- [NextAuth.js / Auth.js](https://authjs.dev) — Open-source auth for Next/Astro/SvelteKit.
- [Lucia](https://lucia-auth.com) — Light, learnable auth library.
- [Hanko](https://www.hanko.io) — Open-source passkey-first auth.

## Payments & Billing

- [Stripe](https://stripe.com) — The default. Cards, subscriptions, invoicing.
- [Polar](https://polar.sh) — Open-source merchant of record for indie SaaS.
- [Lemon Squeezy](https://www.lemonsqueezy.com) — Merchant of record, simpler tax handling.
- [Paddle](https://paddle.com) — Merchant of record competing with LS.
- [Square](https://squareup.com) — POS + online payments.
- [Chargebee](https://www.chargebee.com) — Subscription billing for scaling SaaS.
- [Recurly](https://recurly.com) — Subscription billing.
- [Orb](https://www.withorb.com) — Usage-based billing.
- [Lago](https://www.getlago.com) — Open-source billing platform.
- [Metronome](https://metronome.com) — Usage billing for AI startups (Anthropic, OpenAI use it).
- [Ramp](https://ramp.com) — Corporate cards + spend management.
- [Brex](https://www.brex.com) — Corporate cards aimed at startups.
- [Tally](https://tally.so) — Form builder that handles payments.

## Frontend Frameworks

- [Next.js](https://nextjs.org) — The React meta-framework most teams pick.
- [React](https://react.dev) — Still the dominant UI library.
- [Remix](https://remix.run) — React framework with web-fundamentals philosophy.
- [Astro](https://astro.build) — Content-focused, multi-framework friendly.
- [SvelteKit](https://kit.svelte.dev) — The Svelte meta-framework.
- [Svelte](https://svelte.dev) — Compiler-as-framework.
- [Solid](https://www.solidjs.com) — React-like API with finer-grained reactivity.
- [SolidStart](https://start.solidjs.com) — Solid meta-framework.
- [Vue](https://vuejs.org) — Approachable, ecosystem-heavy.
- [Nuxt](https://nuxt.com) — Vue meta-framework.
- [Tanstack Start](https://tanstack.com/start) — TanStack's full-stack React.
- [Qwik](https://qwik.dev) — Resumability-first framework.
- [Hono](https://hono.dev) — Edge-first web framework (mostly backend).
- [HTMX](https://htmx.org) — HTML-driven hypermedia.
- [Phoenix LiveView](https://www.phoenixframework.org) — Server-rendered reactive UIs in Elixir.

## UI Component Libraries

- [shadcn/ui](https://ui.shadcn.com) — Copy-paste components on Tailwind + Radix. The current default.
- [21st.dev](https://21st.dev) — Community-driven registry of shadcn-compatible components and AI-agent UI templates.
- [Tailwind CSS](https://tailwindcss.com) — Utility-first CSS framework.
- [Radix UI](https://www.radix-ui.com) — Accessible unstyled primitives.
- [Headless UI](https://headlessui.com) — Tailwind Labs' unstyled primitives.
- [Magic UI](https://magicui.design) — Animated shadcn-compatible components.
- [Aceternity UI](https://ui.aceternity.com) — Flashy animated components.
- [Tremor](https://www.tremor.so) — Dashboard components for React.
- [Mantine](https://mantine.dev) — Mature React component library.
- [Chakra UI](https://chakra-ui.com) — Accessible, themable React components.
- [Ant Design](https://ant.design) — Enterprise-leaning, big component set.
- [Material UI (MUI)](https://mui.com) — Material Design React.
- [Park UI](https://park-ui.com) — Ark-based components for any framework.
- [HeroUI (NextUI)](https://heroui.com) — Modern React UI.
- [Daisy UI](https://daisyui.com) — Tailwind-based component classes.
- [Origin UI](https://originui.com) — Beautiful registry components.
- [Untitled UI](https://www.untitledui.com) — Figma + React component kit.
- [Tailwind UI](https://tailwindui.com) — Official premium components from Tailwind.

## Mobile Development

- [React Native](https://reactnative.dev) — Cross-platform native, JS-based.
- [Expo](https://expo.dev) — RN dev platform; the modern default.
- [Flutter](https://flutter.dev) — Google's cross-platform UI framework.
- [Swift / SwiftUI](https://developer.apple.com/swift/) — Native iOS.
- [Kotlin Multiplatform](https://kotlinlang.org/docs/multiplatform.html) — Cross-platform business logic in Kotlin.
- [Ionic](https://ionicframework.com) — Web-tech mobile apps.
- [Capacitor](https://capacitorjs.com) — Native runtime for web apps.
- [Tauri Mobile](https://tauri.app) — Rust + web for mobile.
- [Lynx](https://lynxjs.org) — ByteDance's React-style cross-platform UI.
- [Tamagui](https://tamagui.dev) — Universal component system for RN + web.

## Desktop Development

- [Electron](https://www.electronjs.org) — Web tech to ship Mac/Windows/Linux apps.
- [Tauri](https://tauri.app) — Rust + web tech for tiny native apps.
- [Wails](https://wails.io) — Go + web tech for desktop.
- [Flutter Desktop](https://flutter.dev/desktop) — Flutter for Mac/Windows/Linux.
- [.NET MAUI](https://dotnet.microsoft.com/en-us/apps/maui) — Microsoft's cross-platform native.
- [Qt](https://www.qt.io) — Mature C++ cross-platform framework.
- [Neutralino](https://neutralino.js.org) — Lightweight web-tech alternative to Electron.

## DevTools & CLI

- [GitHub](https://github.com) — Code hosting + actions + collaboration.
- [GitLab](https://about.gitlab.com) — Self-hostable alternative.
- [Linear](https://linear.app) — Issue tracking, the developer favorite.
- [Sentry](https://sentry.io) — Error tracking, frontend + backend.
- [PostHog](https://posthog.com) — Product analytics + feature flags + replay.
- [Datadog](https://www.datadoghq.com) — Enterprise APM.
- [Grafana](https://grafana.com) — Open-source observability.
- [Better Stack](https://betterstack.com) — Logs + uptime in one.
- [LogRocket](https://logrocket.com) — Frontend session replay + monitoring.
- [Highlight](https://www.highlight.io) — Open-source session replay.
- [Bun](https://bun.sh) — Fast JS runtime + package manager.
- [pnpm](https://pnpm.io) — Disk-efficient package manager.
- [Turborepo](https://turbo.build/repo) — Monorepo build system.
- [Nx](https://nx.dev) — Polyglot monorepo build system.
- [Vite](https://vitejs.dev) — Modern frontend build tool.

## Hosting & Deployment

- [Vercel](https://vercel.com) — Frontend hosting + serverless. The default for Next.js.
- [Netlify](https://www.netlify.com) — The original Jamstack host.
- [Cloudflare Pages](https://pages.cloudflare.com) — Static + serverless hosting on Cloudflare's edge.
- [Railway](https://railway.app) — Easy backend hosting.
- [Render](https://render.com) — Heroku alternative.
- [Fly.io](https://fly.io) — Edge-deployed apps.
- [Heroku](https://heroku.com) — Still around, still works.
- [AWS Amplify](https://aws.amazon.com/amplify/) — AWS's frontend host.
- [Coolify](https://coolify.io) — Open-source self-hostable PaaS.
- [Dokku](https://dokku.com) — Open-source Heroku-style platform.
- [Caprover](https://caprover.com) — Self-hosted PaaS.
- [Github Pages](https://pages.github.com) — Free static hosting from a repo.

## Boilerplates & Starter Kits

- [Shipfast](https://shipfa.st) — Next.js SaaS starter (paid).
- [Makerkit](https://makerkit.dev) — Next.js / Remix SaaS starter.
- [Supastarter](https://supastarter.dev) — Open-source SaaS starter on Supabase.
- [SaaS Pegasus](https://www.saaspegasus.com) — Django SaaS boilerplate.
- [Open SaaS](https://opensaas.sh) — Free, open-source full-stack starter.
- [Boilermaker (Stripe)](https://github.com/stripe/stripe-billing-typescript) — Stripe-by-Stripe boilerplate.
- [Divjoy](https://divjoy.com) — Web app code generator.
- [Zerocoder](https://zerocoder.dev) — AI builder for SaaS scaffolds.
- [T3 Stack](https://create.t3.gg) — Opinionated TS-first Next.js starter.
- [Refine](https://refine.dev) — Internal-tool framework for React.
- [Tools for Humans (open SaaS bootstrap)](https://github.com/wasp-lang/open-saas) — Wasp's free open SaaS template.
