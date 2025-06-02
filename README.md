
# 🎥 YouTube-Channel-Revenue-Analysis-and-Prediction

This project analyzes YouTube video data to identify key revenue drivers and predicts estimated revenue using a **Random Forest model**. It includes data cleaning, visualization, and a **Flask web app** where users can input video stats to get real-time revenue predictions—helping creators **optimize their YouTube earnings**.

---

## 🔍 Key Features

✅ Data cleaning and preprocessing (video durations, timestamps)
✅ Feature engineering: *Revenue per View*, *Engagement Rate*, etc.
✅ Exploratory Data Analysis (EDA) with distribution plots, scatter plots, and heatmaps
✅ Random Forest regression model for revenue prediction
✅ Visualizations of feature importance to understand impact factors
✅ Flask-based web app for real-time revenue prediction
✅ Modular and extensible codebase for easy updates

---

## 📊 Dataset Overview

The dataset contains various YouTube video metrics, including:

* **Video Duration**
* **Video Publish Time**
* **Views**
* **Likes, Shares, Comments**
* **Estimated Revenue (USD)**
* **Subscribers**
* **Engagement and revenue-related metrics**

The CSV file should be placed in the `data/` directory.

---

## 🚀 Setup and Usage

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/yourusername/youtube-revenue-prediction.git
cd youtube-revenue-prediction
```

### 2️⃣ Create and Activate a Virtual Environment

```bash
python -m venv venv

# Windows
venv\Scripts\activate

# macOS/Linux
source venv/bin/activate
```

### 3️⃣ Install Required Packages

```bash
pip install -r requirements.txt
```

### 4️⃣ Run Data Processing and Model Training

```bash
python main.py
```

This will:

* Clean and process the data
* Generate visualizations (saved in `outputs/plots/`)
* Train the model and save it as `models/youtube_revenue_predictor.pkl`

### 5️⃣ Launch the Flask Web App

```bash
python app.py
```

### 6️⃣ Open the App in Your Browser

Visit: [http://127.0.0.1:5000/](http://127.0.0.1:5000/)

---

## 🌐 Web App Usage

* Input video stats: **Views, Subscribers, Likes, Shares, Comments, Engagement Rate**
* Submit the form to get a **real-time estimated revenue prediction**
* Explore the visual plots for deeper insights (saved in `outputs/plots/` folder)

---

## 📸 Sample Visuals

| **Revenue vs Views**                                                                                   | **Revenue Distribution**                                                                                  |
| ------------------------------------------------------------------------------------------------------ | --------------------------------------------------------------------------------------------------------- |
| ![revenue\_vs\_views](https://github.com/user-attachments/assets/61eb28cd-ae60-4b54-a3d8-06cdfc6db21b) | ![revenue\_distribution](https://github.com/user-attachments/assets/ccc15576-a711-420b-8631-ed1512123fd0) |

| **Feature Importance**                                                                                  | **Correlation Heatmap**                                                                                  |
| ------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------- |
| ![feature\_importance](https://github.com/user-attachments/assets/e1fad969-ab3d-4da7-a955-ec68588fc140) | ![correlation\_heatmap](https://github.com/user-attachments/assets/50655859-8d89-4a51-87c8-0a62a3189cae) |

---

## 🗂️ Project Structure

```
youtube-revenue-prediction/
│
├── data/
│   └── youtube_channel_real_performance_analytics.csv
│
├── models/
│   └── youtube_revenue_predictor.pkl
│
├── outputs/
│   └── plots/
│       ├── revenue_distribution.png
│       ├── revenue_vs_views.png
│       ├── feature_importance.png
│       └── correlation_heatmap.png
│
├── templates/
│   ├── index.html
│   └── result.html
│
├── static/
│   └── css/
│       └── styles.css
│
├── main.py           # Data processing, EDA, and model training
├── app.py            # Flask web app
├── requirements.txt  # Project dependencies
└── README.md         # Project documentation
```

---

## 🛠️ Technologies Used

* **Python 3.x**
* **Pandas**, **NumPy** (data manipulation)
* **Scikit-learn** (machine learning)
* **Matplotlib**, **Seaborn** (visualization)
* **Flask** (web app interface)
* **Joblib** (model persistence)

---

## 🌟 Future Enhancements

* Advanced feature engineering & hyperparameter tuning
* Real-time data fetching from **YouTube API**
* Cloud deployment (Heroku, AWS, etc.)
* User authentication for personalized predictions
* More detailed analytics and interactive visualizations

---

## 📄 License

This project is licensed under the **MIT License**.

---

