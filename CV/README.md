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
  👁️ <a href="https://github.com/kddresearch/public_releases/tree/main/CV"><strong>Computer Vision [CV]</strong></a> &nbsp;|&nbsp;
  🤖 <a href="https://github.com/kddresearch/public_releases/tree/main/RL">Reinforcement Learning [RL]</a> &nbsp;|&nbsp;
  🛡️ <a href="https://github.com/kddresearch/public_releases/tree/main/ST">Secure &amp; Trustworthy AI [ST]</a> &nbsp;|&nbsp;
  🌾 <a href="https://github.com/kddresearch/public_releases/tree/main/OA">Other Applied AI [OA]</a>
</div>

<div align="center">
 <h1>👁️ KDD Lab — Computer Vision Division [CV]</h1>
 <p>
 <strong>Project:</strong> Structured Perception, Hierarchical Vision &amp; Multimodal Grounding ([CV] Public Releases) | <strong>Principal Investigator:</strong> Prof. William H. Hsu<br>
 <strong>Academic Profiles:</strong> <a href="https://scholar.google.com/citations?hl=en&user=JQoJRcIAAAAJ">Google Scholar</a> • <a href="https://orcid.org/0000-0002-2950-6246">ORCID</a> • <a href="https://dblp.org/pid/21/1034.html">DBLP</a> • <a href="https://openreview.net/profile?id=~William_Hsu1">OpenReview</a><br>
 <strong>Status:</strong> ACTIVE | <strong>Core Tech:</strong> PyTorch, Vision-Language Models (VLMs), Scene &amp; Part-Whole Graphs, Multiresolution XAI, Task-Referenced IQA
 </p>
</div>

<hr>

## 📖 Overview

The **Computer Vision `[CV]` Division** provides **perceptual grounding and structured visual abstractions** for the K-State KDD Lab's broader learning and reasoning architecture. Rather than treating vision as isolated pixel-level pattern recognition, the `[CV]` division treats visual perception as the structural foundation for multi-horizon world models—explicitly extracting part–whole relationships, taxonomic hierarchies, and functional/causal interactions from images and video streams.

Core capabilities advanced by `[CV]` include:
1. **Hierarchical & Part-Whole Visual Understanding:** Inducing compositional representations across ecological, biomedical, agricultural, and biomechanical domains.
2. **Multimodal Semantic Alignment:** Tightly coupling visual encoders with natural language, domain ontologies, and symbolic constraints.
3. **Active & Explainable Perception:** Leveraging multiresolution saliency and Task-Referenced Image Quality Assessment (TR-IQA) to explain model decisions and guide real-time image capture.

### 🎯 Tagged Research Themes (`kdd_16_research_themes.md`)

The `[CV]` division anchors or co-anchors **7 of the KDD Lab's 16 canonical research themes**:

