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
  🛡️ <a href="https://github.com/kddresearch/public_releases/tree/main/ST"><strong>Secure &amp; Trustworthy AI [ST]</strong></a> &nbsp;|&nbsp;
  🌾 <a href="https://github.com/kddresearch/public_releases/tree/main/OA">Other Applied AI [OA]</a>
</div>

<div align="center">
 <h1>🛡️ KDD Lab — Secure &amp; Trustworthy Machine Learning &amp; Reasoning Division [ST]</h1>
 <p>
 <strong>Project:</strong> Epistemic Safety, Alignment, Provenance &amp; Verifiable Reasoning ([ST] Public Releases) | <strong>Principal Investigator:</strong> Prof. William H. Hsu<br>
 <strong>Academic Profiles:</strong> <a href="https://scholar.google.com/citations?hl=en&user=JQoJRcIAAAAJ">Google Scholar</a> • <a href="https://orcid.org/0000-0002-2950-6246">ORCID</a> • <a href="https://dblp.org/pid/21/1034.html">DBLP</a> • <a href="https://openreview.net/profile?id=~William_Hsu1">OpenReview</a><br>
 <strong>Status:</strong> ACTIVE | <strong>Core Tech:</strong> Probabilistic Graphical Models, Neurosymbolic Verification, Multi-Objective Alignment (LOS), XAI &amp; Provenance Ledgers
 </p>
</div>

<hr>

## 📖 Overview

The **Secure & Trustworthy Machine Learning & Reasoning `[ST]` Division** provides the **epistemic and ethical scaffolding** for the K-State KDD Lab's research agenda. Rather than treating security, fairness, and trust as post-hoc wrappers, `[ST]` formulates epistemic humility, traceable data provenance, adversarial robustness, and multi-objective value alignment as first-class mathematical objectives that shape representations, inference, and system architecture across open-world and high-stakes environments.

Core pillars of `[ST]` include:
1. **Information Trust & Provenance Verification:** Modeling reliability as a structured function of evidence corroboration, logical consistency, and world-model grounding.
2. **Latent Objective State (LOS) & Alignment Completeness:** Analyzing how scalarized safety and alignment pressures affect orthogonal latent objectives and information extraction recall/fidelity.
3. **Auditable Neurosymbolic, Causal & Multiresolution Explanation:** Ensuring every inference layer—across language, vision, and sequential control—is interpretable, falsifiable, and resilient under distribution shift.

### 🎯 Tagged Research Themes (`kdd_16_research_themes.md`)

As a cross-cutting foundational division, `[ST]` anchors or co-anchors **13 of the KDD Lab's 16 canonical research themes**:

