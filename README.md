# I build AI for medical imaging

<p align="center">
  <a href="https://hidaayet.github.io/Hidayet_Yaakoubi.github.io/"><img src="https://img.shields.io/badge/Portfolio-Website-blue?style=for-the-badge&logo=google-chrome&logoColor=white" alt="Portfolio"/></a>
  <a href="https://www.linkedin.com/in/hidayet-allah-yaakoubi-5b1975391/"><img src="https://img.shields.io/badge/LinkedIn-Connect-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
  <a href="mailto:enghideya@gmail.com"><img src="https://img.shields.io/badge/Email-Contact-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/></a>
</p>

Hi, I'm Hidayet, a biomedical engineering student at ISTMT in Tunis (expected 2028). I work on imaging systems end to end: how devices acquire images, what they represent, and how they are processed. I build AI models for medical images, and I have completed training in EU MDR, ISO 13485, and ISO 14971.

Right now I'm working on CT quality-assurance drift monitoring and a mini regulatory file for my retinal detector. Alongside that I do data analytics and machine learning on engineering and business data.

## Stack

<p align="left">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white" />
  <img src="https://img.shields.io/badge/scikit_learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white" />
  <img src="https://img.shields.io/badge/XGBoost-337AB7?style=for-the-badge" />
  <img src="https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white" />
  <img src="https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white" />
  <img src="https://img.shields.io/badge/SciPy-8CAAE6?style=for-the-badge&logo=scipy&logoColor=white" />
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white" />
  <img src="https://img.shields.io/badge/Power_BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black" />
  <img src="https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white" />
  <img src="https://img.shields.io/badge/Docker-2CA5E0?style=for-the-badge&logo=docker&logoColor=white" />
</p>

## Featured Projects

### Medical imaging

- **[Retinal Disease Detector](https://github.com/Hidaayet/retinal-disease-detector)**: diabetic retinopathy grading (0–4) from fundus images with EfficientNet-B3, deployed as a Flask app. QWK 0.905 and 83.6% accuracy on an internal 20% validation split (no separate test set; severe DR is the weakest class). ([Live demo](https://huggingface.co/spaces/hidayet-yaakoubi/retinal-disease-detector))
- **[CT Organ Reconstruction](https://github.com/Hidaayet/ct-organ-reconstruction)**: HU thresholding → morphological cleanup → marching cubes → STL meshes of bone, lungs, liver and kidneys, demonstrated on a synthetic CT volume.

### Data and analytics

- **[Olist E-commerce Analytics](https://github.com/Hidaayet/olist-ecommerce-analytics)**: about 100,000 orders taken from raw CSVs to a validated PostgreSQL warehouse, advanced SQL, Python segmentation, a Power BI model and an executive report. 97% of customers never reorder, and late orders average 2.57 stars against 4.29 on time.
- **[Predictive Engine Maintenance](https://github.com/Hidaayet/Predictive_Engine_Maintenance)**: remaining-useful-life prediction on NASA C-MAPSS (XGBoost, PostgreSQL features) with a maintenance-cost simulation. A RUL-threshold policy calibrated on its own fleet was 34–44% cheaper than a tuned fixed interval at a 10:1 failure-to-planned cost ratio, but a threshold moved between fleets without recalibration lost to it. Simulated data, assumed costs.

### Signals and biology (learning projects)

- **[Motor Imagery BCI](https://github.com/Hidaayet/motor-imagery-bci)**: EEGNet in PyTorch on BCI Competition IV 2a. 63.8% accuracy, κ 0.519 on one subject (A01) and one 80/20 split. The README documents a normalisation leakage and what I would fix.
- **[CRISPR Off-Target Predictor](https://github.com/Hidaayet/crispr-off-target-predictor)**: Transformer encoder over guide/site pairs, trained on 54 published GUIDE-seq pairs plus rule-based synthetic augmentation. A proof of concept, not a validated predictor.

## Get in Touch

Building something at the intersection of medical imaging, AI, and device regulation? Reach me at [enghideya@gmail.com](mailto:enghideya@gmail.com).

<p align="center">Updated November 2026</p>