YouTube-Channel-Revenue-Analysis-and-Prediction

This project analyzes YouTube video data to identify key revenue drivers and predicts estimated revenue using a Random Forest model. It includes data cleaning, visualization, and a Flask web app where users input video stats to get real-time revenue predictions—helping creators optimize their YouTube earnings.



Key Features:
- Data cleaning and preprocessing, including converting video durations and timestamps.
- Feature engineering with metrics like Revenue per View and Engagement Rate.
- Exploratory Data Analysis (EDA) with distribution plots, scatter plots, and correlation heatmaps.
- Training and evaluation of a Random Forest regression model for revenue prediction.
- Visualization of feature importance to understand impact factors.
- A Flask-based web UI to interactively predict revenue from video stats.
- Modular and extensible codebase for easy updates.



The dataset contains various YouTube video metrics, including but not limited to:

- Video Duration
- Video Publish Time
- Views
- Likes, Shares, Comments
- Estimated Revenue (USD)
- Subscribers
- Engagement and revenue-related metrics

The CSV file is expected to be in the `data/` directory.


Step-by-Step Setup and Usage Instructions
Clone the repository
Download the entire project from GitHub to your local computer.

Create and activate a virtual environment
Set up an isolated Python environment for this project to avoid conflicts with other Python packages.

Install required packages
Install all necessary Python libraries listed in the requirements file to ensure the project runs smoothly.

Run data processing and model training
Execute the main analysis script to clean and analyze the data, generate visualizations, and train the machine learning model. This process will save plots and the trained model on your system.

Run the Flask web application
Launch the web app that provides a user interface for inputting video statistics and predicting YouTube revenue.

Open the app in a web browser
Access the app locally by opening the provided address in your browser. (It will look like this)
![image](https://github.com/user-attachments/assets/837d9942-b7d4-464e-bb8a-3091136511d2)


How to Use the Web App
Enter video statistics such as views, subscribers, likes, shares, comments, and engagement rate into the input fields.

Submit the form to receive a real-time estimated revenue prediction based on your inputs.

For deeper analysis, check out the generated visual plots stored in the outputs folder.
![revenue_vs_views](https://github.com/user-attachments/assets/61eb28cd-ae60-4b54-a3d8-06cdfc6db21b)
![revenue_distribution](https://github.com/user-attachments/assets/ccc15576-a711-420b-8631-ed1512123fd0)
![feature_importance](https://github.com/user-attachments/assets/e1fad969-ab3d-4da7-a955-ec68588fc140)
![correlation_heatmap](https://github.com/user-attachments/assets/50655859-8d89-4a51-87c8-0a62a3189cae)




Project Structure
![image](https://github.com/user-attachments/assets/1ba59757-ab0c-4107-acf8-0b45c9209b6e)


Technologies Used
Python 3.x
Pandas, NumPy for data manipulation
Scikit-learn for machine learning
Matplotlib and Seaborn for visualization
Flask for web interface
Joblib for saving/loading the model

Future Enhancements
Incorporate advanced feature engineering and hyperparameter tuning.
Add real-time data fetching from YouTube API.
Deploy the web app to cloud hosting platforms (Heroku, AWS, etc.).
Implement user authentication for personalized predictions.
Add more detailed analytics and interactive visualizations.

License
This project is licensed under the MIT License.
