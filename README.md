### hey, I'm sheikh

I build full-stack projects end to end: frontend, backend, and the database schema in between.

**What I'm building right now:**

- a watchlist platform that ranks what you've watched by pairwise comparison instead of star ratings. Every title is binary-inserted into an ordered list by asking "which did you like more?", and the 0-10 Score is read off the finished position rather than typed in. Along with that sits a watchlist, TMDB search, a viewing diary, Letterboxd import, and recommendations from an embedding model that runs locally. This is the one I'm focusing on as of now.
- a content dashboard for an Instagram archive. A Python/FastAPI backend generates a weekly schedule of post subjects with a single LLM call, fact-checks anything time-sensitive against real search results before it's saved, and matches each post to a song from a pool of iTunes-verified tracks. A "post studio" pipeline then turns a picked post into a publishable carousel: multi-source image search, an upscale + smart crop pass, an AI caption, and a push to post, all driven from a clean dashboard.
- the frontend for a sports prediction system: NBA|WNBA, NFL, Soccer and MLB game picks from XGBoost/LightGBM models (current accuracy consistently dropping for all models through champion selection process), player-prop distributions, and live data, with picks also delivered through a social bot.

I've also built a couple of smaller projects for myself or others: a [zero-knowledge password and secure note manager](https://github.com/sheikhmshadid/MasterPass) with client-side AES-256-GCM encryption, and an [AI-assisted nutrition and fitness tracker](https://github.com/sheikhmshadid/aiNutritionTracker) that turns a plain-English meal description into calorie and macro estimates. There are a few smaller tools scattered around too.
