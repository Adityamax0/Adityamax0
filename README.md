<div align="center">

# Aditya Pandey

**AI/ML Engineer — I build the layer between raw data and decisions that matter.**

Kanpur, India · B.Tech CSE (AI & ML), MIPS Kanpur, Class of 2028

[Email](mailto:adityapandey9326@gmail.com) &nbsp;|&nbsp; [LinkedIn](https://www.linkedin.com/in/aditya-pandey-ai-ml) &nbsp;|&nbsp; [GitHub](https://github.com/Adityamax0) &nbsp;|&nbsp; [LeetCode](https://leetcode.com/u/adityapandey9326) &nbsp;|&nbsp; [Portfolio](https://adityapandey.vercel.app)

</div>

<br>

## Profile

I design and ship systems end-to-end — packet parsers, ML pipelines, LLM-orchestrated agents, geospatial backends — not tutorials or clones. Five shipped projects, each solving a real constraint: real-time traffic classification without paid tooling, disease diagnosis from a phone photo with no signal, a UI auditor that fixes its own findings.

I'm early in my degree, not early in engineering judgment. I read RFCs before I read docs, and I'd rather spend a day understanding a problem than a week debugging a solution built on a wrong assumption.

**Currently:** deepening production ML deployment, evaluation rigor, and system architecture under load — the parts that separate a working demo from a system you can trust.

<br>

## Work

Five systems, each built solo, each solving a problem that doesn't have a clean off-the-shelf answer.

<br>

**DPI Engine** — a deep packet inspection system built from raw sockets up
No Scapy shortcuts on the parsing layer — Ethernet, IPv4, TCP/UDP frames decoded by hand with Python `struct`. Pulls TLS SNI domains out of the handshake *before* encryption locks the traffic, classifies 50+ applications, and falls back to a Random Forest model when SNI isn't present. Ships with a live Flask dashboard and offline PCAP analysis.
`Python` `Scapy` `Flask` `scikit-learn`
→ [github.com/Adityamax0/dpi-engine](https://github.com/Adityamax0)

**SCAS Backend** — the decision engine behind a crop advisory platform for Indian farmers
Routes field-worker tickets geospatially with MongoDB `2dsphere` queries (50km radius matching), diagnoses crop disease from a photo via Llama-3.2 Vision, and takes voice queries through Whisper — built for users who may not read fluently, let alone type. A state machine handles SLA escalation with no human in the loop until it's actually needed.
`Node.js` `Express` `MongoDB` `Groq Vision/Whisper` `Docker`
→ [github.com/Adityamax0/scas-backend](https://github.com/Adityamax0)

**Scholar-Agent Pro** — 12 coordinated agents that read a research paper so you don't have to start cold
Executive summaries, section breakdowns, an ELI15 mode, LaTeX equation extraction, and an adversarial agent that peer-reviews the paper's own claims. Runs on Groq's LLaMA 3.3 70B — zero inference cost, full pipeline in seconds, not minutes.
`Streamlit` `Groq API` `PyMuPDF` `Plotly`
→ [github.com/Adityamax0/scholar-agent-pro](https://github.com/Adityamax0)

**LENS** — a visual regression engine that doesn't just report drift, it fixes it
Catches hard-coded hex values and rogue `!important` overrides against a design contract, diffs UI screenshots with headless Chrome and `pixelmatch`, and — the part most tools stop short of — rewrites the offending CSS back to the correct design token via AST transform, autonomously.
`Node.js` `Puppeteer` `pixelmatch` `GitHub Actions`
→ [github.com/Adityamax0/lens](https://github.com/Adityamax0)

**Memet** — a mood-aware AI companion built for the conversations people don't want to have alone
Scored 98% EQ across scripted psychological stress tests, includes crisis detection with direct helpline routing, and ships as a zero-dependency single-file frontend — no build step, no framework, deployed at zero infrastructure cost.
`FastAPI` `Groq` `Vanilla JS`
→ [github.com/Adityamax0/memet](https://github.com/Adityamax0)

<br>

## Stack

```
Language        Python (primary) · C++
ML / Data       scikit-learn · Pandas · NumPy · NLTK
LLM / AI        Groq (LLaMA 3.3, Llama Vision, Whisper) · Prompt & agent orchestration
Backend         Flask · FastAPI · Node.js · Express
Data / Infra    MongoDB · Docker · GitHub Actions
Tooling         Git · Linux · Puppeteer
```

<br>

## Track Record

| | |
|---|---|
| Python | 5★ HackerRank Gold |
| DSA | 100+ problems solved, LeetCode |
| Shipped | 5 independently built and deployed systems |
| Standing | Semester 4 of 8 — building at a pace ahead of the curriculum |

<br>

## Principle

Most people ask what tool solves a problem. I ask what the problem is actually doing underneath — what has to be true for a fix to hold, and what breaks if I'm wrong about it. It costs time up front. It's the only way I've found to build something that doesn't fall over the first time reality disagrees with the demo.

<br>

<div align="center">

Open to internship and early-engineer roles where I can own a system, not just a ticket.

**[adityapandey9326@gmail.com](mailto:adityapandey9326@gmail.com)**

</div>
