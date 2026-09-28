<h1 align="center">Shehla Mushtaq</h1>

<p align="center">
  <b>MS in AI in Digital Anti-Aging & Healthcare</b> · Inje University ·
  <a href="https://ai-sclab.com/">SCLab</a>
</p>

<p align="center">
  <a href="https://orcid.org/0009-0006-6617-3221">
    <img src="https://img.shields.io/badge/ORCID-0009--0006--6617--3221-A6CE39?style=flat-square&logo=orcid&logoColor=white" alt="ORCID">
  </a>
  <a href="https://www.linkedin.com/in/shehla-mushtaq-015343228/">
    <img src="https://img.shields.io/badge/LinkedIn-Shehla%20Mushtaq-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn">
  </a>
  <a href="mailto:shehlamushtaq63@gmail.com">
    <img src="https://img.shields.io/badge/Email-shehlamushtaq63%40gmail.com-D14836?style=flat-square&logo=gmail&logoColor=white" alt="Email">
  </a>
</p>

---

### About

Graduate researcher working at the intersection of **graph representation
learning** and **clinical AI**. My thesis builds heterogeneous graph models over
biomedical case data, combining structured medical knowledge with text and image
evidence to support diagnostic reasoning. Alongside it I build full-stack ML
systems — behaviour-driven personalisation and multi-agent research assistants.

### Research interests

- **Heterogeneous graph learning** — relation-aware transformers over clinical knowledge graphs
- **Biomedical retrieval** — dense retrieval and retrieval-augmented reasoning over case literature
- **Multimodal clinical reasoning** — aligning case text, imaging, and structured labels
- **Digital healthcare & anti-aging** — applied ML for health monitoring and longevity research

### Current work

**MedHGT** — a heterogeneous graph transformer for medical case understanding,
evaluated with stratified cross-validation over multi-relational patient graphs.

**MultiCaRe closed-loop** — an end-to-end pipeline that links case retrieval,
evidence grounding, and diagnostic prediction into a single evaluated loop.

### Toolbox

<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white" alt="PyTorch">
  <img src="https://img.shields.io/badge/PyG-3C2179?style=flat-square&logo=pytorchgeometric&logoColor=white" alt="PyTorch Geometric">
  <img src="https://img.shields.io/badge/Hugging%20Face-FFD21E?style=flat-square&logo=huggingface&logoColor=black" alt="Hugging Face">
  <img src="https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white" alt="NumPy">
  <img src="https://img.shields.io/badge/pandas-150458?style=flat-square&logo=pandas&logoColor=white" alt="pandas">
  <img src="https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white" alt="scikit-learn">
  <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" alt="FastAPI">
  <img src="https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white" alt="Next.js">
  <img src="https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black" alt="React">
  <img src="https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white" alt="MongoDB">
  <img src="https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black" alt="Linux">
  <img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white" alt="Git">
</p>

### Selected repositories

#### [adaptive-persona](https://github.com/shehlamushtaque/adaptive-persona) — AdaptiveShop

An e-commerce storefront that reshapes itself per shopper. Fourteen behavioural
counters feed a `StandardScaler → PCA → KMeans (k=8)` pipeline; each cluster
centroid is interpreted as a persona (Deal Hunter, Ethical Shopper, Gift Giver,
and five more), and the frontend re-renders layout, copy, and CTAs in real time —
same URL, different store.

`Next.js 15` · `React 19` · `FastAPI` · `scikit-learn` · `MongoDB`

#### [Startup-agent](https://github.com/shehlamushtaque/Startup-agent) — Startup Research Assistant

A multi-agent research system for startup due diligence. Specialised agents run
in parallel over funding history, competitor metrics, web search, and SEC
filings; an LLM synthesises the evidence into a cited report with a follow-up
Q&A tab. Designed to degrade honestly — missing keys or data reduce detail
instead of breaking the run.

`Python 3.11` · `FastAPI` · `WebSockets` · `sentence-transformers` · `React` · `Ollama / Groq / DeepSeek`

#### MedHGT — _thesis, coming soon_

Heterogeneous graph transformer for medical case understanding, with a
closed-loop retrieval and evaluation pipeline over multimodal case data.

---

<p align="center">
  <i>Open to research collaborations in clinical AI and graph learning.</i>
</p>
