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

## Project Demo Recording
[Add YouTube or Google Drive link here]

## Dataset
Kaggle NBA Players Stats - Seasons_Stats.csv (1980-2017)
https://www.kaggle.com/datasets/drgilermo/nba-players-stats

## How to Run
1. Upload Seasons_Stats.csv to your working directory
2. Open PlayerPredict_AI.ipynb in Jupyter or Google Colab
3. Run all cells in order
4. Use the Gradio app in the last cell to make predictions

## Libraries Required
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- gradio
