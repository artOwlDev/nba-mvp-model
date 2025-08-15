This project focuses on analyzing NBA player data(cleaning, normalziing etc.) and predicting who's going to be the MVP.

The model incrementally uses past data to predict the next season's data and so on.

## Overview

The goal of this project is to leverage historical NBA statistics to predict who is most likely to win the MVP award. The workflow includes:

Data Acquisition – Scapred data from https://www.basketball-reference.com/

Data Cleaning & Normalization – Processed and standardized the data to ensure consistency and reliability for modeling.

Modeling & Prediction – Built a predictive model to estimate MVP likelihoods based on player statistics.

## Snapshots

#### Correlation of individual statistics on being the MVP
![Correlation of Statistics On Being MVP](https://github.com/user-attachments/assets/0ebfee24-7db9-41a4-bee8-55c7e4f4f532)

#### How has scoring changed throughout the years?
![How has scoring changed throughout the years](https://github.com/user-attachments/assets/6b0d27dd-6448-4108-a6b8-df141f10dec9)

#### MVP data from the 2022-2023 season.
<img width="902" height="651" alt="Screenshot 2025-08-14 at 8 12 07 PM" src="https://github.com/user-attachments/assets/3b58d18e-0d6a-42ad-95c7-376d38311a57" />


####

## Technologies & Libraries

Python 3.x

Pandas, NumPy (Data manipulation)

Scikit-learn (Modeling & Prediction)

Matplotlib (Data Visualization)

## Run

Clone the repository:

git clone https://github.com/artOwlDev/nba-model.git

Open main.ipynb in Jupyter Notebook or VSCode.

## Insights

Normalization and cleaning significantly improved model accuracy.

Key performance metrics like points, assists, rebounds, and efficiency ratings having a high correlation to being selected as the MVP.

The model outputs a ranked list of potential MVP candidates for the season.

Future Work

Do this for every season! I also do believe taking into account players who were incredibly important but don't have lots of points/assists can be interesting. I.e: Steve Nash 2004
