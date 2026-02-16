# Predicting Dementia Severity from Brain MRI Using Deep Learning
**Author:** Sabrina Souhaya Saidoune

---

## Project Overview
This project develops machine learning models to predict dementia status from brain MRI images. The dataset contains three classes:

- **NoImpairment** – MRI images of subjects with no signs of dementia
- **MildImpairment** – MRI images of subjects with mild symptoms of dementia
- **ModerateImpairment** – MRI images of subjects with moderate dementia

Models are designed, implemented, and evaluated, with results presented in a research report structured like a scientific article, discussing clinical utility and ethical considerations.

---

## Dataset
The brain MRI dataset is located on the HPC appbio partition:

```
/scratch/grp/msc_appbio/AI/Assessment/AD/
```

A link to the dataset is also provided in the project repository.

---

## Project Structure
```swift
sabrinasaidoune/
│
├── code/
│   └── 2_AI_ASSESSMENT.ipynb           // Main notebook for model development
│
├── plots/
│   ├── model_1/
│   │   └── training_validation_curve_model1.png  // Training/validation curves for Model 1
│   └── model_2/
│       └── training_validation_curve_model2.png  // Training/validation curves for Model 2
│
├── training_history/
│   ├── training_history_model_1.json    // Training metrics for Model 1
│   └── training_history_model_2.json    // Training metrics for Model 2
│
└── README.md

```

---

## Model Development 

Multiple machine learning models are trained to classify MRI images.

  Training and validation curves for Model 1 and Model 2 are stored in their respective plots folders.
  Model performance metrics are saved in JSON files under training_history.
  Evaluation focuses on classification accuracy across the three dementia classes.

A 15-minute oral presentation via Teams summarizes approach, findings, and medical/ethical implications.

Scheduled for the week of 2nd February 2026
