# NFL Athlete Performance
###### Created by Emir Yorgun

## Overview

This project encompasses comprehensive analyses to optimize the performance of NFL player Justin Hillard. Utilizing Random Forest Regression in Python, the project aims to provide insights into various performance metrics.

## Objectives

- **Performance Analysis:** Calculate the relationship between general features and overall performance.
- **Sleep and Performance Correlation:** Examine the relationship between sleep patterns and next-day performance.
- **Training Effectiveness:** Assess whether the targeted performance from training sessions is being achieved.

## Dataset

The dataset used in this project is the [NFL Daily Performance Dataset by Justin Hilliard](https://www.kaggle.com/datasets/justinhilliard97/nfl-daily-performance-dataset-justin-hilliard), which includes comprehensive information on NFL athlete's daily performances.


## Getting Started

To get started with this project, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/hootbu/NFL-Athlete-Performance.git
   ```
2. Navigate to the project directory:
   ```bash
   cd NFL-Athlete-Performance
   ```
3. Install the necessary dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Usage

1. Start Jupyter Notebook:
   ```bash
   Jupiter notebook
   ```
2. Open the `Performance.ipynb` file and run.

## Key Findings
1. Average RPE vs. Scripted Intensity

This graph shows the average RPE (Rate of Perceived Exertion) for different training intensities: Light, Medium, and High.

<img width="839" height="600" alt="averageRPE_ScriptedIntensity" src="https://github.com/user-attachments/assets/a0c991af-7521-42af-84de-e230bc3caa95" />

- When the training is Light, the average RPE is low.

- For Medium intensity, the RPE is higher.

- For High intensity, the RPE is the highest.

This means the athlete feels more tired when the training is harder. The athlete's feelings match the training plan.

2. Sleep’s Effect on Overall Performance

This graph shows whether sleep affects the athlete’s performance the next day. It compares average sleep hours with the overall performance score.

<img width="855" height="558" alt="SleepEffectonOverallPerformance" src="https://github.com/user-attachments/assets/1ed0fb64-cc1d-48b9-8387-e775bd13d536" />

If the athlete sleeps more, the performance score is usually a little higher.

However, the correlation is not very strong (correlation between totalSleep and Overall = 0.27). This means sleep helps, but it is not the only important factor.

Other things like nutrition, training, and recovery are also important for good performance.


## Acknowledgements

A big thank you to Justin Hilliard for providing the dataset on Kaggle.
