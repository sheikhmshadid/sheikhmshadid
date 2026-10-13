### hey, I'm sheikh

I build full-stack projects end to end: frontend, backend, and the database schema in between.

**What I'm building right now:**

- **Cieve**, a watchlist platform that ranks what you've watched by pairwise comparison instead of star ratings. New titles are binary-inserted into an ordered list by asking "which did you like more?", and the 0-10 Score is read off the finished position. I built the recommender end to end: it embeds every title's synopsis with a small BGE model that runs inside the API itself, so there's no paid call per request, and scores TMDB candidates against your taste. Plain similarity just returns ten near-clones of your favorite, so the list is reranked with maximal marginal relevance to cover more of what you like, and if the local model comes back empty it falls through to Gemini and then TMDB trending, so the page degrades instead of erroring. Around it sits a Node/React app on Postgres with Redis rate limiting that fails open, Letterboxd import, and a Dockerized VPS deploy behind Caddy. This is the one I'm focusing on as of now.
- **A content automation platform for a social media page**: a Python/FastAPI backend that plans a week of posts with a single AI call, then checks its own work by verifying anything time-sensitive against live headlines and search results and dropping fabricated subjects before they're saved. A post studio pipeline takes it from there: it searches four image sources, has a vision model throw out off-subject and watermarked photos, upscales and smart-crops the keepers around the subject, writes the caption, and sends the finished carousel to Instagram or TikTok as a draft through the Zernio API, with media hosted on Cloudinary.

I also helped build the frontend, for both the website and the mobile app, of a sports prediction system that shows game picks and player-prop odds for the NBA, WNBA, NFL, MLB and soccer, with fantasy leagues for various sports as well. On the research side, I'm collaborating on a deep learning system that decodes neural organoid multi-electrode array recordings into classified activity patterns and is built to generalize to other labs' recordings, and I'm building a university networks project that measures how peer connectivity affects block propagation speed in a locally deployed blockchain network. Past that there's an [AI-assisted nutrition and fitness tracker](https://github.com/sheikhmshadid/aiNutritionTracker) that turns a plain-English meal description into calorie and macro estimates, plus a few smaller tools scattered around.

![Stack](https://img.shields.io/badge/Stack-0D1117?style=for-the-badge)

![Languages](https://img.shields.io/badge/Languages-24292F?style=for-the-badge)

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)

![Frameworks, libraries and cloud](https://img.shields.io/badge/Frameworks%2C%20libraries%20and%20cloud-24292F?style=for-the-badge)

![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-5FA04E?style=for-the-badge&logo=nodedotjs&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![React Native](https://img.shields.io/badge/React%20Native-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![pandas](https://img.shields.io/badge/pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3FCF8E?style=for-the-badge&logo=supabase&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![Firebase](https://img.shields.io/badge/Firebase-DD2C00?style=for-the-badge&logo=firebase&logoColor=white)

![Developer tools](https://img.shields.io/badge/Developer%20tools-24292F?style=for-the-badge)

![VS Code](https://img.shields.io/badge/VS%20Code-007ACC?style=for-the-badge&logo=visualstudiocode&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)
![Figma](https://img.shields.io/badge/Figma-F24E1E?style=for-the-badge&logo=figma&logoColor=white)
![Expo](https://img.shields.io/badge/Expo-000020?style=for-the-badge&logo=expo&logoColor=white)
![Adobe Creative Cloud](https://img.shields.io/badge/Adobe%20Creative%20Cloud-DA1F26?style=for-the-badge&logo=adobecreativecloud&logoColor=white)
