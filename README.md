# Muhammad Anas — Portfolio

Portfolio of Muhammad Anas, who builds AI voice and chat agents for businesses. Python developer and AI/ML engineer based in Lahore, Pakistan, with 1 year of experience and remote clients in Australia and Canada. It focuses on RAG pipelines, voice AI agents, full-stack applications and BI reporting.

**Live site:** [muhammadanas-portfolio-lime.vercel.app](https://muhammadanas-portfolio-lime.vercel.app)

Built with plain HTML, CSS and JavaScript: no framework and no build step. The hero includes an animated demo of the voice agent's pipeline (speech-to-text, retrieval, conflict check, routing, reply).

## Projects (voice and support agents first, then other work)

| Project | What it is | Stack |
|---|---|---|
| **Verve Voice Agent** ([live](https://verveassist.live) · [repo](https://github.com/Muhammad-Anas59/Voice-Customer-Support-Agent)) | Real-time voice support agent built for the AssemblyAI Voice Agent Hackathon. Answers from a brand's own policy documents and hands off to a human when sources conflict or a message is sensitive. | Flask-SocketIO, AssemblyAI, Gemini, ElevenLabs, FAISS, AWS EC2 |
| **AI Support Agent** ([repo](https://github.com/Muhammad-Anas59/AI-Support-Agent)) | Shopify-integrated support agent with conflict detection, live order lookup, sentiment escalation and an admin dashboard, validated by an automated evaluation harness. | Flask, Gemini API, FAISS, Shopify Admin API |
| **Loanlytics** ([live](https://loanlytics.streamlit.app) · [repo](https://github.com/Muhammad-Anas59/Loanlytics)) | Credit default risk predictor built during the Big Brains internship: XGBoost model (0.864 cross-validated ROC-AUC on 150,000 borrowers) with SHAP-based explanations and an interactive risk-score app. | Python, XGBoost, scikit-learn, SHAP, Optuna, Streamlit |
| **AI Knowledge Assistant** | Multi-knowledge-base RAG assistant that answers from company documents and flags cross-source contradictions. | Flask, Gemini API, FAISS, SQLite, Docker |
| **Hotel Reservation System** | Multi-branch hotel platform where every booking and payment commits atomically. | Flask REST API, PostgreSQL, Docker, AWS EC2, Nginx |
| **StockFlow Pro** | Desktop warehouse system with barcode-level tracking and PDF reporting, shipped as a single Windows `.exe`. | Python, CustomTkinter, MySQL |
| **Power BI Dashboards** | Interactive sales dashboards with KPI cards, slicers and breakdowns. | Power BI, DAX |

The site also covers experience (Big Brains AI/ML internship, Decode Labs AI internship, BCG X data science simulation), a technical stack overview, education (BS Data Science, UMT Lahore) and certifications, including the Big Brains internship certificate.

## Repository structure

```
index.html          # the whole site: markup, styles and the hero animation script
project-images/     # screenshots shown in each project's gallery, plus the Big Brains certificate
README.md
```

Resume (`resume.pdf`) and the social preview image (`og-image.png`) are served from the repository root.

## Run locally

No build step is needed. Clone the repo and open `index.html`, or serve it:

```bash
git clone https://github.com/Muhammad-Anas59/muhammadanas-portfolio.git
cd muhammadanas-portfolio
python -m http.server 8000
# then visit http://localhost:8000
```

## Deployment

Hosted on Vercel and connected to this repository. Every push to `main` triggers an automatic redeploy.

## Updating the content

- **Edit a project:** change its `<article class="project">` block in `index.html`.
- **Add screenshots:** put the images in `project-images/` and reference them with a relative path, following the existing `.shots-grid` blocks.
- **Update the resume:** replace `resume.pdf` in the repository root.

## Contact

- Email: [muhammadanasehsan@gmail.com](mailto:muhammadanasehsan@gmail.com)
- GitHub: [Muhammad-Anas59](https://github.com/Muhammad-Anas59)
- LinkedIn: [muhammad-anas](https://www.linkedin.com/in/muhammad-anas-a6bb5b2b3/)

Open to freelance, contract and remote work: AI/ML, RAG and voice agents, Python backends and data dashboards.
