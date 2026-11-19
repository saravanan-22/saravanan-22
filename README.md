# Hi, I'm Saravanan 👋

<a href="https://saravanan-22.github.io/"><img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=22&pause=1000&color=0891B2&width=640&lines=Full-Stack+Developer+%C2%B7+FinTech;Go+%7C+Python+%7C+React+%7C+TypeScript;Built+LendOCR%3A+an+OCR+API+for+Indian+lending;Open+to+work+%E2%80%94+on-site%2C+hybrid+or+remote" alt="Typing intro" /></a>

**Full-Stack Developer · FinTech & Digital Lending · Tiruppur, Tamil Nadu, India**

I'm a full-stack software engineer with **2+ years in FinTech**. I build a digital lending platform used by banks, NBFCs and their partner agents, covering both the React screens people use every day and the **Go** back end that stores data, applies business rules and produces reports. I also work directly with clients and with finance and operations teams.

On my own time I built **[LendOCR](https://saravanan-22.github.io/lendocr-website/)**, a production-style OCR API that reads 14 Indian KYC and loan documents into validated JSON, with GPU OCR, API keys, rate limits, background jobs, signed webhooks and monitoring.

<p>
  <a href="https://saravanan-22.github.io/"><img src="https://img.shields.io/badge/Portfolio-0891b2?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Portfolio" /></a>
  <a href="https://www.linkedin.com/in/saravanan-webdeveloper/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="mailto:saravanan.rv22@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
  <img src="https://img.shields.io/badge/Open_to_work-22c55e?style=for-the-badge" alt="Open to work" />
</p>

### 🚀 Core Flagship Projects

#### ⚡ [FinGrid Document & Underwriting Engine](https://github.com/saravanan-22/fingrid-doc-engine)
**Unified Document Generation, Multi-Party eSign, BSA & Credit Underwriting Platform.**
Replaces multiple third-party SaaS tools (Glib.ai, Perfios, Digio, DocuSign, Aggregators) with an in-house lending microservice:
- **Dynamic Financial Document Engine**: Print-perfect vector PDF generation for Credit Appraisal Memos (CAM), Audited P&L Statements, Sanction Letters (KFS), and Loan Closure NOCs with zero backend layout code.
- **In-House Bank Statement Analysis (BSA)**: Replaces Glib.ai with Indian banking narration regex classification, Average Monthly Balance (AMB) computation, EOD milestone tracking (5th, 10th, 15th, 20th), outward bounce radar, and un-reported loan discovery.
- **Credit Bureau Engine (CIBIL & Experian)**: Legacy 36-month DPD string decoder (`000`, `030`, `SMA`, `NPA`), CMR ranking, leverage analysis, and derogatory knockout flags.
- **Tax & GST Triangulation**: Multi-year ITR analysis, 12-month GSTR-3B Table 3.1a outward supplies & cash tax ratio, with automated 3-way reconciliation (GST vs Banking vs ITR) to catch circular trading.
- **Multi-Party eSign Pipeline**: Pluggable interface for Indian Aadhaar eSign (Digio, Leegality), Class 3 USB DSC, DocuSign, and an in-browser mock simulator with full audit trail.

`TypeScript` `Node.js` `Gotenberg` `Handlebars` `Express` `Zod` `Docker` `FinTech`

<p>
  <a href="https://github.com/saravanan-22/fingrid-doc-engine"><img src="https://img.shields.io/badge/Repository-1e3a8a?style=for-the-badge&logo=github&logoColor=white" alt="FinGrid Repository" /></a>
  <img src="https://img.shields.io/badge/Tests-29%2F29_Passing-brightgreen?style=for-the-badge" alt="Tests" />
  <img src="https://img.shields.io/badge/Status-Active_Core_Project-22c55e?style=for-the-badge" alt="Active" />
</p>

---

#### 🛡️ [TrustID — Video KYC & Anti-Deepfake Verification Service](https://github.com/saravanan-22/trustid-vkyc-service)
**Bank-grade Video KYC & Anti-Deepfake API for Digital Lending & Identity Verification (V-KYC).**
Replaces expensive IDV vendors (Jumio, Veriff, Onfido) with a high-throughput, self-hosted Computer Vision microservice:
- **1:1 Biometric Face Match**: Compares live video selfie frames against extracted ID card portraits (Aadhaar, PAN, Passport).
- **2D FFT Deepfake & Virtual Camera Detection**: Spots synthetic facial manipulation, GAN artifacts, screen replay attacks, and virtual camera injections (OBS Studio) in the spectral frequency domain.
- **Active Challenge-Response Liveness**: Randomized behavioral challenges (head yaw turns, eye blink detection, smile tracking) achieving 99.2% anti-spoof accuracy.
- **Document Tamper & Sharpness Engine**: Evaluates ID image blur, glare, and resolution, isolating ID portrait crops automatically.
- **Cryptographic Audit Dossiers**: Generates verifiable SHA-256 HMAC-signed audit certificates for RBI, FATF, and SOC2 compliance.

`Python` `FastAPI` `OpenCV` `Computer Vision` `Docker` `Biometrics` `RBI-Compliance`

<p>
  <a href="https://github.com/saravanan-22/trustid-vkyc-service"><img src="https://img.shields.io/badge/Repository-5C3EE8?style=for-the-badge&logo=github&logoColor=white" alt="TrustID Repository" /></a>
  <img src="https://img.shields.io/badge/Tests-17%20Passed-brightgreen?style=for-the-badge" alt="Tests" />
  <img src="https://img.shields.io/badge/Compliance-RBI%20%7C%20FATF-orange?style=for-the-badge" alt="Compliance" />
</p>

---

#### 🔍 LendOCR
**An OCR API for Indian KYC and loan documents.** Send a photo or PDF of a PAN, Aadhaar, bank statement, cheque, bill, ITR or salary slip and get checked, structured JSON back in about 0.2 seconds, with a flag when a person should review it.

<p>
  <a href="https://saravanan-22.github.io/lendocr-website/"><img src="https://img.shields.io/badge/Live_website-0f766e?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Live website" /></a>
  <a href="https://github.com/saravanan-22/lendocr-website"><img src="https://img.shields.io/badge/Website_code-181717?style=for-the-badge&logo=github&logoColor=white" alt="Website code" /></a>
  <a href="https://saravanan-22.github.io/#work"><img src="https://img.shields.io/badge/Case_study-d8a657?style=for-the-badge&logoColor=white" alt="Case study on my portfolio" /></a>
</p>

- **14 Indian documents** with auto type detection; digital, scanned and password-protected PDFs
- **Validation, not just OCR:** Aadhaar Verhoeff, GSTIN mod-36, passport MRZ check digits, PAN / DL / IFSC formats
- **Bank statement analysis:** salary, EMIs, cheque bounces, average balance and a row-by-row tamper check
- **Two OCR tiers:** RapidOCR on the GPU (~0.15 s per card) and PaddleOCR-VL on vLLM for hard images
- **Sold as an API:** hashed API keys with scopes, rate limits shared through Postgres, quotas, usage metering, admin API
- **Built to scale:** backpressure, batch uploads, nginx load balancer, Postgres job queue, encrypted files, signed webhooks
- **Operated like production:** Prometheus metrics, Grafana dashboard, alert rules, 160 tests in GitHub Actions

`Python` `FastAPI` `PostgreSQL` `RapidOCR` `PaddleOCR-VL` `vLLM` `Docker` `nginx` `Prometheus` `Grafana`

> The API code is in a private repository because LendOCR is a commercial product. I'm happy to walk through it in an interview.

---

### 💼 Experience

**Full Stack Developer · Inforvio Technologies** · Sep 2024 – Present · FinTech
- **650+** reviewed code changes across 3 projects · about **70,000** lines of code
- **Lender API integration:** an 8-step two-wheeler loan journey, end to end (eKYC, video KYC, eNACH, eSign, delivery OTP)
- **Automatic document reading:** AI/OCR for **15+** KYC and business document types, with flags for wrong or unclear documents
- **Loan approval (CAM) report:** tax returns, GST, credit bureau data and risk rating in one ready-to-print PDF
- **Service requests & partner payments:** approval workflows, plus automated monthly commission, invoices and GST records that replaced manual spreadsheets
- **Configurable loan journeys:** business teams change application steps and forms without a release

**Full Stack Developer Intern · itboomi innovations** · Feb 2024 – Jul 2024 · MongoDB features and SEO

---

### 🛠️ Tech stack

<p>
  <img src="https://skillicons.dev/icons?i=go,python,ts,js,react,tailwind,nodejs,express,fastapi,mysql,postgres,redis,mongodb,aws,docker,nginx,prometheus,grafana,githubactions,git&perline=10" alt="Go, Python, TypeScript, JavaScript, React, Tailwind, Node.js, Express, FastAPI, MySQL, PostgreSQL, Redis, MongoDB, AWS, Docker, nginx, Prometheus, Grafana, GitHub Actions, Git" />
</p>

| Area | Skills |
|---|---|
| **Languages** | Go (Golang) · Python · TypeScript · JavaScript · SQL · HTML / CSS |
| **Front end** | React · TypeScript · Tailwind CSS · Shadcn UI · Config-driven forms · Monorepo setup |
| **Back end** | Go Fiber · FastAPI · REST APIs · MySQL · PostgreSQL · Redis · Node.js / Express · MongoDB |
| **AI / OCR** | RapidOCR (PP-OCR) · PaddleOCR-VL · vLLM · ONNX Runtime GPU · PDF parsing · Computer Vision · OpenCV · Deepfake Detection (2D FFT) |
| **Cloud & tools** | AWS S3 · AWS SES · Docker · nginx · Prometheus / Grafana · GitHub Actions · Git · Bitbucket |
| **Integrations** | Video KYC (V-KYC) · AI / OCR document reading · PDF reports · Excel export · Credit bureau data · Lender APIs · eSign · Email & SMS APIs |
| **Lending domain** | Loan origination · Video KYC (VKYC) & liveness · KYC checks · Credit appraisal (CAM) · GST & tax return data · Collections · Partner commission & GST |

---

### 🚀 Featured

| Project | What it is | Tech | Links |
|---|---|---|---|
| ⚡ **[FinGrid Doc Engine](https://github.com/saravanan-22/fingrid-doc-engine)** | Unified dynamic document generator (CAM, P&L, NOC), multi-party eSign pipeline (Aadhaar/DSC/DocuSign), in-house BSA (replacing Glib.ai), CIBIL 36m DPD parser, and 3-way tax triangulation (GST vs Banking vs ITR). 29 tests in CI | TypeScript · Node.js · Handlebars · Gotenberg · Express · Zod · Docker | [Code & Docs](https://github.com/saravanan-22/fingrid-doc-engine) |
| 🛡️ **[TrustID Video KYC](https://github.com/saravanan-22/trustid-vkyc-service)** | Bank-grade Video KYC verification API: 1:1 biometric match, 2D FFT deepfake & virtual camera detection, active liveness challenges, and SHA-256 HMAC audit dossiers for RBI compliance. 17 tests in CI | Python · FastAPI · OpenCV · Computer Vision · Docker | [Code & Docs](https://github.com/saravanan-22/trustid-vkyc-service) |
| ⭐ **LendOCR** | OCR API for Indian KYC and loan documents: 14 document types, checksum validation, bank statement analysis, API keys and quotas, background jobs with signed webhooks, Prometheus monitoring. 160 tests in CI | Python · FastAPI · RapidOCR · PaddleOCR-VL · vLLM · PostgreSQL · Docker · nginx | [Website](https://saravanan-22.github.io/lendocr-website/) · [Site code](https://github.com/saravanan-22/lendocr-website) · API code private |
| 🌐 **[Developer Portfolio](https://github.com/saravanan-22/saravanan-22.github.io)** | My portfolio: interactive 3D background, skill-card deck, animated LendOCR case study | Next.js 16 · React 19 · TypeScript · Three.js · GSAP | [Live](https://saravanan-22.github.io/) · [Code](https://github.com/saravanan-22/saravanan-22.github.io) |

### 🧩 Earlier projects (MERN)

| Project | Description | Tech | Links |
|---|---|---|---|
| 🧠 **[MERN Quiz App](https://github.com/saravanan-22/quiz-game-mern)** | Full-stack quiz game: 10 categories, bcrypt auth, points and a demo login | React · Express · MongoDB | [Live](https://saravanan-22.github.io/quiz-game-mern/) · [Code](https://github.com/saravanan-22/quiz-game-mern) |
| 🎬 **[Movie App](https://github.com/saravanan-22/movie-discovery-react)** | Movie & TV discovery with search, genres, trailers and Firebase auth | React · TMDB API · Firebase | [Live](https://aj-react-p2-movieapp.vercel.app/) · [Code](https://github.com/saravanan-22/movie-discovery-react) |
| ❓ **[Open Question Database](https://github.com/saravanan-22/trivia-question-bank-react)** | Community trivia question bank | React · Firebase · Firestore | [Live](https://openquestionsadddatabase.netlify.app/) · [Code](https://github.com/saravanan-22/trivia-question-bank-react) |
| ✅ **[MERN Task Planner](https://github.com/saravanan-22/task-planner-mern)** | Task manager with groups and completion tracking | React · Express · MongoDB | [Code](https://github.com/saravanan-22/task-planner-mern) |
| ⚡ **[JavaScript Mini Projects](https://github.com/saravanan-22/javascript-mini-projects)** | 15 vanilla JS projects with live demos | HTML · CSS · JavaScript | [Live](https://saravanan-22.github.io/javascript-mini-projects/) · [Code](https://github.com/saravanan-22/javascript-mini-projects) |

---

### 📚 Currently learning

Go concurrency in depth · transactions & isolation levels · double-entry ledger design · event-driven architecture · outbox pattern & sagas · gRPC microservices · advanced Redis · observability · Kubernetes & IaC

---

### 📊 GitHub Stats

<p align="left">
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/stats?username=saravanan-22&theme=github_dark" height="160" alt="GitHub stats" />
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=saravanan-22&theme=github_dark" height="160" alt="Top languages" />
</p>
<p align="left">
  <img src="https://streak-stats.demolab.com/?user=saravanan-22&theme=dark&hide_border=true" alt="GitHub streak" />
</p>
