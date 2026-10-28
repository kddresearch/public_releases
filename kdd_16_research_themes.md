<!--
yaml_schema_version: "2.10"
document_version: "1.0"
document_last_updated_date: "2026-10-28"
-->

<div align="center">
  <h1>🧭 K-State KDD Lab: 16 Canonical Research Themes (KDD-01 – KDD-16)</h1>
  <p>
    <strong>Laboratory for Knowledge Discovery in Databases (KDD Lab) • Est. 1999</strong><br>
    <em>Department of Computer Science • Carl R. Ice College of Engineering • Kansas State University</em><br>
    <em>A Founding Laboratory of the Center for Artificial Intelligence and Data Science (CAIDS)</em>
  </p>
  <p>
    🌐 <a href="https://www.kddresearch.org">KDDResearch.org</a> &nbsp;•&nbsp;
    🤗 <a href="https://huggingface.co/KDDResearch">Hugging Face</a> &nbsp;•&nbsp;
    🦋 <a href="https://bsky.app/profile/kddresearch.bsky.social">Bluesky (@kddresearch.bsky.social)</a> &nbsp;•&nbsp;
    𝕏 <a href="https://x.com/kstate_bigdata">X (@kstate_bigdata)</a> &nbsp;•&nbsp;
    📦 <a href="https://github.com/kddresearch/public_releases">Public Releases</a>
  </p>
  <p>
    <strong>Principal Investigator:</strong> Prof. William H. Hsu
    (<a href="https://github.com/banazir">@banazir</a> •
    <a href="https://scholar.google.com/citations?hl=en&user=JQoJRcIAAAAJ">Google Scholar</a> •
    <a href="https://orcid.org/0000-0002-2950-6246">ORCID</a> •
    <a href="https://dblp.org/pid/21/1034.html">DBLP</a> •
    <a href="https://openreview.net/profile?id=~William_Hsu1">OpenReview</a>)
  </p>
  <hr>
  <strong>🧬 Core Research Divisions (Public Release Directories)</strong><br>
  💬 <a href="https://github.com/kddresearch/public_releases/tree/main/NL">Natural Language [NL]</a> &nbsp;|&nbsp;
  👁️ <a href="https://github.com/kddresearch/public_releases/tree/main/CV">Computer Vision [CV]</a> &nbsp;|&nbsp;
  🤖 <a href="https://github.com/kddresearch/public_releases/tree/main/RL">Reinforcement Learning [RL]</a> &nbsp;|&nbsp;
  🛡️ <a href="https://github.com/kddresearch/public_releases/tree/main/ST">Secure &amp; Trustworthy AI [ST]</a> &nbsp;|&nbsp;
  🌾 <a href="https://github.com/kddresearch/public_releases/tree/main/OA">Other Applied AI [OA]</a>
</div>

---

## 🏛️ Mission & Ontological Index

The **Laboratory for Knowledge Discovery in Databases (KDD Lab)** at Kansas State University is dedicated to the systematic decomposition of analytical learning problems using statistically sound, information-theoretic, and probabilistic criteria. We bridge the gap between statistical pattern recognition and symbolic reasoning by engineering adaptive architectures that preserve epistemic humility, traceable provenance, and structural safety.

This document serves as the canonical public anchor for the **16 Longitudinal Research Themes (`KDD-01` – `KDD-16`)** across our five functional divisions.

