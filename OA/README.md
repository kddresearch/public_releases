	<!--
yaml_schema_version: "2.10"
document_version: "1.2"
document_last_updated_date: "2026-10-28"
-->

<div align="center">
  <p>
    🌐 <a href="https://www.kddresearch.org">KDDResearch.org</a> &nbsp;•&nbsp;
    🤗 <a href="https://huggingface.co/KDDResearch">Hugging Face</a> &nbsp;•&nbsp;
    🦋 <a href="https://bsky.app/profile/kddresearch.bsky.social">Bluesky (@kddresearch.bsky.social)</a> &nbsp;•&nbsp;
    𝕏 <a href="https://x.com/kstate_bigdata">X (@kstate_bigdata)</a> &nbsp;•&nbsp;
    📦 <a href="https://github.com/kddresearch/public_releases">Public Releases</a> &nbsp;•&nbsp;
    🧭 <a href="https://github.com/kddresearch/public_releases/blob/main/kdd_16_research_themes.md">16 Research Themes</a>
  </p>
  <hr>
  <strong>🧬 Core Research Divisions (Public Release Directories)</strong><br>
  💬 <a href="https://github.com/kddresearch/public_releases/tree/main/NL">Natural Language [NL]</a> &nbsp;|&nbsp;
  👁️ <a href="https://github.com/kddresearch/public_releases/tree/main/CV">Computer Vision [CV]</a> &nbsp;|&nbsp;
  🤖 <a href="https://github.com/kddresearch/public_releases/tree/main/RL">Reinforcement Learning [RL]</a> &nbsp;|&nbsp;
  🛡️ <a href="https://github.com/kddresearch/public_releases/tree/main/ST">Secure &amp; Trustworthy AI [ST]</a> &nbsp;|&nbsp;
  🌾 <a href="https://github.com/kddresearch/public_releases/tree/main/OA"><strong>Other Applied AI [OA]</strong></a>
</div>

<div align="center">
 <h1>🌾 KDD Lab — Other Applied Artificial Intelligence Division [OA]</h1>
 <p>
 <strong>Project:</strong> Translational AI Systems, Scientometrics &amp; Domain Decision Support ([OA] Public Releases) | <strong>Principal Investigator:</strong> Prof. William H. Hsu<br>
 <strong>Academic Profiles:</strong> <a href="https://scholar.google.com/citations?hl=en&user=JQoJRcIAAAAJ">Google Scholar</a> • <a href="https://orcid.org/0000-0002-2950-6246">ORCID</a> • <a href="https://dblp.org/pid/21/1034.html">DBLP</a> • <a href="https://openreview.net/profile?id=~William_Hsu1">OpenReview</a><br>
 <strong>Status:</strong> ACTIVE | <strong>Core Tech:</strong> Containerized LLM/VLM Pipelines (Docker, Apptainer, vLLM), Spatio-Temporal Analytics, HCII &amp; Cognitive Prostheses
 </p>
</div>

<hr>

## 📖 Overview

The **Other Applied Artificial Intelligence `[OA]` Division** serves as the **translational and integrative systems layer** of the K-State KDD Lab, connecting foundational research in natural language (`[NL]`), computer vision (`[CV]`), reinforcement learning (`[RL]`), and trustworthy reasoning (`[ST]`) to deployable real-world decision support systems.

The `[OA]` division forces theoretical advances to adapt to practical operational constraints—including hardware/memory bounds, latency requirements, containerized reproducibility, and human-in-the-loop interaction—across interdisciplinary domains such as agricultural and hydrological modeling, scientometrics and meta-research, public health and crisis informatics, and neurosocial/human–computer intelligent interaction (HCII).

### 🎯 Tagged Research Themes (`kdd_16_research_themes.md`)

The `[OA]` division directly anchors **4 primary themes** in the canonical regionalization index while serving as the translational deployment bridge for sustainable (`KDD-01`) and end-to-end active systems (`KDD-09`):