| Theme ID | Canonical Theme Anchor | Role & Inter-Theme Cross-Links in `[ST]` |
| :--- | :--- | :--- |
| [**`KDD-01`**](https://github.com/kddresearch/public_releases/blob/main/kdd_16_research_themes.md#kdd-01-efficient-foundation-models-for-sustainable-machine-learning) | **Efficient Foundation Models for Sustainable ML** | Auditing calibration, robustness, and alignment retention under quantization, pruning, and distillation. |
| [**`KDD-02`**](https://github.com/kddresearch/public_releases/blob/main/kdd_16_research_themes.md#kdd-02-information-trust-and-world-model-grounding) | **Information Trust and World-Model Grounding** | Core epistemic trust estimation; feeds [**KDD-05**](https://github.com/kddresearch/public_releases/blob/main/kdd_16_research_themes.md#kdd-05-trust-weighted-inference-and-evidence-aggregation) and constrains [**KDD-12**](https://github.com/kddresearch/public_releases/blob/main/kdd_16_research_themes.md#kdd-12-neurosymbolic-and-ontology-aware-reasoning). |
| [**`KDD-04`**](https://github.com/kddresearch/public_releases/blob/main/kdd_16_research_themes.md#kdd-04-end-to-end-meta-research-pipelines-from-scientific-literature) | **End-to-End Meta-Research Pipelines from Literature** | Provenance tracking, claim verification, and epistemic consensus estimation across scientific corpora. |
| [**`KDD-05`**](https://github.com/kddresearch/public_releases/blob/main/kdd_16_research_themes.md#kdd-05-trust-weighted-inference-and-evidence-aggregation) | **Trust-Weighted Inference and Evidence Aggregation** | Truth discovery, fairness-aware ranking, and Bayesian belief updating across conflicting sources; supplies priors to [**KDD-13**](https://github.com/kddresearch/public_releases/blob/main/kdd_16_research_themes.md#kdd-13-causal-and-counterfactual-probabilistic-reasoning). |
| [**`KDD-06`**](https://github.com/kddresearch/public_releases/blob/main/kdd_16_research_themes.md#kdd-06-part-whole-hierarchies-for-qualitative-and-mixed-reasoning) | **Part-Whole Hierarchies for Qualitative &amp; Mixed Reasoning** | Mereotopological consistency constraints for verifiable hybrid reasoning. |
| [**`KDD-08`**](https://github.com/kddresearch/public_releases/blob/main/kdd_16_research_themes.md#kdd-08-multimodal-ontology-learning-systems) | **Multimodal Ontology Learning Systems** | Formal ontological validation of concepts induced from noisy multimodal streams. |
| [**`KDD-09`**](https://github.com/kddresearch/public_releases/blob/main/kdd_16_research_themes.md#kdd-09-end-to-end-trusted-multimodal-learning-systems) | **End-to-End Trusted Multimodal Learning Systems** | Trust-calibrated active learning and human-in-the-loop verification gates. |
| [**`KDD-10`**](https://github.com/kddresearch/public_releases/blob/main/kdd_16_research_themes.md#kdd-10-value-alignment-guardrails-and-information-extraction-completeness) | **Value Alignment Guardrails and IE Completeness** | Flagship `[ST]` theme characterizing refusal-coverage tradeoffs and multi-objective alignment via the Latent Objective State (LOS) theorem. |
| [**`KDD-12`**](https://github.com/kddresearch/public_releases/blob/main/kdd_16_research_themes.md#kdd-12-neurosymbolic-and-ontology-aware-reasoning) | **Neurosymbolic and Ontology-Aware Reasoning** | Formal argumentation and symbolic proof verification over neural outputs. |
| [**`KDD-13`**](https://github.com/kddresearch/public_releases/blob/main/kdd_16_research_themes.md#kdd-13-causal-and-counterfactual-probabilistic-reasoning) | **Causal and Counterfactual Probabilistic Reasoning** | Counterfactual robustness and structural causal verification for high-stakes decision support. |
| [**`KDD-14`**](https://github.com/kddresearch/public_releases/blob/main/kdd_16_research_themes.md#kdd-14-multimodality-as-a-unifying-constraint) | **Multimodality as a Unifying Constraint** | Cross-modal consistency invariants for detecting confabulation and out-of-distribution failures. |
| [**`KDD-15`**](https://github.com/kddresearch/public_releases/blob/main/kdd_16_research_themes.md#kdd-15-rich-representations-for-reward-value-and-policy-learning) | **Rich Representations for Reward, Value, and Policy Learning** | Preserving multidimensional value alignment in sequential decision-making without scalar collapse. |
| [**`KDD-16`**](https://github.com/kddresearch/public_releases/blob/main/kdd_16_research_themes.md#kdd-16-multiresolution-gradients-for-saliency-and-explanation) | **Multiresolution Gradients for Saliency and Explanation** | Auditable multiscale feature attribution and task-referenced quality critiquing. |

<details>
 <summary><strong>📁 Associated Publications &amp; Repositories</strong></summary>
 <br>

 ### 📋 Research Thrusts &amp; Verification Frameworks
 * **Latent Objective State (LOS) Theorem &amp; Multi-Objective Alignment** — 📍 *Quotient-space dynamics ($\mathcal{D}_\phi = \mathbb{R}^n / \sim_\phi$) formalizing when multidimensional latent objectives collapse under scalarized optimization*
 * **Value Alignment Guardrails vs. Information Extraction Completeness** — *Measuring and mitigating over-refusal and coverage loss in safety-aligned foundation models*
 * **Trust-Weighted Evidence Fusion &amp; Provenance Ledgers** — *Cryptographic and probabilistic provenance tracking for human-AI collaborative workflows*

 ### 🗄️ Public Repositories &amp; Portals
 * [`kddresearch/public_releases/ST`](https://github.com/kddresearch/public_releases/tree/main/ST) — 📍 Current division release directory
 * [`HuggingFace @KDDResearch`](https://huggingface.co/KDDResearch) — Public safety, alignment, and trust benchmarks
</details>

<hr>

## 🗂️ Repository Structure

| Directory / File | Description |
| :--- | :--- |
| `data/` | Alignment evaluation sets, counterfactual benchmarks, and provenance schemas. |
| `outputs/` | Coverage-refusal tradeoff curves, calibration audits, and verification logs. |
| `reference/` | Formal proofs, LOS specifications, and safety evaluation rubrics. |
| `src/` | Trust-weighted aggregation, neurosymbolic verifiers, and attribution tools. |
| `README.md` | This file. |

<hr>

## 🚀 Quick Start & Execution

**1. Prerequisites**
* Python 3.11+
* Docker / Apptainer or Conda environment (`environment.yml` per verification package)

**2. Initialization**
```bash
git clone [https://github.com/kddresearch/public_releases.git](https://github.com/kddresearch/public_releases.git)
cd public_releases/ST
```

## 👥 Contributors & Citation

**Principal Investigator:** Prof. William H. Hsu ([@banazir](https://github.com/banazir) • [Google Scholar](https://scholar.google.com/citations?hl=en&user=JQoJRcIAAAAJ) • [ORCID](https://orcid.org/0000-0002-2950-6246) • [DBLP](https://dblp.org/pid/21/1034.html) • [OpenReview](https://openreview.net/profile?id=~William_Hsu1))

| Role | Name | Affiliation / Track |
| --- | --- | --- |
| **Director / PI** | Prof. William H. Hsu | K-State KDD Lab / CAIDS |
| **Division Researchers** | KDD Lab `[ST]` Graduate &amp; Undergraduate Research Team | Alignment, Provenance, NeSy Verification, XAI |

**Citation:**
If you use code, proofs, or benchmarks from the `[ST]` division in your research, please cite the relevant paper listed in the sub-project directory and reference the K-State KDD Lab:
```bibtex
@misc{kddresearch_st_2026,
  author       = {Hsu, William H. and {K-State KDD Lab Secure and Trustworthy ML Division}},
  title        = {{K-State KDD Lab Secure and Trustworthy Machine Learning and Reasoning [ST] Public Releases}},
  year         = {2026},
  howpublished = {\url{[https://github.com/kddresearch/public_releases/tree/main/ST](https://github.com/kddresearch/public_releases/tree/main/ST)}}
}
```
