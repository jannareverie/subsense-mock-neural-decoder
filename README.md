# Neural Intent Decoder (Mock Nanoparticle BCI)  
*Inspired by Subsense's Non-Surgical Brain-Computer Interface Technology*

This project simulates a neural intent decoding pipeline designed to reflect the challenges faced in developing real-time, non-invasive brain-computer interfaces (BCIs) such as those pioneered by **Subsense**.

---

## 🧠 Project Overview

This demo explores the core machine learning and signal processing workflow that could underlie a nanoparticle-based BCI system. It focuses on transforming raw biosignal streams into interpretable mental state predictions, enabling intuitive human-machine communication and future therapeutic interventions.

While Subsense’s proprietary signals may differ (e.g., optical or electrochemical recordings via biocompatible nanoparticles), this mock dataset assumes high-dimensional, multi-sensor biosignals to simulate the computational requirements of intent decoding.

---

## 🧪 Dataset Description

- Simulated multi-channel biosignals (shape: trials × time × sensors)
- Two intent labels: **Rest** and **Motor Imagery**
- Multiple synthetic "subjects" with added variability
- Data augmentations include:
  - Temporal jitter
  - Sensor dropout noise
  - Inter-subject variation

> Dataset: `mock_nanobci_dataset.npz`

---

## 🛠️ Core Workflow

- Preprocessing: Trial-wise and global normalization
- Windowing: Simulated streaming via sliding windows
- Feature Engineering: Flattened time-sensor windows
- Classification: Supervised ML pipeline (Logistic Regression)
- Post-hoc: ROC evaluation, interpretability scaffolding

---

## 🔁 Real-Time Decoder Simulation

The pipeline includes a real-time inference simulation using fixed-length windows over incoming signal data. This models how a future deployed system might continuously decode intent in response to brain activity in a feedback loop.

---

## 📂 Files

| File | Description |
|------|-------------|
| `Subsense Project Demo.ipynb` | Main notebook with pipeline implementation |
| `mock_nanobci_dataset.npz` | Clean synthetic signal dataset |
| `mock_nanobci_augmented.npz` | Augmented dataset with realistic challenges |
| `README.md` | Project overview and documentation |

---

## 💡 Motivation

This project was developed to demonstrate the practical skillset and scientific grounding needed for building robust neurotechnology systems.
- End-to-end biosignal ML pipelines
- Robust signal decoding under noise
- Cross-functional integration with neurotech and hardware teams

---

## 🧬 About Me

I’m a neuroscience researcher with experience in:
- Computational modeling of brain and biosignals
- Digital pathology and high-dimensional biological data
- Bridging code with clinical and biological insight

I’m excited about technologies that safely and meaningfully link the brain to the world—particularly those that are scalable, patient-centered, and visionary like Subsense’s.

---

## 🔗 Contact

📩 **jannareverie@gmail.com**  
🌐 [LinkedIn](https://www.linkedin.com/in/jannareverie/)
