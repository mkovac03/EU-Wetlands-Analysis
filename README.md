
**Description:** This repository contains workflows, data, and scripts used for the study **"Europe's Wetlands Reveal High Carbon Storage Despite Human Disturbances"**. 

## Abstract

Wetlands are vital for mitigating climate change due to their carbon storage, but historical land use changes have caused carbon losses and increased CO2 emissions. To address this, the European Union aims to restore 30% of degraded wetlands within Europe by 2030. Identifying restoration needs and prioritizing wetlands with high carbon stocks require detailed continental-scale inventories of wetland ecosystems. However, existing wetland datasets are unsuitable for detailed assessments of wetland areas, carbon storage, and related human disturbances across Europe. Here, utilizing 10-meter satellite data with machine learning, we achieved a 94±0.5% accuracy in mapping six wetland types across Europe in 2018. Despite considerable carbon storage losses to land-use disturbances (up to 26%), our findings reveal a substantial carbon pool in wetlands, with a natural variability of 11.07 Gt to 49.09 Gt of CO2 equivalent across key types – up to 45% higher than previous estimates. We provide country-level carbon storage area estimates to meet restoration targets, highlighting the uneven distribution of restoration needs and opportunities across Europe.

**Authors:** Gyula Mate Kovács, Xiaoye Tong, Stefan Oehmcke, Dimitri Gominski, Stéphanie Horion, Christin Abel, Eva Ivits, Guy Schurgers, Bo Elberling, Alexander Prishchepov, Sebastian van der Linden, Susan Page, Alexandra Barthelmes, and Rasmus Fensholt.

## Repository Structure

- `data/`: Contains necessary data files, including GeoPackage and CSV files used for the analysis of wetland areas and carbon storage.
- `notebooks/`: Jupyter notebooks for various stages of the analysis.
  - **Training Data Generation**: Notebook for generating training datasets for wetland mapping.
  - **XGBoost Model**: Notebook for training an XGBoost model for wetland classification.
  - **Accuracy Assessment and Area Estimation**: Notebook for assessing model accuracy and estimating wetland areas.
  - **Image Extraction**: Notebook for extracting image data used in the analysis.
  - **Prediction**: Notebook for applying the trained model to make predictions on wetland presence and carbon storage.
- `outputs/`: Generated outputs from the analysis, including confusion matrices, sample points, and accuracy assessment metrics.

![Example Image](fig1.png)

## Contact

For questions, collaborations, or further information on the study, please contact Dr. Gyula Mate Kovacs at [gmk@ign.ku.dk].
