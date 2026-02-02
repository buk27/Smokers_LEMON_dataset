# Smokers_LEMON_dataset
# Predicting Smoking Behavior via Psychological Factors
### An Analysis of the MPI-Leipzig Mind-Brain-Body Dataset

## Project Overview
This project investigates whether demographic factors and psychological traits—specifically stress (TICS), anger (STAXI), and coping strategies—can predict smoking status. Using Python and Machine Learning, I analyzed a subset of the "Mind-Brain-Body" database to see how emotional regulation and social stress relate to nicotine use.

## Data Source
The dataset used in this analysis is sourced from the **MPI-Leipzig Mind-Brain-Body database**, a large-scale open-access dataset focused on the relationship between brain structure, psychological traits, and health behaviors.
* **Title:** *A mind-brain-body dataset of MRI, EEG, cognition, emotion, and peripheral physiology in young and old adults*
* **Publication:** [Scientific Data, 5:180308 (2018)](https://www.nature.com/articles/sdata2018308)
* **Authors:** Babayan, A., Erbey, M., Kumral, D., et al.

## How to Run
This project was developed in **Google Colab**. You can interact with the code and view visualizations directly:

1. Click the **"Open in Colab"** button at the top of the `.ipynb` file in this repository.
2. (Optional) Local setup requires `scikit-learn`, `pandas`, `seaborn`, and `matplotlib`.

## Key Research Findings
* **Model Performance:** The classification model reached an overall accuracy of **89%**.
* **Addressing Class Imbalance:** The high accuracy was largely influenced by a majority of non-smokers in the data. While the model predicted non-smokers with high precision, identifying the smoking minority class remained a challenge, as discussed in the notebook.
* **Top Predictors:** Using a **Random Forest** feature importance analysis, I found that **Anger Regulation (STAXI)** and **Social Stress (TICS)** were higher contributors to the model's decisions than basic demographic markers.
* **Conclusion:** The findings support the idea that psychological coping mechanisms and social stress levels are more indicative of smoking behavior than age or education alone.



## Tech Stack
* **Language:** Python
* **Key Libraries:** `scikit-learn` (Random Forest, Classification), `pandas` (Data Cleaning), `seaborn` & `matplotlib` (Plots)
* **Environment:** Google Colab
