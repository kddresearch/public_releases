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
    🧭 <a href="https://github.com/kddresearch/public_releases/blob/main/KDD_16_RESEARCH_THEMES.md">16 Research Themes</a>
  </p>
  <hr>
  <strong>🧬 Core Research Divisions (Public Release Directories)</strong><br>
  💬 <a href="https://github.com/kddresearch/public_releases/tree/main/NL"><strong>Natural Language [NL]</strong></a> &nbsp;|&nbsp;
  👁️ <a href="https://github.com/kddresearch/public_releases/tree/main/CV">Computer Vision [CV]</a> &nbsp;|&nbsp;
  🤖 <a href="https://github.com/kddresearch/public_releases/tree/main/RL">Reinforcement Learning [RL]</a> &nbsp;|&nbsp;
  🛡️ <a href="https://github.com/kddresearch/public_releases/tree/main/ST">Secure &amp; Trustworthy AI [ST]</a> &nbsp;|&nbsp;
  🌾 <a href="https://github.com/kddresearch/public_releases/tree/main/OA">Other Applied AI [OA]</a>
</div>

<div align="center">
 <h1>💬 KDD Lab — Natural Language Division [NL]</h1>
 <p>
 <strong>Project:</strong> Natural Language, Speech &amp; Semantic Knowledge Discovery ([NL] Public Releases) | <strong>Principal Investigator:</strong> Prof. William H. Hsu<br>
 <strong>Academic Profiles:</strong> <a href="https://scholar.google.com/citations?hl=en&user=JQoJRcIAAAAJ">Google Scholar</a> • <a href="https://orcid.org/0000-0002-2950-6246">ORCID</a> • <a href="https://dblp.org/pid/21/1034.html">DBLP</a> • <a href="https://openreview.net/profile?id=~William_Hsu1">OpenReview</a><br>
 <strong>Status:</strong> ACTIVE | <strong>Core Tech:</strong> PyTorch, vLLM, Transformers, Whisper ASR, Qdrant, Neurosymbolic &amp; Probabilistic Graphical Models
 </p>
</div>

<hr>

## 📖 Overview

The **Natural Language `[NL]` Division** serves as the **semantic backbone** of the K-State KDD Lab. It focuses on representation, extraction, reasoning, trust, and longitudinal modeling of meaning across text, speech, and multimodal language artifacts. Rejecting brittle heuristic parsing and ungrounded black-box generation, the division emphasizes mostly-unsupervised learning, relational graphical model stabilization, meta-research from scientific corpora, trust-aware evidence aggregation, and neurosymbolic reasoning.

Core research questions addressed in `[NL]` include:
1. **Knowledge Stabilization:** How structured claims, entities, and ontologies are extracted and stabilized from noisy, unstructured, or code-mixed sources.
2. **Epistemic Provenance:** How uncertainty, information trust, and source provenance are represented as structured latent variables and propagated through retrieval and ranking pipelines.
3. **Longitudinal & Neurosymbolic Reasoning:** How language models support verifiable reasoning, explanation, argumentation, and decision-making over evolving time scales, domains, and modalities.

### 🎯 Tagged Research Themes (`KDD_16_RESEARCH_THEMES.md`)

The `[NL]` division anchors or co-anchors **13 of the KDD Lab's 16 canonical research themes**:

