# my_chess_game_analysis
# Chess Match Analysis and Win Prediction 

This project analyzes the data from my last 100 nullet chess matches on **Lichess**, a popular online chess platform, to predict the win percentage for future games. As a **professional chess player**, I aim to leverage machine learning algorithms to better understand patterns in my performance and predict outcomes when playing with white or black pieces.

## Project Objective
- Predict win percentages based on whether I play with white or black pieces.
- Use insights from the data to refine strategies and improve performance.
- Compare machine learning algorithms such as **Random Forest**, **Decision Trees**, and **K-Nearest Neighbors (KNN)** to determine the best approach for this problem.

## Dataset
- The dataset consists of detailed information from my **last 100 bullet matches on Lichess**.
- Key features include:
  - **Color**: Whether I played with white or black pieces.
  - **Opponent ELO**: The difference between my rating and my opponent's rating.
  - **Number of Moves**: Total number of moves made in the game.
  - **Opening Name**: The name of the opening played.
  - **Result**: Outcome of the game (win, draw, or loss).

## Machine Learning Algorithms
1. **Random Forest**:
   - Ensemble-based method combining multiple decision trees.
   - Provides insights into feature importance, such as the impact of ELO differences and opening choice.

2. **Decision Trees**:
   - Simple, interpretable models that visualize decision-making processes.
   - Useful for understanding how specific factors contribute to outcomes.

3. **K-Nearest Neighbors (KNN)**:
   - Classifies matches based on similarity to past games.
   - Effective for small datasets like this one.

## Project Workflow
1. **Data Preparation**:
   - Preprocessing raw data from Lichess to handle missing values and inconsistencies.
   - Feature engineering, such as encoding categorical variables (e.g., opening names) and calculating derived metrics like ELO differences.

2. **Modeling**:
   - Training models using the specified algorithms.
   - Evaluating model performance using metrics like accuracy, precision, recall, and F1 score.

3. **Prediction and Insights**:
   - Predicting win percentages for games where I play with white or black pieces.
   - Analyzing feature importance to identify key factors that influence match outcomes.

4. **Model Comparison**:
   - Comparing algorithms to identify the best-performing model.
   - Visualizing model performance through confusion matrices and ROC curves.

## Tools and Technologies
- **Python**: For data preprocessing, analysis, and modeling.
- **scikit-learn**: For implementing machine learning algorithms.
- **pandas and numpy**: For data manipulation and analysis.
- **matplotlib and seaborn**: For data visualization.

