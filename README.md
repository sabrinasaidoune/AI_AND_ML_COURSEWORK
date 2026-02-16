Brain MRI Classification Project

Author: sabrinasaidoune

Project Overview

This project aims to develop a machine learning model that predicts dementia status from brain MRI images. The dataset contains three classes of images:

NoImpairment – MRI images of subjects with no signs of dementia

MildImpairment – MRI images of subjects with mild symptoms of dementia

ModerateImpairment – MRI images of subjects with moderate dementia

Using this dataset, the project applies machine learning techniques to classify MRI scans and evaluate the model’s performance. Results are presented in a research report, structured like a scientific article, discussing both clinical utility and ethical considerations.

Dataset

The brain MRI dataset is located on the HPC appbio partition:

/scratch/grp/msc_appbio/AI/Assessment/AD/


Additionally, a link to the dataset is provided in the project repository.

Project Structure
sabrinasaidoune/
│
├── code/
│   └── 2_AI_ASSESSMENT.ipynb     # Main notebook for model development
│
├── plots/
│   └── model_2/
│       └── training_validation_curve_model2.png   # Training/validation curves for Model 2
│
├── training_history/
│   └── training_history_model_2.json   # Model 2 training metrics
│
└── README.md

Model Development

Design, implementation, and evaluation of machine learning models were performed using knowledge from previous workshops.

Performance metrics, such as accuracy and loss, are tracked in JSON and visualized in training plots.

Models are evaluated on their ability to differentiate between the three dementia classes.

Research Report & Presentation

A research report is submitted to KEATS by 4 pm, 23rd February 2026.

The report includes:

Model design and methodology

Results and evaluation

Integration with relevant literature

Discussion of clinical utility and ethical considerations

A 15-minute oral presentation via Teams will summarize the approach, findings, and implications. Scheduled for the week of 2nd February 2026.

An example research article for guidance:
Frontiers in Human Neuroscience, 2023

Assessment Notes

The project contributes 40% of the total mark via oral presentation.

Ensure clarity, timing, and ethical discussion are included in the presentation.

If you want, I can also draft a more visually appealing version with badges, quick-start instructions, and dataset download links that would make it GitHub-ready.

Do you want me to do that?

there a model 1 folder in plots

Perfect! We can update the README to reflect both Model 1 and Model 2 folders in plots so it’s fully accurate. Here’s the revised version:

Brain MRI Classification Project

Author: sabrinasaidoune

Project Overview

This project develops machine learning models to predict dementia status from brain MRI images. The dataset contains three classes:

NoImpairment – MRI images of subjects with no signs of dementia

MildImpairment – MRI images of subjects with mild symptoms of dementia

ModerateImpairment – MRI images of subjects with moderate dementia

Models are designed, implemented, and evaluated, with results presented in a research report structured like a scientific article, discussing clinical utility and ethical considerations.

Dataset

The brain MRI dataset is located on the HPC appbio partition:

/scratch/grp/msc_appbio/AI/Assessment/AD/


A link to the dataset is also provided in the project repository.

Project Structure
sabrinasaidoune/
│
├── code/
│   └── 2_AI_ASSESSMENT.ipynb           # Main notebook for model development
│
├── plots/
│   ├── model_1/
│   │   └── training_validation_curve_model1.png  # Training/validation curves for Model 1
│   └── model_2/
│       └── training_validation_curve_model2.png  # Training/validation curves for Model 2
│
├── training_history/
│   ├── training_history_model_1.json    # Training metrics for Model 1
│   └── training_history_model_2.json    # Training metrics for Model 2
│
└── README.md

Model Development

Multiple machine learning models are trained to classify the MRI images.

Training and validation curves for Model 1 and Model 2 are stored in their respective plots folders.

Model performance metrics are saved in training_history JSON files.

Evaluation focuses on classification accuracy across the three dementia classes.

Research Report & Presentation

Submit the research report to KEATS by 4 pm, 23rd February 2026.

The report includes:

Model design and methodology

Results and evaluation

Integration with relevant literature

Discussion of clinical utility and ethical considerations

A 15-minute oral presentation via Teams summarizes approach, findings, and medical/ethical implications. Scheduled for the week of 2nd February 2026.
