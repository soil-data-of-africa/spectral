# AI for Soil Property Prediction from MIR Spectra  

[![NumPy](https://img.shields.io/badge/NumPy-4DABCF?logo=numpy&logoColor=fff)](#)
[![Pandas](https://img.shields.io/badge/Pandas-150458?logo=pandas&logoColor=fff)](#)
[![Matplotlib](https://custom-icon-badges.demolab.com/badge/Matplotlib-71D291?logo=matplotlib&logoColor=fff)](#)
[![Sklearn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=fff)](#)

This repository contains a Jupyter Notebook demonstrating how to build AI models for predicting soil properties using Mid-Infrared (MIR) spectral data. The tutorial progresses through three levels of proficiency: Beginner, Intermediate, and Expert, leveraging the **[spectraxai](https://github.com/i-bec-org/spectra-xai)** library.  

# Table of contents

- [AI for Soil Property Prediction from MIR Spectra](#ai-for-soil-property-prediction-from-mir-spectra)
- [Table of contents](#table-of-contents)
- [Overview](#overview)
  - [🟢 Beginner Level](#-beginner-level)
  - [🔵 Intermediate Level](#-intermediate-level)
  - [🔴 Expert Level](#-expert-level)
- [Requirements (advanced)](#requirements-advanced)
- [Getting Started](#getting-started)
- [License](#license)
- [Acknowledgments](#acknowledgments)


# Overview  

Using AI and machine learning to predict key soil physicochemical properties from infrared spectra is crucial for sustainable soil management. These methods significantly reduce the cost and time required for traditional lab analyses while enabling large-scale monitoring. By leveraging AI-driven predictions, we can make informed decisions to safeguard and protect our soils, ensuring their health and productivity for future generations.

This repository uses **spectraxai** to develop the models, a spectral processing package designed to:  
- Visualize spectral data.  
- Apply various preprocessing techniques.  
- Train machine learning models for soil property prediction.  
- Provide explainability for model results.  

This tutorial introduces key concepts in three levels:  

## 🟢 Beginner Level  
- Basic ML pipeline using spectral data, including simple data visualization.
- Training a simple model to predict soil properties.  

## 🔵 Intermediate Level  
- Cross-validation with 5-fold splitting.  
- Experimenting with different preprocessing techniques (e.g., Standard Normal Variate).  
- Comparing multiple machine learning algorithms.  

## 🔴 Expert Level  
- Pre Hoc analysis: Investigating feature correlations using Pearson’s correlation.  
- Post Hoc analysis: Model explainability techniques.  

# Requirements (advanced)

To run the notebook, it's necessary to install the spectraxai package, which is currently available on Github only. A beginner friendly guide is provided below.

# Getting Started

We recommend using a new conda environment to keep everything organized.

1. Install anaconda from the [official guide](https://www.anaconda.com/docs/getting-started/anaconda/install).

2. Clone the repository and navigate to the project folder:
```bash
git clone https://github.com/soil-data-of-africa/spectral
cd spectral
```

3. Create the spectral environment from the provided file and activate it:
```bash
conda env create -f environment.yml
conda activate spectral
```

4. Install spectraxai:
```bash
git clone https://github.com/i-bec-org/spectra-xai.git
cd spectra-xai
git checkout v1.0.0
python setup.py install
cd ..
```

5. Open the notebook using Jupyter Lab:
```bash
jupyter-lab
```
and double click to open the .ipynb file.

6. Run the notebook to explore the ML pipeline for soil spectroscopy.

# License

This repository is released under the CC0-1.0 License (Public Domain Dedication).

# Acknowledgments

This notebook was developed under the [Soils4Africa](https://www.soils4africa-h2020.eu/) project that has received funding from the European Union’s Horizon 2020 research and innovation programme under Grant Agreement Νο 862900.

![Soils4Africa](https://www.soils4africa-h2020.eu/serverspecific/soils4africa/images/Template/logo.png?t=2) ![EU-flag](https://upload.wikimedia.org/wikipedia/commons/thumb/b/b7/Flag_of_Europe.svg/320px-Flag_of_Europe.svg.png)

This project utilizes [spectraxai]((https://github.com/i-bec-org/spectra-xai)), an open-source library for spectral data processing.