| Theme ID | Canonical Theme Anchor | Role & Inter-Theme Cross-Links in `[NL]` |
| :--- | :--- | :--- |
| [**`KDD-01`**](https://github.com/kddresearch/public_releases/blob/main/kdd_16_research_themes.md#kdd-01-efficient-foundation-models-for-sustainable-machine-learning) | **Efficient Foundation Models for Sustainable ML** | Quantization, distillation, and parameter-efficient fine-tuning for local open-weight LLM/ASR deployment; bounds [**KDD-04**](https://github.com/kddresearch/public_releases/blob/main/kdd_16_research_themes.md#kdd-04-end-to-end-meta-research-pipelines-from-scientific-literature) and [**KDD-09**](https://github.com/kddresearch/public_releases/blob/main/kdd_16_research_themes.md#kdd-09-end-to-end-trusted-multimodal-learning-systems). |
| [**`KDD-02`**](https://github.com/kddresearch/public_releases/blob/main/kdd_16_research_themes.md#kdd-02-information-trust-and-world-model-grounding) | **Information Trust and World-Model Grounding** | Distinguishes fluent generation from grounded inference; feeds trust estimates into [**KDD-05**](https://github.com/kddresearch/public_releases/blob/main/kdd_16_research_themes.md#kdd-05-trust-weighted-inference-and-evidence-aggregation), constrains [**KDD-12**](https://github.com/kddresearch/public_releases/blob/main/kdd_16_research_themes.md#kdd-12-neurosymbolic-and-ontology-aware-reasoning), and interacts with [**KDD-10**](https://github.com/kddresearch/public_releases/blob/main/kdd_16_research_themes.md#kdd-10-value-alignment-guardrails-and-information-extraction-completeness). |
| [**`KDD-03`**](https://github.com/kddresearch/public_releases/blob/main/kdd_16_research_themes.md#kdd-03-mostly-unsupervised-few-shot-temporal-topic-modeling) | **Mostly-Unsupervised Few-Shot Temporal Topic Modeling** | Models semantic drift and topic trajectories under minimal supervision; supplies structure to [**KDD-04**](https://github.com/kddresearch/public_releases/blob/main/kdd_16_research_themes.md#kdd-04-end-to-end-meta-research-pipelines-from-scientific-literature) and abstractions to [**KDD-12**](https://github.com/kddresearch/public_releases/blob/main/kdd_16_research_themes.md#kdd-12-neurosymbolic-and-ontology-aware-reasoning). |
| [**`KDD-04`**](https://github.com/kddresearch/public_releases/blob/main/kdd_16_research_themes.md#kdd-04-end-to-end-meta-research-pipelines-from-scientific-literature) | **End-to-End Meta-Research Pipelines from Literature** | Extracts, deduplicates, and synthesizes claims across scholarly corpora; relies on [**KDD-03**](https://github.com/kddresearch/public_releases/blob/main/kdd_16_research_themes.md#kdd-03-mostly-unsupervised-few-shot-temporal-topic-modeling) and [**KDD-05**](https://github.com/kddresearch/public_releases/blob/main/kdd_16_research_themes.md#kdd-05-trust-weighted-inference-and-evidence-aggregation). |
| [**`KDD-05`**](https://github.com/kddresearch/public_releases/blob/main/kdd_16_research_themes.md#kdd-05-trust-weighted-inference-and-evidence-aggregation) | **Trust-Weighted Inference and Evidence Aggregation** | Learning-to-Rank and Bayesian source weighting under conflict/imbalance; consumes [**KDD-02**](https://github.com/kddresearch/public_releases/blob/main/kdd_16_research_themes.md#kdd-02-information-trust-and-world-model-grounding) and supplies priors to [**KDD-13**](https://github.com/kddresearch/public_releases/blob/main/kdd_16_research_themes.md#kdd-13-causal-and-counterfactual-probabilistic-reasoning). |
| [**`KDD-06`**](https://github.com/kddresearch/public_releases/blob/main/kdd_16_research_themes.md#kdd-06-part-whole-hierarchies-for-qualitative-and-mixed-reasoning) | **Part-Whole Hierarchies for Qualitative &amp; Mixed Reasoning** | Mereological and compositional hierarchies bridging linguistic ontologies ([**KDD-08**](https://github.com/kddresearch/public_releases/blob/main/kdd_16_research_themes.md#kdd-08-multimodal-ontology-learning-systems)) and visual structures ([**KDD-07**](https://github.com/kddresearch/public_releases/blob/main/kdd_16_research_themes.md#kdd-07-hierarchy-aware-vision-language-explanation)). |
| [**`KDD-07`**](https://github.com/kddresearch/public_releases/blob/main/kdd_16_research_themes.md#kdd-07-hierarchy-aware-vision-language-explanation) | **Hierarchy-Aware Vision-Language Explanation** | Grounded captioning, diagram generation, and scene-graph alignment with `[CV]`. |
| [**`KDD-08`**](https://github.com/kddresearch/public_releases/blob/main/kdd_16_research_themes.md#kdd-08-multimodal-ontology-learning-systems) | **Multimodal Ontology Learning Systems** | Joint concept and ontology induction across text, audio, and video (e.g., SPAR-KG and Open IE). |
| [**`KDD-09`**](https://github.com/kddresearch/public_releases/blob/main/kdd_16_research_themes.md#kdd-09-end-to-end-trusted-multimodal-learning-systems) | **End-to-End Trusted Multimodal Learning Systems** | Active learning and silver-standard query synthesis loops for continuous knowledge extraction. |
| [**`KDD-11`**](https://github.com/kddresearch/public_releases/blob/main/kdd_16_research_themes.md#kdd-11-sentic-and-affective-downstream-modeling) | **Sentic and Affective Downstream Modeling** | Sentiment, stylistic control, and sociolinguistic code-mixing analysis; grounded by [**KDD-02**](https://github.com/kddresearch/public_releases/blob/main/kdd_16_research_themes.md#kdd-02-information-trust-and-world-model-grounding) and [**KDD-12**](https://github.com/kddresearch/public_releases/blob/main/kdd_16_research_themes.md#kdd-12-neurosymbolic-and-ontology-aware-reasoning). |
| [**`KDD-12`**](https://github.com/kddresearch/public_releases/blob/main/kdd_16_research_themes.md#kdd-12-neurosymbolic-and-ontology-aware-reasoning) | **Neurosymbolic and Ontology-Aware Reasoning** | Unifies neural LMs with formal ontologies, argumentation, sense disambiguation, and anaphora resolution. |
| [**`KDD-14`**](https://github.com/kddresearch/public_releases/blob/main/kdd_16_research_themes.md#kdd-14-multimodality-as-a-unifying-constraint) | **Multimodality as a Unifying Constraint** | Cross-modal consistency across speech, text, and video metadata for disambiguation and hallucination reduction. |
| [**`KDD-16`**](https://github.com/kddresearch/public_releases/blob/main/kdd_16_research_themes.md#kdd-16-multiresolution-gradients-for-saliency-and-explanation) | **Multiresolution Gradients for Saliency and Explanation** | Multiscale token/span attribution and interpretable rationale extraction. |

<details>
 <summary><strong>📁 Associated Publications &amp; Repositories</strong></summary>
 <br>

 ### 📋 Research Thrusts &amp; Model Releases
 * **Open Information Extraction &amp; Hybrid Learning-to-Rank (`Open IE / KDDIE`)** — 📍 *7-stage open-domain relation extraction, BM25/LambdaMART/neural reranking, and information-trust evaluation*
 * **Ontology-Grounded Multimodal Knowledge Graphs (`SPAR-KG`)** — *Weakly supervised query synthesis, silver-standard pre-labeling, and ontology verification*
 * **Code-Mixed &amp; Multilingual Speech Recognition (`MLCS`)** — *Ontology-backed ASR error correction and ambient-context grounding for spontaneous Mandarin–English speech*
 * **Topical Knowledge Maps (`TKM`)** — *Longitudinal scientometric and meta-research synthesis pipelines*

 ### 🗄️ Public Repositories &amp; Portals
 * [`kddresearch/public_releases/NL`](https://github.com/kddresearch/public_releases/tree/main/NL) — 📍 Current division release directory
 * [`HuggingFace @KDDResearch`](https://huggingface.co/KDDResearch) — Public model cards and benchmark datasets
</details>

<hr>

## 🗂️ Repository Structure

| Directory / File | Description |
| :--- | :--- |
| `data/` | Sanitized public benchmark splits, silver-standard query templates, and ontology schemas. |
| `outputs/` | Published evaluation metrics, ranking baselines, and ablation tables. |
| `reference/` | Protocol specifications, annotation rubrics, and bibliography files. |
| `src/` | Vetted source code for Open IE, Learning-to-Rank, topic modeling, and ASR post-correction. |
| `README.md` | This file. |

<hr>

## 🚀 Quick Start & Execution

**1. Prerequisites**
* Python 3.11+
* Docker / Apptainer or Conda environment (`environment.yml` provided per sub-package)

**2. Initialization**
```bash
git clone [https://github.com/kddresearch/public_releases.git](https://github.com/kddresearch/public_releases.git)
cd public_releases/NL
```

## 👥 Contributors & Citation

**Principal Investigator:** Prof. William H. Hsu ([@banazir](https://github.com/banazir) • [Google Scholar](https://scholar.google.com/citations?hl=en&user=JQoJRcIAAAAJ) • [ORCID](https://orcid.org/0000-0002-2950-6246) • [DBLP](https://dblp.org/pid/21/1034.html) • [OpenReview](https://openreview.net/profile?id=~William_Hsu1))

| Role | Name | Affiliation / Track |
| --- | --- | --- |
| **Director / PI** | Prof. William H. Hsu | K-State KDD Lab / CAIDS |
| **Division Researchers** | KDD Lab `[NL]` Graduate &amp; Undergraduate Research Team | Open IE, SPAR-KG, MLCS, TKM |

**Citation:**
If you use code, models, or datasets from the `[NL]` division in your research, please cite the relevant paper listed in the sub-project directory and reference the K-State KDD Lab:
```bibtex
@misc{kddresearch_nl_2026,
  author       = {Hsu, William H. and {K-State KDD Lab Natural Language Division}},
  title        = {{K-State KDD Lab Natural Language [NL] Public Releases}},
  year         = {2026},
  howpublished = {\url{[https://github.com/kddresearch/public_releases/tree/main/NL](https://github.com/kddresearch/public_releases/tree/main/NL)}}
}
```
