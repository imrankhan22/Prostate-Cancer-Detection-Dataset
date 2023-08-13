# Prostate Cancer Detection Dataset

This dataset supports the research article “Reasons for missing clinically significant prostate cancer by targeted magnetic resonance imaging/ultrasound fusion-guided biopsy” [1]. The dataset includes information about patients referred to the Department of Interventional and Diagnostic Radiology at the University Hospital Duesseldorf, Germany, for mp-MRI of the prostate. The dataset contains details on patient demographics, MRI protocols, biopsy results, and more.

## Table of Contents

- [Introduction](#introduction)
- [Dataset Description](#dataset-description)
  - [Patient Demographics](#patient-demographics)
  - [MRI Imaging](#mri-imaging)
  - [Biopsy Results](#biopsy-results)
  - [PI-RADS Classification](#pi-rads-classification)
- [PCa Detection Statistics](#pca-detection-statistics)
- [PCa Detection According to PI-RADS](#pca-detection-according-to-pi-rads)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Introduction

This repository contains a dataset that accompanies the research article focused on investigating the reasons for missing clinically significant prostate cancer using targeted magnetic resonance imaging (MRI)/ultrasound fusion-guided biopsy. The dataset provides valuable insights into patient characteristics, MRI evaluation, biopsy outcomes, and the effectiveness of different diagnostic techniques.

## Dataset Description

### Patient Demographics

- Total patients: 2,418
- Patients included in the analysis: 785
- Mean age: 65 ± 9 years
- Median PSA value: 8.1 ng/ml (Interquartile range: 5.9 - 12 ng/ml)
- Median prostate volume: 47 ml (Interquartile range: 33 - 66 ml)

### MRI Imaging

- Different 3T MRI scanners used (Magnetom Trio TIM: n=549, Skyra: n=90, Prisma: n=104, Siemens Healthcare GmbH, Germany; other: n=42)
- Coil configurations: 18-channel phased-array surface coil with 32-channel spine coil (n=681) or 60-channel phased-array surface coil with 30 elements anterior and posterior (n=104)
- Detailed mp-MRI protocol according to PI-RADS version 2

### Biopsy Results

- Complete subsequent MRI/US fusion-guided targeted (TB) and systematic (SB) biopsies analyzed: 785 patients
- Overall PCa detection rate: 59% (n=461)
- Detection rate of clinically significant prostate cancer (csPCa) (ISUP grade group ≥2): 84% (n=342)
- Different detection rates based on primary biopsy, secondary biopsy, and Active Surveillance (AS)

### PI-RADS Classification

- MRI index lesion (IL) localization and maximum diameter documented
- All mp-MRI evaluated according to PI-RADS version 2
- PCa detection rates based on PI-RADS classification v2.1

Please refer to the original research article [1] for a more comprehensive understanding of the dataset.

## PCa Detection Statistics

- Overall PCa detection rate: 59% (n=461)
- Detection rate of clinically significant prostate cancer (csPCa) (ISUP grade group ≥2): 84% (n=342)
- Detection rates based on biopsy type: primary biopsy (51%), secondary biopsy (34%), Active Surveillance (AS) (47%)

- PCa detection by biopsy technique:
  - TB detected 300 csPCa (88%)
  - SB detected 247 csPCa (72%)

- Additional findings:
  - 30 cases (8.8%) csPCa detected by SB only
  - 67 cases (20%) csPCa detected by TB only
  - 12 cases (3.5%) Gleason upgrade ≥ ISUP 2 due to SB
  - 28 cases (8.2%) Gleason upgrade ≥ ISUP 2 due to TB
  - Additional non-significant (ns) PCa detected by SB: 44 cases
  - Additional nsPCa detected by TB: 34 cases

- PCa detection by PI-RADS classification v2.1:
  - Sensitivity: 94%
  - Specificity: 54% for all PCa
  - Sensitivity: 98%
  - Specificity: 44% for csPCa

Please refer to the original research article [1] for detailed tables and analysis.

## PCa Detection According to PI-RADS

- PCa detection rates according to PI-RADS classification v2.1
- Histopathologically proven PCa rates in PI-RADS assessment categories
- Sensitivity and specificity achieved for all PCa and csPCa

Please refer to the original research article [1] for detailed tables and analysis.

## Usage

You are encouraged to use this dataset for research purposes, especially in the field of prostate cancer detection and diagnostic techniques. Explore and analyze the dataset to gain insights into the effectiveness of targeted and systematic biopsies in detecting clinically significant prostate cancer.

## Contributing

Contributions to this dataset are not applicable as it is intended to support the referenced research article. However, you are welcome

## Setup 
Create and activate a virtual environment (optional but recommended):

python -m venv venv
source venv/bin/activate

Install the required dependencies:
    pip install -r requirements.txt
