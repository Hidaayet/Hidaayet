# AI for medical imaging

<p align="center">
  <a href="https://hidaayet.github.io/Hidayet_Yaakoubi.github.io/"><img src="https://img.shields.io/badge/Portfolio-Website-blue?style=for-the-badge&logo=google-chrome&logoColor=white" alt="Portfolio"/></a>
  <a href="https://www.linkedin.com/in/hidayet-allah-yaakoubi-5b1975391/"><img src="https://img.shields.io/badge/LinkedIn-Connect-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
  <a href="mailto:enghideya@gmail.com"><img src="https://img.shields.io/badge/Email-Contact-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/></a>
</p>

I'm Hidayet. I build deep-learning systems for medical images and take them from raw data to a deployed demo, with the evaluation and regulatory groundwork a real device needs.

- **Imaging, end to end.** How devices acquire images, what the pixels represent, and how to process them: fundus photography, CT, EEG.
- **Evidence before claims.** Stratified splits, confidence intervals, error analysis by class and lifecycle stage, and leakage checks. My repos state what the model cannot do.
- **Regulatory fluency.** Trained in EU MDR, ISO 13485 and ISO 14971, and applying them: I'm writing a mini regulatory file for my retinal detector and building CT quality-assurance drift monitoring.

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

## Featured work

### [Retinal Disease Detector](https://github.com/Hidaayet/retinal-disease-detector) &nbsp;·&nbsp; [Live demo](https://huggingface.co/spaces/hidayet-yaakoubi/retinal-disease-detector)

Diabetic retinopathy grading (0–4) from fundus photographs. EfficientNet-B3 fine-tuned on APTOS 2019, served through a Flask app in Docker with Grad-CAM attention maps, and deployed publicly.
**QWK 0.905 · 83.6% accuracy** on a stratified validation split. The README reports per-class results, the weak class (severe DR) and a known failure mode on laser-treated eyes.

### [Predictive Engine Maintenance](https://github.com/Hidaayet/Predictive_Engine_Maintenance)

Remaining-useful-life prediction on NASA C-MAPSS with XGBoost and SQL-built features, turned into a maintenance-cost decision.
**RMSE 15.3 cycles on FD001**, against 40.2 for the naive baseline. A threshold policy calibrated on its own fleet was **34–44% cheaper** than a tuned fixed interval at a 10:1 failure-to-planned cost ratio. The same policy moved to another fleet without recalibration lost to it. That is the finding, backed by 95% confidence intervals and 40 repeated splits. Simulated data, assumed costs.

### [Olist E-commerce Analytics](https://github.com/Hidaayet/olist-ecommerce-analytics)

About 100,000 orders from raw CSVs to a validated PostgreSQL warehouse, advanced SQL, Python segmentation, a Power BI model and a 7-page executive report. One command rebuilds everything in about 90 seconds, with 20 data-validation checks.
**97% of customers never reorder**, late orders average **2.57 stars vs 4.29**, and a naive join would have overstated revenue by 4.5%.

### [CT Organ Reconstruction](https://github.com/Hidaayet/ct-organ-reconstruction)

HU thresholding → morphological cleanup → marching cubes → printable STL meshes of bone, lungs, liver and kidneys, demonstrated on a synthetic CT volume.

### Also built

[Motor-imagery BCI](https://github.com/Hidaayet/motor-imagery-bci) (EEGNet on BCI Competition IV 2a, single-subject, with its preprocessing leakage documented) · [CRISPR off-target predictor](https://github.com/Hidaayet/crispr-off-target-predictor) (Transformer proof of concept on a small GUIDE-seq set)

## Get in touch

Working on medical imaging, AI, or device regulation? I'd like to hear about it: [enghideya@gmail.com](mailto:enghideya@gmail.com)

<p align="center">Updated November 2026</p>