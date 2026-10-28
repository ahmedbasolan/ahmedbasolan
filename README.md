# Ahmed Basolan

**Applied AI & automation engineer in Dubai, UAE.** I build LLM-powered tools for real industries (insurance, real estate, customs, finance) and ship them as working products: web apps, mobile apps, and production automations.

## Featured work

| Project | What it is | Highlights |
|---|---|---|
| [motor-claims-triage](https://github.com/ahmedbasolan/motor-claims-triage) | Claims triage and decision-support copilot for UAE motor insurance | Coverage, complexity and fraud rules engine · 105 tests, CI with ruff + mypy · calibration harness that measures which thresholds actually change decisions |
| [dubai-property-bot](https://github.com/ahmedbasolan/dubai-property-bot) | Investment scoring and Q&A for Dubai real estate ([live demo](https://dubai-property-bot.vercel.app)) | Built on 47,677 real Dubai Land Department sales and rent records · routes questions to DuckDB (numbers) or ChromaDB (market reports) · 4-factor community scoring · 95-question eval with ground truth computed from the data: retrieval and the no-LLM answers both 95/95, held there by CI · Next.js + FastAPI |
| [devrag](https://github.com/ahmedbasolan/devrag) | Ask questions about any Python codebase | Hybrid retrieval (BM25 + embeddings + reciprocal rank fusion) · AST-based chunking · code-first ranking, tests kept out of the index · Hit@5 0.93 on two held-out repos it wasn't built against |
| [Sift](https://github.com/ahmedbasolan/Sift) | Due-diligence copilot for financial documents | Risk findings, metrics and summaries with source citations · hybrid RAG over PDF, DOCX, PPTX, XLSX |
| [customs-copilot](https://github.com/ahmedbasolan/customs-copilot) | Pre-fills Dubai customs declarations from shipping documents | Vision-LLM extraction (GPT-4o, Claude, Gemini, or local Ollama) · block/warn validation rules · 87 tests |
| [ai-automation-portfolio](https://github.com/ahmedbasolan/ai-automation-portfolio) | 7 n8n workflows built for clients | Voice agent for clinic bookings · lead-gen agent with tool calling · AI ad and video generation pipelines |
| [Sakina](https://github.com/ahmedbasolan/Sakina) | Offline-first mood-based Qur'an and Sunnah app ([App Store](https://apps.apple.com/app/id6801511292)) | React Native + Expo · SQLite · Supabase sync · RevenueCat subscriptions |
| [Fasih](https://github.com/ahmedbasolan/Fasih) | Gulf Arabic learning app built around role-play scenarios | Branching NPC dialogues · spaced repetition · Expo + Supabase |

## Stack

**AI:** RAG (BM25, ChromaDB, sentence-transformers, rank fusion) · OpenAI, Anthropic, Gemini, Groq · vision extraction · LLM evaluation · n8n agents
**Backend & data:** Python, FastAPI, DuckDB, SQLite, PostgreSQL / Supabase
**Frontend & mobile:** TypeScript, Next.js, React Native / Expo, Streamlit
**Delivery:** Docker, GitHub Actions, pytest

## Contact

[LinkedIn](https://linkedin.com/in/ahmed-basolan-80364025a)
