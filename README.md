# Hidayet Allah Yaakoubi

**Biomedical engineering student (expected 2028) · Medical imaging systems · AI for imaging · Device regulation & risk**
<<<<<<< HEAD
Tunis, Tunisia · [Portfolio](https://hidaayet.github.io/Hidayet_Yaakoubi.github.io/) · [LinkedIn](https://www.linkedin.com/in/hideya-allah-yaakoubi-5b1975391) · [Email](mailto:enghideya@gmail.com)
=======
Tunis, Tunisia
>>>>>>> b26cd35d82653df4722d78c047bb4d9a90fcffa0

I work on medical imaging systems end to end: how devices acquire images, what those images actually represent, and how they are processed and checked. Across hospital and biomedical-maintenance internships (2024–2026) I worked hands-on with imaging equipment; alongside that I build and evaluate AI models for medical images, and I've completed training in EU MDR, ISO 13485 and ISO 14971.

I report results with the dataset, split and limitations next to the number — the way a reviewer would want them.

**Currently:** CT quality-assurance drift monitoring (RadFlow), and a mini regulatory file for the retinal detector.
**Open to:** [research collaboration / internship / whatever you're actually looking for — edit this line]

---

## Imaging projects

| Project | What it does | Result | Status |
|---|---|---|---|
| [**Retinal Disease Detector**](https://github.com/Hidaayet/retinal-disease-detector) · [Live demo](https://huggingface.co/spaces/hidayet-yaakoubi/retinal-disease-detector) | Diabetic retinopathy grading (0–4) from fundus images — EfficientNet-B3, APTOS 2019 (3,662 images) | QWK **0.9053** · accuracy **83.6%** (internal validation split) | Deployed |
| [**CT Organ Reconstruction**](https://github.com/Hidaayet/ct-organ-reconstruction) | HU thresholding → morphological cleanup → marching cubes → STL meshes of bone, lungs, liver, kidneys | Pipeline demo on a synthetic CT volume; DICOM loading on real data | Complete (demo) |

**On the retinal detector's numbers.** 80/20 stratified split of APTOS 2019 (2,929 / 733, seed 42), no held-out test set, best epoch (13/15) selected on that same validation split — so the scores are optimistic and not comparable to the competition's private leaderboard. Weakest class: severe DR (F1 0.36, n = 39). Research project, not a medical device, not clinically validated. Full methodology in the [repo README](https://github.com/Hidaayet/retinal-disease-detector).

**On the CT pipeline.** Reconstruction runs on a synthetic volume with threshold-based segmentation, so it demonstrates the pipeline, not a validated segmentation method.

---

## Other work

| Project | What it shows | Result | Status |
|---|---|---|---|
| [**Motor Imagery BCI**](https://github.com/Hidaayet/motor-imagery-bci) | EEG preprocessing (MNE) + EEGNet in PyTorch, BCI Competition IV Dataset 2a | Test accuracy **63.8%**, κ **0.519** (single subject A01) † | Research prototype |
| [**CRISPR Off-Target Predictor**](https://github.com/Hidaayet/crispr-off-target-predictor) | Transformer encoder on guide/site pairs, GUIDE-seq data | AUC **0.9711** · accuracy **96.5%** † | Complete |
| [**Drug–Target Interaction GNN**](https://github.com/Hidaayet/drug-target-interaction-gnn) | Graph Attention Network on RDKit molecular graphs, ChEMBL / BindingDB | AUC **0.7630** † | Exploratory |
| **EMG-controlled robotic hand** | Wearable armband reads forearm EMG and wirelessly drives a 3D-printed hand in real time — sensors, acquisition, wireless control | Working prototype | Prototype (repo private) |

† Split, class balance and known limitations are documented in each repo README. For the BCI project that includes normalization computed before the split (leakage), no validation set, and a single subject — so 63.8% is the number to quote, not the 72.4% peak seen on the test set during training.

---

## Regulatory and quality training

Certificates of completion, SkillMed, September 2026: **EU MDR** (Regulation (EU) 2017/745), **ISO 13485:2016** (QMS for medical devices), **ISO 14971:2019** (risk management). These are training courses, not professional certifications — I'm applying them to my own projects, starting with the retinal detector's mini regulatory file.

---

## Technical foundation

- **Modeling:** PyTorch · PyTorch Geometric · scikit-learn · NumPy · SciPy · RDKit · Hugging Face Spaces
- **Imaging & signals:** DICOM · SimpleITK · OpenCV · scikit-image · MNE · Matplotlib
- **Engineering:** Python · Flask · Docker · Git · Jupyter · MATLAB · STM32 / embedded systems

Also from coursework and labs: biomedical instrumentation, digital filtering and biomedical signal processing.

---

## Background

- **ISTMT (Higher Institute of Medical Technologies of Tunis)** — Engineer's degree in biomedical engineering, 2023 – expected 2028
- **CETMBI, Tunis** — internship, June – October 2026
- **Hôpital Militaire Principal d'Instruction de Tunis** — internship, June – July 2025
- **Centre de Traumatologie et des Grands Brûlés** — internship, June – July 2024
- UNESCO-SIGHT Ambassador 2026 · IEEE ISTMT Student Branch

## Contact

<<<<<<< HEAD
[Portfolio](https://hidaayet.github.io/Hidayet_Yaakoubi.github.io/) · [LinkedIn](https://www.linkedin.com/in/hideya-allah-yaakoubi-5b1975391) · [Email](mailto:enghideya@gmail.com)
=======
[LinkedIn](https://www.linkedin.com/in/hideya-allah-yaakoubi-5b1975391) · [Email](mailto:enghideya@gmail.com)
>>>>>>> b26cd35d82653df4722d78c047bb4d9a90fcffa0
