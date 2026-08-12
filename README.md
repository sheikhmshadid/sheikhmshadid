### hey, I'm Sheikh

I build full-stack side projects end to end — frontend, backend, and the database schema in between.

**What I'm building right now:**

* [**Loage**](https://github.com/sheikhmshadid/stacktracker) — a watchlist platform that ranks what you've watched by pairwise comparison instead of star ratings. Every title is binary-inserted into an ordered list by asking "which did you like more?", and the 0-10 Loage Score is read off the finished position rather than typed in. Around that sit a watchlist, TMDB search, a viewing diary, Letterboxd import, and recommendations from an embedding model that runs locally rather than a paid call per request. This is the one I'm focusing on as of now.
* [**ninetyfourohfive**](https://github.com/sheikhmshadid/ninetyfourohfive) dashboard — a content dashboard for `@ninetyfourohfive`, a football + streetwear Instagram archive. A Python/FastAPI backend generates a weekly schedule of post subjects with a single LLM call, fact-checks anything time-sensitive against real search results before it's saved, and matches each post to a song from a local pool of iTunes-verified tracks. A "post studio" pipeline then turns a picked post into a publishable carousel — multi-source image search, an upscale + smart crop pass, an AI caption, and a push to Buffer — all driven from a React + TypeScript dashboard.
* **Kirkova Sports** — the frontend for a self-hosted sports prediction system: NBA and MLB game picks from XGBoost/LightGBM models (current accuracy sits around 65% for NBA and 53% for MLB moneylines), player-prop distributions, and live data, with picks also delivered through a Discord bot and Telegram.

I've also built a couple of projects for my own use — a [zero-knowledge password and secure note manager](https://github.com/sheikhmshadid/MasterPass) with client-side AES-256-GCM encryption, and an [AI-assisted nutrition and fitness tracker](https://github.com/sheikhmshadid/aiNutritionTracker) that turns a plain-English meal description into calorie and macro estimates — along with a few smaller tools here and there.
