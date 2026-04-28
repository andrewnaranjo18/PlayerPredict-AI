# PlayerPredict AI 🏀
NBA Next-Season Performance Predictor

## Overview
PlayerPredict AI is a machine learning system that predicts NBA player 
performance for the next season using historical season statistics. 
The system trains three regression models — Linear Regression, Random Forest, 
and MLP Neural Network — to predict next-season Points Per Game (PPG), 
Rebounds Per Game (RPG), and Assists Per Game (APG). 
Results are displayed through an interactive Gradio web interface 
with confidence ranges for transparency.

## Team Members
Ethan Zbeda, Andrew Naranjo, Frank Watkins, Edwin Feliz, Jake Scheck

## Course
CAP 4630 - Intro to Artificial Intelligence | Spring 2026
Professor: Dr. Ahmed Imteaj

## Dataset
Kaggle NBA Players Stats (1980-2017)
https://www.kaggle.com/datasets/drgilermo/nba-players-stats

⚠️ Only download **Seasons_Stats.csv** from this dataset — it is the only file required to run the project.

## How to Run on Google Colab
1. Go to https://colab.research.google.com
2. Click **File** → **Upload notebook**
3. Upload **PlayerPredictAI.ipynb** from this repository
4. Download **Seasons_Stats.csv** from this repository
5. In Colab, click the **folder icon** on the left sidebar
6. Click the **upload icon** and upload **Seasons_Stats.csv**
7. Click **Runtime** → **Run all**
8. Scroll to the last cell and click the Gradio link to open the app
9. Type any NBA player name and click **Predict Next Season**

## Links
Google Colab Notebook -
https://colab.research.google.com/drive/1eojrq-EsrIf4kNTj3HBqEo8fvjr-7EdZ?usp=sharing

Presentation Recording - https://www.youtube.com/watch?v=uo6DRlKrlow 

## Libraries Required
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- gradio
