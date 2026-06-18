# Q-M-O Decision Tree Simulator

**Interactive framework for interpreting "improvement" in animal models of Alzheimer's disease and dementia.**

[![Access the Tool](https://img.shields.io/badge/Access_the_Simulator-Live_Web_App-indigo?style=for-the-badge)](https://umutsimsekci.github.io/qmo-simulator)

## Overview
This repository hosts the **Q-M-O (Question-Model-Outcome) Decision Tree Simulator**, an interactive web-based tool designed to accompany our conceptual review article: 

> **"From Pathology to Network Failure: A Question-Model-Outcome Framework for Interpreting Animal Models of AD-Related and Dementia-Relevant Mechanisms"** 
> *Umut Şimşekçi & Yıldırım Cesaretli (2026)*

Animal models are essential for studying dementia, but interpreting a simple behavioral "improvement" can be challenging. Is the effect merely symptomatic, or does it represent true disease modification and network preservation? 

This simulator translates the theoretical framework from our manuscript into a practical, step-by-step assessment tool.

## Features
- **Progressive Evaluation:** Step-by-step guidance covering biological modifiers, target engagement, appropriate timecourses, circuit preservation, trajectory changes, and biomarker concordance.
- **Translational Confidence Score:** Automatically calculates a score (0-100) reflecting the strength of the clinical/translational claim.
- **Bounded Inferences:** Provides explicit boundaries on what can legitimately be claimed (e.g., warning against "neuroprotection" claims if only histological data is present).
- **Publication Guidance:** Generates real-time tips for manuscript drafting to avoid over-interpretation and address common reviewer concerns.
- **AI-Assisted Drafting:** Uses an integrated AI module to propose an academic paragraph for the *Discussion* or *Limitations* section based on the user's specific inputs.

## How to Use
You do not need to install anything or write any code to use this tool. 
Simply visit the live link: **[Launch the Q-M-O Simulator](https://umutsimsekci.github.io/qmo-simulator)**

## Data & Code Availability
The entire simulator runs locally in your browser. It is built using HTML, React (via Babel standalone), and Tailwind CSS. The source code (`index.html`) is open and available in this repository.

## Citation
If you use this framework or simulator in your research or journal clubs, please cite our main manuscript:

```bibtex
@article{SimsekciCesaretli2026,
  title={From Pathology to Network Failure: A Question-Model-Outcome Framework for Interpreting Animal Models of AD-Related and Dementia-Relevant Mechanisms},
  author={{\c{S}}im{\c{s}}ek{\c{c}}i, Umut and Cesaretli, Y{\i}ld{\i}r{\i}m},
  journal={Frontiers in Neuroscience (or relevant journal)},
  year={2026}
}
