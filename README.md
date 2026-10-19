<!-- Project details and screenshots follow geraldikem.com, which is the source of truth (GeraldIkem/gerald-ikem-site, src/data/ and src/assets/projects/). The images are kept in sync by .github/workflows/sync-project-images.yml. -->
<p align="center">
  <img src="assets/header.svg" width="100%" alt="Gerald Ikem — Backend engineer. Payments now, machine learning next." />
</p>

<p align="center">
  <a href="https://geraldikem.com/"><strong>Website</strong></a> &nbsp; · &nbsp;
  <a href="https://geraldikem.com/resume/Gerald_Ikem_Resume.pdf"><strong>Résumé</strong></a> &nbsp; · &nbsp;
  <a href="https://www.linkedin.com/in/gerald-ikem-158926233/"><strong>LinkedIn</strong></a> &nbsp; · &nbsp;
  <a href="mailto:geraldikem15@gmail.com"><strong>Email me</strong></a> &nbsp; · &nbsp;
  <a href="#explore-the-projects"><strong>Explore the projects</strong></a>
</p>

**Hi, I'm Gerald Ikem; a backend engineer based in Woodbridge, near Toronto.** At **Payaza**, I build Java and Spring Boot services for payments, merchant onboarding, foreign-exchange rates, and back-office security. I also develop and maintain campaign websites for **Believer's LoveWorld**.

I'm studying part-time for a **Master of Computer Science at the University of Illinois Urbana-Champaign**, starting with Applied Machine Learning, after an **Honours BSc in Computer Science from York University**. My interests span **backend engineering, data science, and applied machine learning**. These projects bring those interests into apps people can explore and use. The full write-ups, with what was hard and how I fixed it, are on **[geraldikem.com](https://geraldikem.com/)**.

**Open to backend roles, hybrid in the GTA or remote.** I'm looking for a backend or platform role on a team that runs serious systems, at a bank, a payments company or a large enterprise, ideally one where I can grow toward ML infrastructure. Authorized to work in Canada and the United States.

## Now building

<table>
<tr>
<td width="50%" valign="top">
<a href="https://hummle.app/"><img src="assets/hummle.png" width="100%" alt="Hummle's homepage: Give every line a voice, beside a page of text with one word highlighted" /></a>
</td>
<td width="50%" valign="top">

### Hummle &nbsp; `in progress`
**Give every line a voice.**

A private read-aloud app for your own PC. Hummle will read your drafts, web pages, and long web novels aloud in expressive, consistent voices, with nothing sent to the cloud. Right now I'm proving the voice engine: every engine generates speech faster than real time on one GPU, and quality is checked by code, not by ear, for word accuracy, voice identity, and accent.

**Stack:** `Python` `audio.cpp (GGUF on Vulkan)` `whisper.cpp` `PyTorch on ROCm` `CAM++` `DeepFilterNet3` `Praat` `librosa`