| Theme ID | Canonical Theme Anchor | Role & Inter-Theme Cross-Links in `[CV]` |
| :--- | :--- | :--- |
| [**`KDD-01`**](https://github.com/kddresearch/public_releases/blob/main/kdd_16_research_themes.md#kdd-01-efficient-foundation-models-for-sustainable-machine-learning) | **Efficient Foundation Models for Sustainable ML** | Model compression, pruning, and distillation for edge/field deployment of vision and VLM pipelines (e.g., mobile ecological and agricultural sensing). |
| [**`KDD-06`**](https://github.com/kddresearch/public_releases/blob/main/kdd_16_research_themes.md#kdd-06-part-whole-hierarchies-for-qualitative-and-mixed-reasoning) | **Part-Whole Hierarchies for Qualitative &amp; Mixed Reasoning** | Anatomical, morphological, and spatial part–whole decompositions that directly ground [**KDD-07**](https://github.com/kddresearch/public_releases/blob/main/kdd_16_research_themes.md#kdd-07-hierarchy-aware-vision-language-explanation) and [**KDD-08**](https://github.com/kddresearch/public_releases/blob/main/kdd_16_research_themes.md#kdd-08-multimodal-ontology-learning-systems). |
| [**`KDD-07`**](https://github.com/kddresearch/public_releases/blob/main/kdd_16_research_themes.md#kdd-07-hierarchy-aware-vision-language-explanation) | **Hierarchy-Aware Vision-Language Explanation** | Contrastive and scene-graph-grounded visual explanation, linking part–whole structures ([**KDD-06**](https://github.com/kddresearch/public_releases/blob/main/kdd_16_research_themes.md#kdd-06-part-whole-hierarchies-for-qualitative-and-mixed-reasoning)) with multiscale attribution ([**KDD-16**](https://github.com/kddresearch/public_releases/blob/main/kdd_16_research_themes.md#kdd-16-multiresolution-gradients-for-saliency-and-explanation)). |
| [**`KDD-08`**](https://github.com/kddresearch/public_releases/blob/main/kdd_16_research_themes.md#kdd-08-multimodal-ontology-learning-systems) | **Multimodal Ontology Learning Systems** | Aligning visual taxons, cellular morphologies, and video events with formal symbolic ontologies alongside `[NL]` and `[ST]`. |
| [**`KDD-09`**](https://github.com/kddresearch/public_releases/blob/main/kdd_16_research_themes.md#kdd-09-end-to-end-trusted-multimodal-learning-systems) | **End-to-End Trusted Multimodal Learning Systems** | Active perception and human-in-the-loop visual verification systems integrating uncertainty and attribution. |
| [**`KDD-14`**](https://github.com/kddresearch/public_releases/blob/main/kdd_16_research_themes.md#kdd-14-multimodality-as-a-unifying-constraint) | **Multimodality as a Unifying Constraint** | Exploiting visual–textual–temporal consistency as a structural regularizer across video analytics and multimodal extraction. |
| [**`KDD-16`**](https://github.com/kddresearch/public_releases/blob/main/kdd_16_research_themes.md#kdd-16-multiresolution-gradients-for-saliency-and-explanation) | **Multiresolution Gradients for Saliency and Explanation** | Multiscale visual saliency and XAI-driven Task-Referenced Image Quality Assessment (TR-IQA) for real-time capture critiquing. |

<details>
 <summary><strong>📁 Associated Publications &amp; Repositories</strong></summary>
 <br>

 ### 📋 Research Thrusts &amp; Model Releases
 * **BeeMachine &amp; Pollinator Computer Vision** — 📍 *Fine-grained species identification, part-whole morphological attribution, and task-referenced image capture critiquing*
 * **Biomedical &amp; Cellular Image Analysis (`Astroglia`)** — *3D/2D super-resolution, cellular morphology segmentation, and structured biological representation*
 * **Biomechanics &amp; Behavioral Video Analytics (`Tackle Study` / `CNAP`)** — *Spatio-temporal pose/contact tracking and automated behavioral scoring*
 * **Agricultural &amp; Livestock Vision (`AgVision`)** — *Phenotyping, remote sensing, and organism tracking under field constraints*

 ### 🗄️ Public Repositories &amp; Portals
 * [`kddresearch/public_releases/CV`](https://github.com/kddresearch/public_releases/tree/main/CV) — 📍 Current division release directory
 * [`HuggingFace @KDDResearch`](https://huggingface.co/KDDResearch) — Public vision checkpoints and evaluation benchmarks
</details>

<hr>

## 🗂️ Repository Structure

| Directory / File | Description |
| :--- | :--- |
| `data/` | Dataset loaders, preprocessing transforms, and annotation schemas. |
| `outputs/` | Quantitative benchmarks, saliency maps, ROC/calibration curves, and ablation logs. |
| `reference/` | Taxonomic ontologies, task-referenced IQA rubrics, and related literature. |
| `src/` | Training, inference, and multiresolution attribution pipelines. |
| `README.md` | This file. |

<hr>

## 🚀 Quick Start & Execution

**1. Prerequisites**
* Python 3.11+ with CUDA-enabled PyTorch
* Docker / Apptainer container specification (`Dockerfile` / `environment.yml` per project)

**2. Initialization**
```bash
git clone [https://github.com/kddresearch/public_releases.git](https://github.com/kddresearch/public_releases.git)
cd public_releases/CV
```

## 👥 Contributors & Citation

**Principal Investigator:** Prof. William H. Hsu ([@banazir](https://github.com/banazir) • [Google Scholar](https://scholar.google.com/citations?hl=en&user=JQoJRcIAAAAJ) • [ORCID](https://orcid.org/0000-0002-2950-6246) • [DBLP](https://dblp.org/pid/21/1034.html) • [OpenReview](https://openreview.net/profile?id=~William_Hsu1))

| Role | Name | Affiliation / Track |
| --- | --- | --- |
| **Director / PI** | Prof. William H. Hsu | K-State KDD Lab / CAIDS |
| **Division Researchers** | KDD Lab `[CV]` Graduate &amp; Undergraduate Research Team | BeeMachine, Astroglia, Tackle Study, AgVision |

**Citation:**
If you use code, models, or datasets from the `[CV]` division in your research, please cite the relevant paper listed in the sub-project directory and reference the K-State KDD Lab:
```bibtex
@misc{kddresearch_cv_2026,
  author       = {Hsu, William H. and {K-State KDD Lab Computer Vision Division}},
  title        = {{K-State KDD Lab Computer Vision [CV] Public Releases}},
  year         = {2026},
  howpublished = {\url{[https://github.com/kddresearch/public_releases/tree/main/CV](https://github.com/kddresearch/public_releases/tree/main/CV)}}
}
```
