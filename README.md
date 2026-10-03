# Hidayet Allah Yaakoubi

**Biomedical engineering student (expected 2027) · Medical imaging systems · AI for imaging · Device regulation & risk**
Tunis, Tunisia

I focus on medical imaging systems: how the devices acquire images, what those images represent, and how they are processed and checked. During hospital and biomedical-maintenance internships (2024–2026) I worked with imaging equipment. On top of that I build AI models for medical images, and I have completed training in EU MDR, ISO 13485 and ISO 14971.

I report results the way a reviewer would want them: the dataset, the split and the limitations sit next to the number.

---

## Imaging projects

| Project | What it does | Result | Status |
|---|---|---|---|
| [**Retinal Disease Detector**](https://github.com/Hidaayet/retinal-disease-detector) · [Live demo](https://huggingface.co/spaces/hidayet-yaakoubi/retinal-disease-detector) | Grades diabetic retinopathy (0–4) from fundus images with EfficientNet-B3, trained on APTOS 2019 (3,662 images) | QWK **0.9053**, accuracy **83.6%** on an internal validation split | Complete, deployed |
| [**CT Organ Reconstruction**](https://github.com/Hidaayet/ct-organ-reconstruction) | HU thresholding → morphological cleanup → marching cubes → STL meshes of bone, lungs, liver and kidneys | Pipeline demo on a synthetic CT volume; DICOM loading shown on real data | Complete (demo) |

**In progress:** CT quality-assurance drift monitoring (repository not yet public).

### How to read these numbers

**Retinal Disease Detector.** 80/20 stratified split of APTOS 2019 (2,929 train / 733 validation, seed 42). There is no separate test set and no cross-validation, and the best epoch (13 of 15) is reported on that same validation split, so treat the scores as optimistic and not comparable to the competition's private leaderboard. The weakest class is severe DR (F1 0.36, n = 39). This is a research project, not a medical device, and it has not been clinically validated.

**CT Organ Reconstruction.** The reconstruction runs on a synthetic volume with threshold-based segmentation. No segmentation accuracy is reported, so this demonstrates the pipeline and not a validated method.

---

## Regulatory and quality training

Certificates of completion, SkillMed, September 2026:

- EU MDR: Regulation (EU) 2017/745
- ISO 13485:2016: Quality Management System for Medical Devices
- ISO 14971:2019: Risk Management for Medical Devices

These are training courses, not professional certifications. I am applying them to my own projects, starting with a mini regulatory file for the retinal detector (in progress).

---

## Other work

| Project | What it shows | Notes |
|---|---|---|
| **EMG-controlled robotic hand** | A wearable armband reads forearm muscle signals (EMG) and wirelessly controls a 3D-printed robotic hand in real time. Sensors, signal acquisition and wireless control. | Prototype. Repository is private while it is being cleaned up. |
| [**Motor Imagery BCI**](https://github.com/Hidaayet/motor-imagery-bci) | EEG preprocessing (MNE) and EEGNet in PyTorch on BCI Competition IV Dataset 2a. | Single subject (A01), stratified 80/20 split (230 train / 58 test). **Final test accuracy 63.8%, κ 0.519.** A peak of 72.4% was recorded on the test set during training, so it is selection-biased and not the headline. Known limitations: normalization computed before the split (leakage), no validation set, one subject. Research prototype, not under active development. |
| [**CRISPR Off-Target Predictor**](https://github.com/Hidaayet/crispr-off-target-predictor) | Transformer encoder on guide/site sequence pairs, GUIDE-seq data. | AUC 0.9711, accuracy 96.5%. Train/test split, class balance and AUPRC: **[FILL IN BEFORE PUBLISHING]** |
| [**Drug–Target Interaction GNN**](https://github.com/Hidaayet/drug-target-interaction-gnn) | Graph Attention Network on RDKit molecular graphs, ChEMBL / BindingDB. | AUC 0.7630. Exploratory. Data subset and split: **[FILL IN BEFORE PUBLISHING]** |

---

## Technical foundation

**Used in the projects above**
Python · PyTorch · PyTorch Geometric · MNE · OpenCV · scikit-image · scikit-learn · NumPy · SciPy · RDKit · DICOM · Matplotlib · Flask · Docker · Git · Jupyter · Hugging Face Spaces

**Studied and used in university coursework and labs**
STM32 and embedded systems · biomedical instrumentation · digital filtering and biomedical signal processing · MATLAB · SimpleITK

---

## Background

- Higher Institute of Medical Technologies of Tunis (ISTMT): Engineer's degree in biomedical engineering, 2023 – expected 2027
- Centre d'Etude Techniques de Maintenance Biomédicale et Hospitalière (Tunis): internship, June – October 2026
- Hôpital Militaire Principal d'Instruction de Tunis: internship, June – July 2025
- Centre de Traumatologie et des Grands Brûlés: internship, June – July 2024
- UNESCO-SIGHT Ambassador 2026, IEEE ISTMT Student Branch

## Contact

[LinkedIn](https://www.linkedin.com/in/hideya-allah-yaakoubi-5b1975391) · [Email](mailto:enghideya@gmail.com)