| Stable ID | Canonical Theme Title | Tagged Divisions | Primary Keywords |
| :--- | :--- | :--- | :--- |
| [**`KDD-01`**](#kdd-01-efficient-foundation-models-for-sustainable-machine-learning) | Efficient Foundation Models for Sustainable Machine Learning | `[NL]` `[CV]` `[RL]` `[ST]` | efficiency, compression, distillation, quantization, sustainability |
| [**`KDD-02`**](#kdd-02-information-trust-and-world-model-grounding) | Information Trust and World-Model Grounding | `[NL]` `[ST]` | epistemics, factuality, provenance, structured uncertainty |
| [**`KDD-03`**](#kdd-03-mostly-unsupervised-few-shot-temporal-topic-modeling) | Mostly-Unsupervised Few-Shot Temporal Topic Modeling | `[NL]` `[OA]` | semantic drift, dynamic topic models, few-shot induction |
| [**`KDD-04`**](#kdd-04-end-to-end-meta-research-pipelines-from-scientific-literature) | End-to-End Meta-Research Pipelines from Scientific Literature | `[NL]` `[ST]` `[OA]` | scholarly IE, claim deduplication, epistemic synthesis |
| [**`KDD-05`**](#kdd-05-trust-weighted-inference-and-evidence-aggregation) | Trust-Weighted Inference and Evidence Aggregation | `[NL]` `[ST]` | truth discovery, Bayesian aggregation, evidence fusion |
| [**`KDD-06`**](#kdd-06-part-whole-hierarchies-for-qualitative-and-mixed-reasoning) | Part-Whole Hierarchies for Qualitative and Mixed Reasoning | `[NL]` `[CV]` `[ST]` | mereotopology, compositional hierarchies, hybrid reasoning |
| [**`KDD-07`**](#kdd-07-hierarchy-aware-vision-language-explanation) | Hierarchy-Aware Vision-Language Explanation | `[CV]` `[NL]` | explainable vision, scene graphs, contrastive alignment |
| [**`KDD-08`**](#kdd-08-multimodal-ontology-learning-systems) | Multimodal Ontology Learning Systems | `[NL]` `[CV]` `[ST]` | ontology induction, multimodal knowledge graphs |
| [**`KDD-09`**](#kdd-09-end-to-end-trusted-multimodal-learning-systems) | End-to-End Trusted Multimodal Learning Systems | `[NL]` `[CV]` `[RL]` `[ST]` | active learning, active perception, never-ending learning |
| [**`KDD-10`**](#kdd-10-value-alignment-guardrails-and-information-extraction-completeness) | Value Alignment Guardrails and Information Extraction Completeness | `[ST]` | AI safety, refusal-coverage tradeoffs, adversarial robustness |
| [**`KDD-11`**](#kdd-11-sentic-and-affective-downstream-modeling) | Sentic and Affective Downstream Modeling | `[NL]` `[OA]` | affective computing, controlled generation, stylistic variation |
| [**`KDD-12`**](#kdd-12-neurosymbolic-and-ontology-aware-reasoning) | Neurosymbolic and Ontology-Aware Reasoning | `[NL]` `[ST]` | formal argumentation, sense disambiguation, hybrid inference |
| [**`KDD-13`**](#kdd-13-causal-and-counterfactual-probabilistic-reasoning) | Causal and Counterfactual Probabilistic Reasoning | `[RL]` `[ST]` | Bayesian decision networks, structural causal models, counterfactuals |
| [**`KDD-14`**](#kdd-14-multimodality-as-a-unifying-constraint) | Multimodality as a Unifying Constraint | `[NL]` `[CV]` `[RL]` `[ST]` `[OA]` | cross-modal consistency, multimodal fusion, grounding constraints |
| [**`KDD-15`**](#kdd-15-rich-representations-for-reward-value-and-policy-learning) | Rich Representations for Reward, Value, and Policy Learning | `[RL]` `[ST]` | inverse RL, hyperbolic discounting, non-stationary MDPs |
| [**`KDD-16`**](#kdd-16-multiresolution-gradients-for-saliency-and-explanation) | Multiresolution Gradients for Saliency and Explanation | `[NL]` `[CV]` `[ST]` | multiscale attribution, task-referenced IQA, XAI |

---

# KDD-01: Efficient Foundation Models for Sustainable Machine Learning

* **Division Tags:** [[NL]](https://github.com/kddresearch/public_releases/tree/main/NL) • [[CV]](https://github.com/kddresearch/public_releases/tree/main/CV) • [[RL]](https://github.com/kddresearch/public_releases/tree/main/RL) • [[ST]](https://github.com/kddresearch/public_releases/tree/main/ST)
* **Core Idea:** Methods for reducing parameter count, memory footprint, and energy consumption via quantization, pruning, knowledge distillation, and compute-bounded cramming across pretraining, fine-tuning, and inference.
* **Scientific Context & Explanation:** Tracing to early KDD Lab research on automatic synthesis of heterogeneous compression techniques, feature selection wrappers, and scalable high-performance data mining, this theme frames sustainability as a systems-level question: *how can expressive probabilistic, neural, and hybrid foundation models retain reasoning fidelity while operating under real-world hardware and energy constraints?*
* **Literature Anchors:** Han et al. (2015, deep compression and pruning); Hinton et al. (2015, knowledge distillation); Dettmers et al. (2022, LLM.int8() and quantization); memory-efficient and compute-optimal training architectures.
* **Cross-Links:**
  * Constrains deployment architectures in [**KDD-09**](#kdd-09-end-to-end-trusted-multimodal-learning-systems) (End-to-End Trusted Multimodal Learning Systems) and [**KDD-04**](#kdd-04-end-to-end-meta-research-pipelines-from-scientific-literature) (Meta-Research Pipelines).
  * Interacts with [**KDD-10**](#kdd-10-value-alignment-guardrails-and-information-extraction-completeness) on preserving alignment and extraction recall under model compression.

---

# KDD-02: Information Trust and World-Model Grounding

* **Division Tags:** [[NL]](https://github.com/kddresearch/public_releases/tree/main/NL) • [[ST]](https://github.com/kddresearch/public_releases/tree/main/ST)
* **Core Idea:** Frameworks for evaluating, estimating, and reasoning about the trustworthiness, reliability, and epistemic grounding of extracted or generated information relative to implicit or explicit world models.
* **Scientific Context & Explanation:** Modern foundation models frequently emit statements that appear fluent and coherent yet lack guarantees of factual correctness or provenance. Rooted in Bayesian network inference and probabilistic reasoning, this theme investigates how to distinguish fluent generation from grounded inference, separate epistemic uncertainty from stylistic hedging, and represent confidence and trust as structured latent variables inferred from source agreement, logical consistency, and empirical alignment rather than scalar scores.
* **Literature Anchors:** Pearl (2009, causality and probabilistic networks); Floridi (2011, philosophy and epistemics of information); truth discovery, data fusion, and calibration/factuality in large language models.
* **Cross-Links:**
  * Feeds trust estimates directly into [**KDD-05**](#kdd-05-trust-weighted-inference-and-evidence-aggregation) (Trust-Weighted Inference and Evidence Aggregation).
  * Provides epistemic calibration for [**KDD-03**](#kdd-03-mostly-unsupervised-few-shot-temporal-topic-modeling), [**KDD-11**](#kdd-11-sentic-and-affective-downstream-modeling), and [**KDD-12**](#kdd-12-neurosymbolic-and-ontology-aware-reasoning).
  * Interacts with safety and refusal boundaries in [**KDD-10**](#kdd-10-value-alignment-guardrails-and-information-extraction-completeness).

---

# KDD-03: Mostly-Unsupervised Few-Shot Temporal Topic Modeling

* **Division Tags:** [[NL]](https://github.com/kddresearch/public_releases/tree/main/NL) • [[OA]](https://github.com/kddresearch/public_releases/tree/main/OA)
* **Core Idea:** Techniques for dynamic topic induction with minimal supervision, adaptive time scales, and explicit modeling of semantic and topic drift over evolving corpora.
* **Scientific Context & Explanation:** Real-world document streams (scientific literature, policy archives, social media telemetry) evolve continuously. Building on hierarchical Bayesian modeling (HDP-based topic models) and continuous-time representations, this research models topics not as static word distributions, but as trajectories through semantic space that emerge, split, merge, or decay across adaptive temporal granularities under zero-shot or few-shot supervision.
* **Literature Anchors:** Blei & Lafferty (2006, Dynamic Topic Models); Wang et al. (2008, continuous-time dynamic topic models); nonparametric Bayesian models; time-aware neural embeddings and semantic shift detection.
* **Cross-Links:**
  * Supplies longitudinal topic structure to [**KDD-04**](#kdd-04-end-to-end-meta-research-pipelines-from-scientific-literature) (Meta-Research Pipelines).
  * Depends on epistemic trust calibration from [**KDD-02**](#kdd-02-information-trust-and-world-model-grounding).
  * Informs concept abstraction layers for [**KDD-08**](#kdd-08-multimodal-ontology-learning-systems) and [**KDD-12**](#kdd-12-neurosymbolic-and-ontology-aware-reasoning).

---

# KDD-04: End-to-End Meta-Research Pipelines from Scientific Literature

* **Division Tags:** [[NL]](https://github.com/kddresearch/public_releases/tree/main/NL) • [[ST]](https://github.com/kddresearch/public_releases/tree/main/ST) • [[OA]](https://github.com/kddresearch/public_releases/tree/main/OA)
* **Core Idea:** Automated pipelines for parsing, extracting, deduplicating, aggregating, and estimating scientific quantities and claims across large collections of scholarly documents.
* **Scientific Context & Explanation:** Scientific progress increasingly depends on treating the research literature itself as a structured, queryable dataset. Integrating layout detection, structural parsing, metadata extraction, and named entity/relation recognition, this theme moves beyond surface information extraction to *epistemic aggregation*: determining what a body of literature collectively supports, where studies conflict, and how methodological quality shapes confidence.
* **Literature Anchors:** Bornmann & Marx (2014, scientometrics); Ammar et al. (2018, Semantic Scholar literature graph); scientific knowledge graphs, systematic review automation, and scholarly NLP.
* **Cross-Links:**
  * Relies on [**KDD-03**](#kdd-03-mostly-unsupervised-few-shot-temporal-topic-modeling) for longitudinal topic organization.
  * Requires [**KDD-05**](#kdd-05-trust-weighted-inference-and-evidence-aggregation) for trust-weighted claim synthesis.
  * Feeds structured priors and domain rules into [**KDD-12**](#kdd-12-neurosymbolic-and-ontology-aware-reasoning) and [**KDD-13**](#kdd-13-causal-and-counterfactual-probabilistic-reasoning).

---

# KDD-05: Trust-Weighted Inference and Evidence Aggregation

* **Division Tags:** [[NL]](https://github.com/kddresearch/public_releases/tree/main/NL) • [[ST]](https://github.com/kddresearch/public_releases/tree/main/ST)
* **Core Idea:** Empirical, probabilistic, and logical methods for weighting heterogeneous sources, topics, and posterior estimates by trust, uncertainty, class imbalance, and evidentiary corroboration.
* **Scientific Context & Explanation:** When multiple extractors, sensors, or documents make overlapping or conflicting claims, naive majority voting or unweighted averaging fails. Emerging from ensemble learning and probabilistic graphical models, this theme develops context-sensitive methods for assigning source credibility weights, propagating uncertainty through multi-stage pipelines (including Learning-to-Rank), and reconciling disagreement without erasing valid minority evidence.
* **Literature Anchors:** Li et al. (2016, truth discovery and data fusion surveys); Bayesian model averaging; multi-source credibility modeling and imbalance-aware learning.
* **Cross-Links:**
  * Consumes structured trust estimates from [**KDD-02**](#kdd-02-information-trust-and-world-model-grounding).
  * Powers scholarly synthesis in [**KDD-04**](#kdd-04-end-to-end-meta-research-pipelines-from-scientific-literature).
  * Supplies calibrated priors for [**KDD-13**](#kdd-13-causal-and-counterfactual-probabilistic-reasoning) (Causal Reasoning) and supports active decision pipelines in [**KDD-09**](#kdd-09-end-to-end-trusted-multimodal-learning-systems).

---

# KDD-06: Part-Whole Hierarchies for Qualitative and Mixed Reasoning

* **Division Tags:** [[NL]](https://github.com/kddresearch/public_releases/tree/main/NL) • [[CV]](https://github.com/kddresearch/public_releases/tree/main/CV) • [[ST]](https://github.com/kddresearch/public_releases/tree/main/ST)
* **Core Idea:** Representing and inducing hierarchical part-whole (mereological and mereotopological) structures to support qualitative, quantitative, and hybrid reasoning across biological, ecological, social, and engineered systems.
* **Scientific Context & Explanation:** Complex entities—ranging from anatomical and cellular structures or pollinator morphologies to multi-document arguments—cannot be faithfully modeled as flat feature vectors. Rooted in relational graphical models and structural knowledge representation, this theme formalizes compositional part-whole hierarchies that constrain both visual perception and symbolic inference.
* **Literature Anchors:** Winston et al. (1987, taxonomy of part-whole relations); Bateman et al. (2010, linguistic and spatial ontologies); qualitative spatial/temporal reasoning and mereotopology.
* **Cross-Links:**
  * Directly grounds visual decompositions in [**KDD-07**](#kdd-07-hierarchy-aware-vision-language-explanation) (Hierarchy-Aware Vision-Language Explanation).
  * Provides structural backbones for [**KDD-08**](#kdd-08-multimodal-ontology-learning-systems) (Multimodal Ontology Learning) and [**KDD-12**](#kdd-12-neurosymbolic-and-ontology-aware-reasoning) (Neurosymbolic Reasoning).

---

# KDD-07: Hierarchy-Aware Vision-Language Explanation

* **Division Tags:** [[CV]](https://github.com/kddresearch/public_releases/tree/main/CV) • [[NL]](https://github.com/kddresearch/public_releases/tree/main/NL)
* **Core Idea:** Computer vision and vision-language systems that exploit explicit part-whole hierarchies and domain semantics to generate verifiable explanations, grounded captions, and structural diagrams.
* **Scientific Context & Explanation:** Standard contrastive vision-language models (such as CLIP) align global image and text embeddings but frequently fail on compositional attribute binding, fine-grained taxonomic distinctions, and spatial relations. Spanning document layout analysis, agricultural remote sensing, biomechanical video analysis, and species identification, this theme couples deep visual encoders with hierarchical scene and part graphs to produce human-verifiable visual explanations.
* **Literature Anchors:** Radford et al. (2021, CLIP contrastive pretraining); Johnson et al. (2017, scene graphs and visual reasoning); fine-grained visual categorization and explainable computer vision.
* **Cross-Links:**
  * Operationalizes compositional structures from [**KDD-06**](#kdd-06-part-whole-hierarchies-for-qualitative-and-mixed-reasoning).
  * Connects with multiscale saliency in [**KDD-16**](#kdd-16-multiresolution-gradients-for-saliency-and-explanation) and cross-modal constraints in [**KDD-14**](#kdd-14-multimodality-as-a-unifying-constraint).

---

# KDD-08: Multimodal Ontology Learning Systems

* **Division Tags:** [[NL]](https://github.com/kddresearch/public_releases/tree/main/NL) • [[CV]](https://github.com/kddresearch/public_releases/tree/main/CV) • [[ST]](https://github.com/kddresearch/public_releases/tree/main/ST)
* **Core Idea:** Inducing, aligning, and expanding formal ontologies jointly from text, speech, vision, and structured metadata, unifying symbolic structure induction with dense representation learning.
* **Scientific Context & Explanation:** Hand-crafted ontologies provide rigorous logical semantics but suffer from knowledge-acquisition bottlenecks when confronted with rapidly evolving real-world domains (such as emerging illicit-drug terminology, code-mixed social speech, or ecological field observations). This theme combines weak supervision, silver-standard query synthesis, and multimodal embeddings to discover candidate concepts and ground them into verifiable ontological schemas.
* **Literature Anchors:** Chen et al. (2020, multimodal knowledge graph construction);
