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
  🤖 <a href="https://github.com/kddresearch/public_releases/tree/main/RL"><strong>Reinforcement Learning [RL]</strong></a> &nbsp;|&nbsp;
  🛡️ <a href="https://github.com/kddresearch/public_releases/tree/main/ST">Secure &amp; Trustworthy AI [ST]</a> &nbsp;|&nbsp;
  🌾 <a href="https://github.com/kddresearch/public_releases/tree/main/OA">Other Applied AI [OA]</a>
</div>

<div align="center">
 <h1>🤖 KDD Lab — Reinforcement Learning Division [RL]</h1>
 <p>
 <strong>Project:</strong> Sequential Decision-Making, Causal Control &amp; Inverse RL ([RL] Public Releases) | <strong>Principal Investigator:</strong> Prof. William H. Hsu<br>
 <strong>Academic Profiles:</strong> <a href="https://scholar.google.com/citations?hl=en&user=JQoJRcIAAAAJ">Google Scholar</a> • <a href="https://orcid.org/0000-0002-2950-6246">ORCID</a> • <a href="https://dblp.org/pid/21/1034.html">DBLP</a> • <a href="https://openreview.net/profile?id=~William_Hsu1">OpenReview</a><br>
 <strong>Status:</strong> ACTIVE | <strong>Core Tech:</strong> PyTorch, Gymnasium / PettingZoo, Multi-Objective MARL (MOMARL), Inverse RL, Bayesian Decision Networks
 </p>
</div>

<hr>

## 📖 Overview

The **Reinforcement Learning `[RL]` Division** provides the **decision-making and autonomous control layer** of the K-State KDD Lab's research architecture. Focusing on sequential decision-making under uncertainty where state, reward, and policy representations are structured, multi-objective, or non-stationary, the `[RL]` division emphasizes **causality over pure correlation**, counterfactual reasoning, and the interpretability of learned policies.

Key scientific concerns in `[RL]` include:
1. **Rich Reward & Policy Representations:** Learning reward structures (via Inverse Reinforcement Learning and preference modeling) and policy representations that preserve multidimensional latent objectives without collapsing under scalarization.
2. **Causal & Counterfactual Decision Support:** Integrating Bayesian decision networks and structural causal models to reason explicitly about interventions, temporal discounting (including hyperbolic discounting), and non-stationary environment dynamics.
3. **Closed-Loop Active Perception & Robotics:** Coupling multi-agent reinforcement learning with real-time visual and multimodal sensing for precision agriculture, autonomous robotics, and dynamic heuristic selection.

### 🎯 Tagged Research Themes (`kdd_16_research_themes.md`)

The `[RL]` division anchors or co-anchors **5 of the KDD Lab's 16 canonical research themes**:

