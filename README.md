# 🔬 Neuro-Integrative Analysis: Fusing IKS Phenotyping with Digital Biomarkers for Stage-0 Dementia

> **Status:** Research Abstract Submitted to **AAIC 2026** (Alzheimer's Association International Conference).
> **Objective:** To redefine early-stage dementia screening by integrating Ayurvedic Prakriti (IKS) with modern AI.

## 📚 Research Context (Based on AAIC Submission)
My preliminary research, titled *"A Two-stage AI/ML Framework Integrating Ayurvedic Phenotyping and Clinical Data for Early Alzheimer's Risk Detection,"* focuses on:
* **Ayurvedic Integration:** Using **Prakriti** (Vata, Pitta, Kapha) to capture subtle physiological variations.
* **Two-Stage Pipeline:** Fusing constitutional profiling with clinical and lifestyle data for better risk segmentation.
* **Technical Feasibility:** Initial validation using synthetic datasets to prove the logic of culturally-grounded diagnostics.

##  Technical Implementation & Evolution
This research builds upon the functional foundation of my initial prototype, which proved the technical viability of the Ayu-Allo fusion.

Initial Codebase: [!https://github.com/Avgohil/fusion-care-alzheimer-ml]

Core Stack: Python, FastAPI, Scikit-learn, MongoDB.

Key Achievement: Successfully demonstrated that adding Prakriti-derived phenotypes improves risk segmentation accuracy beyond standard clinical factors.

## ⚠️ Identified Research Gaps 
While the AAIC abstract proves the technical feasibility, it highlights a critical **Scientific Challenge**:

1. **Phenotypic Overlap:** A naturally restless **Vata-dominant** person exhibits traits (sleep variability, rapid speech) that overlap with early-stage Alzheimer’s.
2. **The Noise Problem:** Current AI models might flag healthy Vata individuals as "High Risk" due to this overlap. 
3. **Requirement:** We need a **Longitudinal Baseline** (14-15 days) to distinguish between a person's natural state (*Prakriti*) and pathological decline (*Vikriti*).

## Proposed Methodology (The Research Roadmap)
To address the phenotypic overlap and improve diagnostic precision, the next phase of this research focuses on a Tri-Layered Validation Framework:

Layer 1: Temporal Baseline Calibration (The 14-Day Rule)
Instead of a "One-Point Assessment," we propose a passive observation period.

Mechanism: The system records a user's natural behavioral fluctuations (sleep patterns, activity levels) for 14 days to establish a Personalized Prakriti Baseline.

Goal: To ensure that a "Vata-restless" person is not compared against a "Kapha-stable" average, but against their own unique physiological norm.

Layer 2: Multimodal Biomarker Fusion (Ayu-Allo Correlation)
We will cross-verify Ayurvedic functional shifts (Vikriti) with objective Allopathic ground truths:

Vata Imbalance (Restlessness) <---> HRV (Heart Rate Variability) & Sleep Latency.

Pitta Imbalance (Inflammation) <---> Body Temperature & Stress Biomarkers.

Kapha Imbalance (Lethargy) <---> Physical Activity Slopes & Cognitive Speed.

Layer 3: Privacy-Preserving AI (Federated Learning)
Recognizing the sensitivity of medical and IKS data, we are moving towards an On-Device AI model.

Approach: Using Federated Learning to train models locally on the user's smartphone, ensuring that raw health data never leaves the device.

## 🎓 Recognition & References
* **Conference Submission:** *A Two-stage AI/ML Framework Integrating Ayurvedic Phenotyping and Clinical Data for Early Alzheimer's Risk Detection*, Submitted to **AAIC 2026**.
* **Key Literature:**
  1. Dagum, P. (2018). *Digital biomarkers of cognitive function.*
  2. Kurunji, V. (2022). *Ayurvedic Prakriti and its correlation with modern genomic and physiological markers.*
  