| Theme ID | Canonical Theme Anchor | Role & Inter-Theme Cross-Links in `[OA]` |
| :--- | :--- | :--- |
| [**`KDD-03`**](https://github.com/kddresearch/public_releases/blob/main/kdd_16_research_themes.md#kdd-03-mostly-unsupervised-few-shot-temporal-topic-modeling) | **Mostly-Unsupervised Few-Shot Temporal Topic Modeling** | Tracking longitudinal topic drift across policy archives, extension bulletins, news streams, and social media observatories; feeds [**KDD-04**](https://github.com/kddresearch/public_releases/blob/main/kdd_16_research_themes.md#kdd-04-end-to-end-meta-research-pipelines-from-scientific-literature). |
| [**`KDD-04`**](https://github.com/kddresearch/public_releases/blob/main/kdd_16_research_themes.md#kdd-04-end-to-end-meta-research-pipelines-from-scientific-literature) | **End-to-End Meta-Research Pipelines from Literature** | Large-scale scientometric synthesis, evidence mapping, and automated systematic review tooling across interdisciplinary domains; couples with [**KDD-05**](https://github.com/kddresearch/public_releases/blob/main/kdd_16_research_themes.md#kdd-05-trust-weighted-inference-and-evidence-aggregation). |
| [**`KDD-11`**](https://github.com/kddresearch/public_releases/blob/main/kdd_16_research_themes.md#kdd-11-sentic-and-affective-downstream-modeling) | **Sentic and Affective Downstream Modeling** | Audience-adapted summarization, reading-level control, and affective/social-media analytics for extension, education, and human-centered decision support. |
| [**`KDD-14`**](https://github.com/kddresearch/public_releases/blob/main/kdd_16_research_themes.md#kdd-14-multimodality-as-a-unifying-constraint) | **Multimodality as a Unifying Constraint** | Integrating heterogeneous spatio-temporal, remote-sensing, tabular, and linguistic data streams into unified decision support systems (coupled with [**KDD-01**](https://github.com/kddresearch/public_releases/blob/main/kdd_16_research_themes.md#kdd-01-efficient-foundation-models-for-sustainable-machine-learning) and [**KDD-09**](https://github.com/kddresearch/public_releases/blob/main/kdd_16_research_themes.md#kdd-09-end-to-end-trusted-multimodal-learning-systems)). |

<details>
 <summary><strong>📁 Associated Publications &amp; Repositories</strong></summary>
 <br>

 ### 📋 Translational Systems &amp; Curriculum Releases
 * **Agricultural, Hydrological &amp; Epidemiological Decision Support (`AgHydro`)** — 📍 *Spatio-temporal data mining, sensor fusion, and resource management systems*
 * **Applied LLM Engineering &amp; Reproducible AI Infrastructure** — *Containerized open-weight inference pipelines (Docker, Apptainer, vLLM, Qdrant RAG) for research and graduate instruction*
 * **Human–Computer Intelligent Interaction (HCII) &amp; Cognitive Exoskeletons** — *Neurosocial user-system alignment, artifact-first GitOps workflows, and intelligent visualization*

 ### 🗄️ Public Repositories &amp; Portals
 * [`kddresearch/public_releases/OA`](https://github.com/kddresearch/public_releases/tree/main/OA) — 📍 Current division release directory
 * [`HuggingFace @KDDResearch`](https://huggingface.co/KDDResearch) — Public applied models, datasets, and course artifacts
</details>

<hr>

## 🗂️ Repository Structure

| Directory / File | Description |
| :--- | :--- |
| `data/` | Public domain datasets, spatio-temporal benchmarks, and ingestion scripts. |
| `outputs/` | Deployed system evaluations, scientometric reports, and benchmark artifacts. |
| `reference/` | Architecture runbooks, container specifications, and domain documentation. |
| `src/` | End-to-end translational pipelines, RAG/vLLM orchestration, and visualization tools. |
| `README.md` | This file. |

<hr>

## 🚀 Quick Start & Execution

**1. Prerequisites**
* Python 3.11+
* Docker / Apptainer (for containerized local inference and reproducible pipelines)

**2. Initialization**
```bash
git clone [https://github.com/kddresearch/public_releases.git](https://github.com/kddresearch/public_releases.git)
cd public_releases/OA
```

## 👥 Contributors & Citation

**Principal Investigator:** Prof. William H. Hsu ([@banazir](https://github.com/banazir) • [Google Scholar](https://scholar.google.com/citations?hl=en&user=JQoJRcIAAAAJ) • [ORCID](https://orcid.org/0000-0002-2950-6246) • [DBLP](https://dblp.org/pid/21/1034.html) • [OpenReview](https://openreview.net/profile?id=~William_Hsu1))

| Role | Name | Affiliation / Track |
| --- | --- | --- |
| **Director / PI** | Prof. William H. Hsu | K-State KDD Lab / CAIDS |
| **Division Researchers** | KDD Lab `[OA]` Graduate &amp; Undergraduate Research Team | AgHydro, Applied LLM Engineering, Scientometrics |

**Citation:**
If you use code, containers, or datasets from the `[OA]` division in your research, please cite the relevant paper listed in the sub-project directory and reference the K-State KDD Lab:
```bibtex
@misc{kddresearch_oa_2026,
  author       = {Hsu, William H. and {K-State KDD Lab Other Applied AI Division}},
  title        = {{K-State KDD Lab Other Applied Artificial Intelligence [OA] Public Releases}},
  year         = {2026},
  howpublished = {\url{[https://github.com/kddresearch/public_releases/tree/main/OA](https://github.com/kddresearch/public_releases/tree/main/OA)}}
}
```