| Theme ID | Canonical Theme Anchor | Role & Inter-Theme Cross-Links in `[RL]` |
| :--- | :--- | :--- |
| [**`KDD-01`**](https://github.com/kddresearch/public_releases/blob/main/kdd_16_research_themes.md#kdd-01-efficient-foundation-models-for-sustainable-machine-learning) | **Efficient Foundation Models for Sustainable ML** | Resource-bounded policy inference, model compression for onboard robotics/UAV control, and RL-guided dynamic heuristic selection. |
| [**`KDD-09`**](https://github.com/kddresearch/public_releases/blob/main/kdd_16_research_themes.md#kdd-09-end-to-end-trusted-multimodal-learning-systems) | **End-to-End Trusted Multimodal Learning Systems** | Closed-loop perception–reasoning–action pipelines integrating active learning and active perception with [**KDD-14**](https://github.com/kddresearch/public_releases/blob/main/kdd_16_research_themes.md#kdd-14-multimodality-as-a-unifying-constraint) and [**KDD-15**](https://github.com/kddresearch/public_releases/blob/main/KDD_15_RESEARCH_THEMES.md#kdd-15-rich-representations-for-reward-value-and-policy-learning). |
| [**`KDD-13`**](https://github.com/kddresearch/public_releases/blob/main/kdd_16_research_themes.md#kdd-13-causal-and-counterfactual-probabilistic-reasoning) | **Causal and Counterfactual Probabilistic Reasoning** | Bayesian decision networks and counterfactual policy evaluation informed by priors from [**KDD-05**](https://github.com/kddresearch/public_releases/blob/main/kdd_16_research_themes.md#kdd-05-trust-weighted-inference-and-evidence-aggregation) and symbolic constraints from [**KDD-12**](https://github.com/kddresearch/public_releases/blob/main/kdd_16_research_themes.md#kdd-12-neurosymbolic-and-ontology-aware-reasoning). |
| [**`KDD-14`**](https://github.com/kddresearch/public_releases/blob/main/kdd_16_research_themes.md#kdd-14-multimodality-as-a-unifying-constraint) | **Multimodality as a Unifying Constraint** | Multimodal state grounding combining visual, spatial, and symbolic observations in sequential control tasks. |
| [**`KDD-15`**](https://github.com/kddresearch/public_releases/blob/main/kdd_16_research_themes.md#kdd-15-rich-representations-for-reward-value-and-policy-learning) | **Rich Representations for Reward, Value, and Policy Learning** | Inverse RL, hyperbolic discounting, and multi-objective MARL (MOMARL) preserving Latent Objective State (LOS) dimensions alongside [**KDD-10**](https://github.com/kddresearch/public_releases/blob/main/kdd_16_research_themes.md#kdd-10-value-alignment-guardrails-and-information-extraction-completeness). |

<details>
 <summary><strong>📁 Associated Publications &amp; Repositories</strong></summary>
 <br>

 ### 📋 Research Thrusts &amp; Simulation Environments
 * **Inverse Reinforcement Learning for Behavioral Neuroscience (`CNAP IRL`)** — 📍 *Recovering latent reward structures and temporal discounting dynamics from animal and human behavioral trajectories*
 * **Multi-Objective Multi-Agent RL for Precision Agriculture (`RL4PrecisionAg` / `MOMARL`)** — *Coordinated UAV/UGV coverage, targeted weed management, and non-colliding trajectory optimization under stochastic weather constraints*
 * **Dynamic Heuristic Selection &amp; Agentic Planning** — *Reinforcement learning for meta-reasoning and algorithmic control*

 ### 🗄️ Public Repositories &amp; Portals
 * [`kddresearch/public_releases/RL`](https://github.com/kddresearch/public_releases/tree/main/RL) — 📍 Current division release directory
 * [`HuggingFace @KDDResearch`](https://huggingface.co/KDDResearch) — Public policy checkpoints and environment benchmarks
</details>

<hr>

## 🗂️ Repository Structure

| Directory / File | Description |
| :--- | :--- |
| `data/` | Trajectory logs, behavioral datasets, and environment configuration schemas. |
| `outputs/` | Pareto-front evaluations, reward recovery fidelity metrics, and policy rollouts. |
| `reference/` | MDP/MOMARL formal specifications and related literature. |
| `src/` | IRL, MOMARL, and causal decision-network implementations. |
| `README.md` | This file. |

<hr>

## 🚀 Quick Start & Execution

**1. Prerequisites**
* Python 3.11+, PyTorch, Gymnasium / PettingZoo
* Docker / Apptainer container specification (`Dockerfile` / `environment.yml` per project)

**2. Initialization**
```bash
git clone [https://github.com/kddresearch/public_releases.git](https://github.com/kddresearch/public_releases.git)
cd public_releases/RL
```

## 👥 Contributors & Citation

**Principal Investigator:** Prof. William H. Hsu ([@banazir](https://github.com/banazir) • [Google Scholar](https://scholar.google.com/citations?hl=en&user=JQoJRcIAAAAJ) • [ORCID](https://orcid.org/0000-0002-2950-6246) • [DBLP](https://dblp.org/pid/21/1034.html) • [OpenReview](https://openreview.net/profile?id=~William_Hsu1))

| Role | Name | Affiliation / Track |
| --- | --- | --- |
| **Director / PI** | Prof. William H. Hsu | K-State KDD Lab / CAIDS |
| **Division Researchers** | KDD Lab `[RL]` Graduate &amp; Undergraduate Research Team | CNAP IRL, RL4PrecisionAg, MOMARL |

**Citation:**
If you use code, models, or environments from the `[RL]` division in your research, please cite the relevant paper listed in the sub-project directory and reference the K-State KDD Lab:
```bibtex
@misc{kddresearch_rl_2026,
  author       = {Hsu, William H. and {K-State KDD Lab Reinforcement Learning Division}},
  title        = {{K-State KDD Lab Reinforcement Learning [RL] Public Releases}},
  year         = {2026},
  howpublished = {\url{[https://github.com/kddresearch/public_releases/tree/main/RL](https://github.com/kddresearch/public_releases/tree/main/RL)}}
}
```
