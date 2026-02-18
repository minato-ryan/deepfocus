<div align="center">

# 🔭 DeepFocus
### Precision Filters for Credible Research & Agent Context Control

[![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue.svg)](./LICENSE)
[![Agent-Compatible](https://img.shields.io/badge/Agent-Compatible-purple)]()

**DeepFocus** is a curated collection of search operators designed for **credible research** and **controlling the external information sources** of AI Agents.

By enforcing strict `site:` filters, DeepFocus ensures that both human researchers and autonomous agents (LLMs/RAG) retrieve information *only* from verified, high-authority academic, industrial, and regulatory domains—effectively eliminating noise, hallucinations, and SEO spam.

[**How to Use**](#how-to-use) • [**General Academic**](#general-academic) • [**CS & AI**](#cs-ai) • [**Medicine**](#medicine) • [**Physics**](#physics) • [**Social Sci**](#social-sci)

</div>

---

<h2 id="how-to-use">🛠 How to Use</h2>

Copy the **Filter Code** from any section below and paste it directly into your search bar alongside your keywords.

**Example:**
```
transformer architecture mechanisms (site:arxiv.org OR site:ieeexplore.ieee.org OR site:dl.acm.org)
```

---

<h2 id="general-academic">📚 General Academic</h2>

**Scope:** Multidisciplinary sciences, major publishers, and global archives.

### Tier 1: Top Peer-Reviewed Publishers (Highest Credibility)
*The world's largest repositories of peer-reviewed journal articles. Abstracts are free.*

| Platform | Domain | Type |
| :--- | :--- | :--- |
| **ScienceDirect** | `sciencedirect.com` | Elsevier (Bio/Med/Phys/Eng) |
| **Wiley Online** | `onlinelibrary.wiley.com` | Multidisciplinary |
| **SpringerLink** | `link.springer.com` | Multidisciplinary |
| **Oxford Academic** | `academic.oup.com` | University Press |
| **JSTOR** | `jstor.org` | Humanities/Social Sci |
| **Sage Journals** | `journals.sagepub.com` | Social/Health/Bio |
| **Taylor & Francis** | `tandfonline.com` | Multidisciplinary |

#### 📋 Copy Filter
```text
(site:sciencedirect.com OR site:onlinelibrary.wiley.com OR site:link.springer.com OR site:academic.oup.com OR site:jstor.org OR site:journals.sagepub.com OR site:tandfonline.com)

```

### Tier 2: Open Repositories & Aggregators

*High utility for open access content, but mix of peer-reviewed and preprint.*

| Platform | Domain | Type |
| :--- | :--- | :--- |
| **arXiv** | `arxiv.org` | Physics, Math, CS |
| **PubMed / PMC** | `ncbi.nlm.nih.gov` | Bio/Med Archive (NIH) |
| **ChemRxiv** | `chemrxiv.org` | Chemistry Preprints |
| **BioRxiv** | `biorxiv.org` | Biology Preprints |
| **PsyArXiv** | `psyarxiv.org` | Psychology Preprints |
| **Research Square** | `researchsquare.com` | Multidisciplinary |
| **ResearchGate** | `researchgate.net` | Researcher Social Network | Mixed |
| **Semantic Scholar** | `semanticscholar.org` | AI Research Aggregator |
| **J-STAGE** | `jstage.jst.go.jp` | Japan Science & Tech | Open Access |
| **CORE** | `core.ac.uk` | Open Access Aggregator | Open Access |

#### 📋 Copy Filter

```text
(site:arxiv.org OR site:ncbi.nlm.nih.gov OR site:semanticscholar.org OR site:chemrxiv.org OR site:biorxiv.org OR site:psyarxiv.org OR site:researchsquare.com OR site:osf.io OR site:researchgate.net OR site:jstage.jst.go.jp OR site:core.ac.uk)
```

---

<h2 id="cs-ai">💻 Computer Science & AI</h2>

**Scope:** Artificial Intelligence, Software Engineering, Theory, and Hardware.

### Tier 1: Peer-Reviewed Conferences & Journals

*The gold standard for CS research (IEEE, ACM, CVF).*

| Source | Domain | Focus |
| --- | --- | --- |
| **IEEE Xplore** | `ieeexplore.ieee.org` | Engineering/CS Standards |
| **ACM Digital Lib** | `dl.acm.org` | CS Research/Software |
| **CVF** | `cvf.com` | Computer Vision (CVPR/ICCV) |
| **ACL Anthology** | `aclweb.org` | NLP (ACL/EMNLP) |
| **NeurIPS** | `neurips.cc` | AI/ML Conference |
| **ICML** | `icml.cc` | AI/ML Conference |

### Tier 2: Industry Labs & Preprints

*Cutting-edge trends and industrial breakthroughs.*

| Source | Domain | Focus |
| --- | --- | --- |
| **arXiv (CS)** | `arxiv.org` | CS/AI Preprints |
| **OpenAI** | `openai.com` | GPT/GenAI |
| **Google DeepMind** | `deepmind.google` | AGI/AlphaFold |
| **Meta AI** | `ai.meta.com` | Open Source/Llama |
| **Hugging Face** | `huggingface.co` | Models/Datasets |

#### 📋 Copy Filter

```text
(site:ieeexplore.ieee.org OR site:dl.acm.org OR site:arxiv.org OR site:cvf.com OR site:aclweb.org OR site:neurips.cc OR site:openai.com OR site:deepmind.google OR site:huggingface.co/blog)

```

---

<h2 id="medicine">🧬 Medicine & Pharmacology</h2>

**Scope:** Clinical trials, evidence-based medicine, and drug safety.

### Tier 1: Clinical Gold Standard (Peer-Reviewed)

| Organization | Domain | Role |
| --- | --- | --- |
| **Cochrane Library** | `cochranelibrary.com` | Evidence-Based Medicine (High Trust) |
| **NEJM** | `nejm.org` | Top Clinical Journal |
| **The Lancet** | `thelancet.com` | Top Clinical Journal |
| **JAMA** | `jamanetwork.com` | American Medical Assoc. |
| **BMJ** | `bmj.com` | British Medical Journal |

### Tier 2: Regulatory & Preprints

| Organization | Domain | Role |
| --- | --- | --- |
| **WHO** | `who.int` | Global Health Standards |
| **FDA (USA)** | `fda.gov` | Drug Approval |
| **EMA (EU)** | `ema.europa.eu` | EU Drug Approval |
| **medRxiv** | `medrxiv.org` | Medical Preprints |

#### 📋 Copy Filter

```text
(site:cochranelibrary.com OR site:nejm.org OR site:thelancet.com OR site:jamanetwork.com OR site:bmj.com OR site:who.int OR site:fda.gov OR site:ncbi.nlm.nih.gov)

```

---

<h2 id="physics">⚛️ Physics & Astronomy</h2>

**Scope:** Astrophysics, High-energy physics, and Nuclear research.

| Organization | Domain | Focus |
| --- | --- | --- |
| **NASA ADS** | `ui.adsabs.harvard.edu` | Astrophysics/Physics Data |
| **arXiv (Phys)** | `arxiv.org` | Physics Preprints |
| **CERN** | `home.cern` | Particle Physics |
| **APS Journals** | `journals.aps.org` | Physical Review Letters |
| **IOP Science** | `iop.org` | Institute of Physics |
| **Nature Physics** | `nature.com/nphys` | Top Tier Journal |

#### 📋 Copy Filter

```text
(site:ui.adsabs.harvard.edu OR site:arxiv.org OR site:home.cern OR site:journals.aps.org OR site:iop.org OR site:nature.com/nphys)

```

---

<h2 id="social-sci">⚖️ Social Sciences</h2>

**Scope:** Education, Economics, Psychology, and Sociology.

### Tier 1: Academic Databases & Think Tanks

| Source | Domain | Focus |
| --- | --- | --- |
| **ERIC** | `eric.ed.gov` | Education Research (US Gov) |
| **APA PsycNET** | `psycnet.apa.org` | Psychology (Abstracts) |
| **Brookings** | `brookings.edu` | Policy Think Tank |
| **JSTOR (SocSci)** | `jstor.org` | Sociology/History |

### Tier 2: Preprints & Networks

| Platform | Domain | Focus |
| --- | --- | --- |
| **SSRN** | `ssrn.com` | Law/Econ/Social Sci |
| **PhilPapers** | `philpapers.org` | Philosophy |
| **AEA** | `aeaweb.org` | Economics |

#### 📋 Copy Filter

```text
(site:eric.ed.gov OR site:psycnet.apa.org OR site:ssrn.com OR site:brookings.edu OR site:jstor.org OR site:philpapers.org OR site:aeaweb.org)

```

---

<div align="center">
<sub>Remember to verify all information. Even high-quality domains can contain outdated research. Use these filters as a tool, not a guarantee of truth.</sub>
</div>
