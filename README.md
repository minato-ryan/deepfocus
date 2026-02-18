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

### Tier 1: Top Peer-Reviewed Publishers

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
| **Cambridge Core** | `cambridge.org/core` | Cambridge University Press |
| **Nature** | `nature.com` | Top-tier Multidisciplinary |
| **Science Journals** | `science.org` | AAAS Journals |
| **PNAS** | `pnas.org` | National Academy of Sciences |
| **IEEE Xplore** | `ieeexplore.ieee.org` | Engineering & Tech (Essential) |

#### 📋 Copy Filter

```text
(site:sciencedirect.com OR site:onlinelibrary.wiley.com OR site:link.springer.com OR site:academic.oup.com OR site:cambridge.org/core OR site:jstor.org OR site:journals.sagepub.com OR site:tandfonline.com OR site:nature.com OR site:science.org OR site:ieeexplore.ieee.org)
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
| **HAL Open Science** | `hal.science` | French Multidisciplinary Archive |
| **MDPI** | `mdpi.com` | Massive Open Access Publisher |
| **PLOS** | `plos.org` | Public Library of Science |
| **Frontiers** | `frontiersin.org` | Open Access Series |
| **DOAJ** | `doaj.org` | Directory of OA Journals |

#### 📋 Copy Filter

```text
(site:arxiv.org OR site:ncbi.nlm.nih.gov OR site:semanticscholar.org OR site:chemrxiv.org OR site:biorxiv.org OR site:psyarxiv.org OR site:researchsquare.com OR site:osf.io OR site:researchgate.net OR site:jstage.jst.go.jp OR site:core.ac.uk OR site:hal.science OR site:mdpi.com OR site:plos.org OR site:frontiersin.org)
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
| **CVF** | `openaccess.thecvf.com` | Computer Vision (CVPR/ICCV) |
| **ACL Anthology** | `aclweb.org` | NLP (ACL/EMNLP) |
| **NeurIPS** | `neurips.cc` | AI/ML Conference |
| **ICML** | `icml.cc` | AI/ML Conference |
| **AAAI** | `aaai.org` | General AI Research |
| **IJCAI** | `ijcai.org` | Artificial Intelligence Excellence |
| **USENIX** | `usenix.org` | Systems and Security (OSDI/ATC) |

### Tier 1: Governance

*Top conferences, global standard-setters.*

| Source | Domain | Focus |
| :--- | :--- | :--- |
| **UNESCO AI** | `unesco.org` | Global AI Ethics |
| **UNIDIR** | `unidir.org` | AI Security/Disarmament |

### Tier 2: Industry Labs & Preprints

*Cutting-edge trends and industrial breakthroughs.*

| Source | Domain | Focus |
| --- | --- | --- |
| **arXiv (CS)** | `arxiv.org` | CS/AI Preprints |
| **OpenReview** | `openreview.net` | CS/AI Preprints |
| **OpenAI** | `openai.com` | GPT/GenAI |
| **Google DeepMind** | `deepmind.google` | AGI/AlphaFold |
| **Meta AI** | `ai.meta.com` | Open Source/Llama |
| **Microsoft Research** | `microsoft.com/research` | CS/AI Research |
| **Anthropic** | `anthropic.com` | Claude/GenAI |
| **Mistral AI** | `mistral.ai` | Efficient Open-weight Models |
| **NVIDIA Research** | `research.nvidia.com` | Graphics/GPU Acceleration/AI |
| **Databricks** | `databricks.com/blog` | Enterprise AI/LLM Training |
| **Hugging Face** | `huggingface.co` | Models/Datasets |

### Tier 2: Expert Blogs & Niche Communities

*Deep dives, formal verification, and robotics.*

| Source | Domain | Focus |
| :--- | :--- | :--- |
| **Distill** | `distill.pub` | Machine Learning Visualization |
| **Lean Community** | `leanprover-community.github.io` | Formal Math Verification |
| **Robohub** | `robohub.org` | Robotics Labs |
| **Sebastian Ruder** | `ruder.io` | NLP/Transfer Learning |
| **Tim Dettmers** | `timdettmers.com` | LLM Efficiency/Quantization |
| **Lilian Weng** | `lilianweng.github.io` | Machine Learning |

#### 📋 Copy Filter

```text
(site:openreview.net OR site:openaccess.thecvf.com OR site:arxiv.org OR site:dl.acm.org OR site:ieeexplore.ieee.org OR site:aclweb.org OR site:neurips.cc OR site:icml.cc OR site:aaai.org OR site:ijcai.org OR site:usenix.org OR site:openai.com OR site:anthropic.com OR site:deepmind.google OR site:ai.meta.com OR site:microsoft.com OR site:mistral.ai OR site:research.nvidia.com OR site:huggingface.co OR site:lilianweng.github.io OR site:distill.pub OR site:unesco.org OR site:unidir.org)
```