**[Follow Hummle](https://hummle.app/)**

</td>
</tr>
</table>

## Explore the projects

<table>
<tr>
<td width="50%" valign="top">
<a href="https://uselinkify.com/"><img src="assets/linkify.jpg" width="100%" alt="Linkify's sharing workspace and product homepage" /></a>

### 01 / Linkify
**One place for everything you share.**

Create memorable short links, share files up to 1 GB, and bring your links together on a personal page. Add custom QR codes, set expiry dates or passcodes, and see how people discover what you've shared. The core is being rewritten in Java 21 and Spring Boot 4, with 244 tests run against real Postgres and Redis.

**Stack:** `Java 21` `Spring Boot 4.1` `Spring Security` `JPA and Flyway` `PostgreSQL 17` `Redis 7.4` `Testcontainers` `Next.js 16` `TypeScript` `Cloudflare Workers and D1` `AWS S3` `Docker` `GitHub Actions`

**[Visit Linkify](https://uselinkify.com/)**

</td>
<td width="50%" valign="top">
<a href="https://usequickread.com/"><img src="assets/quickread.jpg" width="100%" alt="QuickRead's workspace for importing documents and making study material" /></a>

### 02 / QuickRead
**Turn a long read into lasting understanding.**

Bring in documents, webpages, or recordings. Explore summaries at different depths, ask questions with references to the original text, and turn useful ideas into editable study cards and notes. Extraction, OCR, and speech transcription happen on your device, for uploads up to 1 GiB and recordings up to 4 hours.

**Stack:** `TypeScript` `React 19` `Next.js 16` `Python` `Pyodide` `Cloudflare Workers, D1, R2 and Workers AI` `Supabase Auth` `PDF.js` `Tesseract.js` `Transformers.js`

**[Open QuickRead](https://usequickread.com/)**

</td>
</tr>
<tr>
<td width="50%" valign="top">
<a href="https://threadfern.dev/demo"><img src="assets/threadfern-preview.jpg" width="100%" alt="Threadfern's public demo displaying a real saved crawl of example.com" /></a>

### 03 / Threadfern
**Follow the links. Keep the discoveries.**

Crawl a website and collect its page titles, URLs, status codes, and discovered links. Search your collections, inspect broken links, revisit previous runs, and export the results. The engine is plain Java 17 with no framework, and concurrent workers make it 2.95× faster when the server is slow. The public example lets you look around immediately.

**Stack:** `Java 17` `java.net.http` `JDBC` `PostgreSQL 17` `Docker Compose` `Node.js` `Neon` `Render` `GitHub Actions`

**[Explore the demo](https://threadfern.dev/demo)** · [Start a collection](https://threadfern.dev/)

</td>
<td width="50%" valign="top">
<a href="https://matchdayml.com/"><img src="assets/matchday.png" width="100%" alt="Matchday ML's match predictions page" /></a>

### 04 / Matchday ML
**See the game through the numbers.**

Explore Premier League, La Liga, NBA, and WNBA predictions. Every forecast is frozen at kickoff, so you can compare what the model said before a game with what actually happened. On 1,140 held-out Premier League games it picks 53.4% correctly, against 43.2% for a baseline, and 66.4% of 3,941 held-out NBA games.

**Stack:** `Python` `scikit-learn` `CatBoost` `Next.js` `React` `TypeScript` `Node.js` `SQLite` `Drizzle` `Docker` `Caddy` `Render` `GitHub Actions`

**[Matchday ML website](https://matchdayml.com/)**

</td>
</tr>
<tr>
<td width="50%" valign="top">
<a href="https://skyloom.app/"><img src="assets/skyloom-preview.jpg" width="100%" alt="Skyloom's animated sky and interactive hourly weather timeline" /></a>

### 05 / Skyloom
**Step into the forecast.**

Explore the weather with a sky that changes alongside the forecast. Move through hourly conditions, check the days ahead, inspect rain and wind charts, follow daylight and moon phases, and save places you care about. 78 tests cover the daylight-saving and midnight edge cases.

**Stack:** `React 19` `TypeScript` `Three.js` `React Three Fiber` `GLSL` `Tailwind 4` `Recharts` `Leaflet` `Zod` `Cloudflare Workers`

**[Explore Skyloom](https://skyloom.app/)**

</td>
<td width="50%" valign="top">
<a href="https://www.reelrank.dev/"><img src="assets/reelrank.jpg" width="100%" alt="ReelRank's film discovery page with favorites and movie recommendations" /></a>

### 06 / ReelRank
**Your next film starts with your favorites.**

Discover films shaped by what you like. Compare recommendation approaches, explore film details, build a watchlist, and hide titles you've watched or aren't interested in. Recommendations change as your preferences do, and run entirely in your browser. On 32 million MovieLens ratings, the EASE model beats popularity by 56.7% on NDCG@10.

**Stack:** `Python` `pandas` `NumPy` `SciPy` `scikit-learn` `JavaScript (ES modules)` `Playwright` `GitHub Actions` `Vercel`

**[Find your next film](https://www.reelrank.dev/)**

</td>
</tr>
</table>

---

<p align="center">
  <strong>Found something interesting? I'd love to hear what you think.</strong><br />
  <a href="mailto:geraldikem15@gmail.com">geraldikem15@gmail.com</a> &nbsp; · &nbsp;
  <a href="https://www.linkedin.com/in/gerald-ikem-158926233/">Connect on LinkedIn</a> &nbsp; · &nbsp;
  <a href="https://geraldikem.com/">geraldikem.com</a>
</p>
