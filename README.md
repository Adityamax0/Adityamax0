```
┌─────────────────────────────────────────────────────────────┐
│  aditya@systems:~$ whoami                                     │
│                                                                 │
│   █████╗ ██████╗ ██╗████████╗██╗   ██╗ █████╗                │
│  ██╔══██╗██╔══██╗██║╚══██╔══╝╚██╗ ██╔╝██╔══██╗               │
│  ███████║██║  ██║██║   ██║    ╚████╔╝ ███████║               │
│  ██╔══██║██║  ██║██║   ██║     ╚██╔╝  ██╔══██║               │
│  ██║  ██║██████╔╝██║   ██║      ██║   ██║  ██║               │
│  ╚═╝  ╚═╝╚═════╝ ╚═╝   ╚═╝      ╚═╝   ╚═╝  ╚═╝               │
│                                                                 │
│  PANDEY · AI/ML Engineer · Kanpur, IN                          │
└─────────────────────────────────────────────────────────────┘
```

<div align="center">

[`mail`](mailto:adityapandey9326@gmail.com) &nbsp;·&nbsp; [`linkedin`](https://www.linkedin.com/in/aditya-pandey-ai-ml) &nbsp;·&nbsp; [`github`](https://github.com/Adityamax0) &nbsp;·&nbsp; [`leetcode`](https://leetcode.com/u/adityapandey9326) &nbsp;·&nbsp; [`portfolio`](https://adityapandey.vercel.app)

</div>

<br>

```diff
+ status      : building, not learning to build
+ education   : B.Tech CSE (AI & ML) · MIPS Kanpur · Sem 4 / 8
+ shipped     : 5 independent systems, solo, end-to-end
+ looking for : internship / early-engineer role — ownership over tickets
```

I don't ship demos. I ship the version that still works after someone else pokes at it — a packet parser that doesn't choke on malformed frames, an ML pipeline that degrades gracefully when a feature is missing, an agent chain that catches its own hallucinated citation. That difference is the whole job.

<br>

## `~/projects`

<br>

### 01 · DPI Engine
**Deep packet inspection, parsed by hand — no shortcuts on the hard part**

Most "DPI" projects lean entirely on a library and call it done. This one decodes Ethernet, IPv4, and TCP/UDP frames straight from raw sockets using Python `struct` — zero parsing dependencies — then pulls the TLS SNI domain out of the handshake *before* encryption locks it away. 50+ apps classified live; a Random Forest model catches the traffic that hides its SNI. Ships with a real-time Flask dashboard and offline PCAP replay.

```
stack     Python · Scapy · Flask · scikit-learn
repo      github.com/Adityamax0/dpi-engine
```

<br>

### 02 · SCAS Backend
**The decision engine behind a crop advisory platform — built for users who may not read fluently**

Field workers get geospatially routed tickets via MongoDB `2dsphere` queries, matched within a 50km radius. Farmers photograph a diseased leaf and get a diagnosis back through Llama-3.2 Vision, or ask by voice through Whisper. A state machine handles SLA escalation without a human touching it until it's actually needed. This is infrastructure for people who don't have infrastructure.

```
stack     Node.js · Express · MongoDB · Groq Vision/Whisper · Docker
repo      github.com/Adityamax0/scas-backend
```

<br>

### 03 · Scholar-Agent Pro
**12 agents that read a paper so you don't start from zero**

Executive summary, section-by-section breakdown, an ELI15 mode for the parts that assume too much, LaTeX equation extraction, and — the one nobody builds — an adversarial agent that peer-reviews the paper's own claims instead of just summarizing them. Runs on LLaMA 3.3 70B via Groq: full pipeline in seconds, zero inference cost.

```
stack     Streamlit · Groq API · PyMuPDF · Plotly
repo      github.com/Adityamax0/scholar-agent-pro
```

<br>

### 04 · LENS
**A visual regression tool that fixes what it finds instead of just flagging it**

Catches hard-coded hex values and rogue `!important` overrides against a design contract, diffs screenshots with headless Chrome and `pixelmatch` — then goes further than most tools bother to: it rewrites the offending CSS back to the correct design token via AST transform, on its own, and alerts the team through Slack.

```
stack     Node.js · Puppeteer · pixelmatch · GitHub Actions
repo      github.com/Adityamax0/lens
```

<br>

### 05 · Memet
**An AI companion built for the conversation someone doesn't want to have alone**

98% EQ score across scripted psychological stress tests. Crisis detection routes straight to a helpline, no delay, no friction. The frontend is a single dependency-free file — no framework, no build step — deployed at zero infrastructure cost, because the people who need this shouldn't be gated by a slow load.

```
stack     FastAPI · Groq · Vanilla JS
repo      github.com/Adityamax0/memet
```

<br>

## `~/stack`

```
┌──────────────┬────────────────────────────────────────────┐
│ Language     │ Python (primary) · C++                      │
│ ML / Data    │ scikit-learn · Pandas · NumPy · NLTK         │
│ LLM / Agents │ Groq (LLaMA 3.3, Vision, Whisper) · prompt   │
│              │ & multi-agent orchestration                  │
│ Backend      │ Flask · FastAPI · Node.js · Express          │
│ Infra        │ MongoDB · Docker · GitHub Actions            │
│ Tooling      │ Git · Linux · Puppeteer                      │
└──────────────┴────────────────────────────────────────────┘
```

<br>

## `~/stats`

<div align="center">
<img src="https://github-readme-stats.vercel.app/api?username=Adityamax0&show_icons=true&theme=nord&hide_border=true&hide_title=true" width="48%"/>
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Adityamax0&layout=compact&theme=nord&hide_border=true&hide=jupyter%20notebook" width="30%"/>
</div>

<br>

## `~/track-record`

```
python      5★  HackerRank Gold Badge
dsa         100+ problems solved, LeetCode
shipped     5 systems, solo, end-to-end, in production or demo-deployed
standing    semester 4 of 8 — output ahead of the syllabus
```

<br>

## `~/how-i-think`

Most people ask *what tool solves this.* I ask *what is this problem actually doing underneath* — what has to hold true for a fix to survive contact with reality, and what breaks first if I'm wrong about it. Slower on day one. It's the only approach I've found that doesn't collapse the moment something unexpected shows up in production.

<br>

```
aditya@systems:~$ contact --reason "internship or early-engineer role"
> adityapandey9326@gmail.com
```

<div align="center">
<br>
<sub>Building in public from Kanpur, India.</sub>
</div>