---

<h2 id="medicine">🧬 Medicine & Pharmacology</h2>

**Scope:** Clinical trials, evidence-based medicine, and drug safety.

### Tier 1: Clinical Gold Standard (Peer-Reviewed)

| Source | Domain | Focus |
| --- | --- | --- |
| **Cochrane Library** | `cochranelibrary.com` | Evidence-Based Medicine (High Trust) |
| **NEJM** | `nejm.org` | Top Clinical Journal |
| **The Lancet** | `thelancet.com` | Top Clinical Journal |
| **JAMA** | `jamanetwork.com` | American Medical Assoc. |
| **BMJ** | `bmj.com` | British Medical Journal |
| **PubMed** | `pubmed.ncbi.nlm.nih.gov` | Primary database for biomedical literature |
| **ClinicalTrials** | `clinicaltrials.gov` | World's largest clinical trials registry |

### Tier 2: Regulatory & Preprints

| Source | Domain | Focus |
| --- | --- | --- |
| **WHO** | `who.int` | Global Health Standards |
| **FDA (USA)** | `fda.gov` | Drug Approval |
| **EMA (EU)** | `ema.europa.eu` | EU Drug Approval |
| **medRxiv** | `medrxiv.org` | Medical Preprints |

### Tier 3: Specialized Pharmacology & Guidelines

| Source | Domain | Focus |
| --- | --- | --- |
| **Nature Medicine** | `nature.com/nm` | High-impact translational research |
| **NICE (UK)** | `nice.org.uk` | Clinical guidelines and cost-effectiveness |
| **Medicines** | `medicines.org.uk` | Electronic Medicines Compendium (Detailed SPCs) |

#### 📋 Copy Filter

```text
(site:cochranelibrary.com OR site:nejm.org OR site:thelancet.com OR site:jamanetwork.com OR site:bmj.com OR site:who.int OR site:fda.gov OR site:ema.europa.eu OR site:medrxiv.org OR site:pubmed.ncbi.nlm.nih.gov OR site:clinicaltrials.gov OR site:nice.org.uk)
```

---

<h2 id="physics">⚛️ Physics & Astronomy</h2>

**Scope:** Astrophysics, High-energy physics, and Nuclear research.

| Source | Domain | Focus |
| --- | --- | --- |
| **NASA ADS** | `ui.adsabs.harvard.edu` | Astrophysics/Physics Data |
| **arXiv (Phys)** | `arxiv.org` | Physics Preprints |
| **CERN** | `home.cern` | Particle Physics |
| **APS Journals** | `journals.aps.org` | Physical Review Letters |
| **IOP Science** | `iop.org` | Institute of Physics |
| **Nature Physics** | `nature.com` | Top Tier Journal |
| **INSPIRE-HEP** | `inspirehep.net` | High-Energy Physics Literature Database |
| **AIP Publishing** | `pubs.aip.org` | American Institute of Physics Journals |
| **ScienceDirect** | `sciencedirect.com` | Elsevier Physics & Astronomy Collection |
| **STScI** | `stsci.edu` | Hubble & James Webb Space Telescope Data |
| **Phys.org** | `phys.org` | Physics News & Research Highlights |

#### 📋 Copy Filter

```text
(site:ui.adsabs.harvard.edu OR site:arxiv.org OR site:home.cern OR site:journals.aps.org OR site:iop.org OR site:nature.com OR site:inspirehep.net OR site:pubs.aip.org OR site:sciencedirect.com)
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
| **NBER** | `nber.org` | National Bureau of Economic Research (Top-tier Economics) |
| **SAGE Journals** | `journals.sagepub.com` | Leading publisher for Sociology & Psychology |
| **OECD iLibrary** | `oecd-ilibrary.org` | Global Economic & Social Data/Reports |
| **Taylor & Francis** | `tandfonline.com` | Major academic publisher for Education & Social Sci |
| **DOAJ** | `doaj.org` | Directory of Open Access Journals (Great for free full-text) |

### Tier 2: Preprints & Networks

| Platform | Domain | Focus |
| --- | --- | --- |
| **SSRN** | `ssrn.com` | Law/Econ/Social Sci |
| **PhilPapers** | `philpapers.org` | Philosophy |
| **AEA** | `aeaweb.org` | Economics |

#### 📋 Copy Filter

```text
(site:eric.ed.gov OR site:psycnet.apa.org OR site:ssrn.com OR site:brookings.edu OR site:jstor.org OR site:philpapers.org OR site:aeaweb.org OR site:nber.org OR site:journals.sagepub.com OR site:oecd-ilibrary.org OR site:tandfonline.com OR site:doaj.org)
```

---

<div align="center">
<sub>Remember to verify all information. Even high-quality domains can contain outdated research. Use these filters as a tool, not a guarantee of truth.</sub>
</div>
