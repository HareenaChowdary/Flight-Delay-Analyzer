# ✈️ Flight Delay Analyzer 🚀  

## 📌 Overview  
Air travel delays impact millions of passengers worldwide. **Flight Delay Analyzer** is a comprehensive data analysis and predictive modeling project that uncovers the patterns behind flight delays using **R**. This project utilizes **data visualization, machine learning models, and statistical analysis** to predict flight delays and help airlines improve punctuality.

## 📊 Key Features  
✅ **Data Preprocessing:** Cleans missing values, extracts time-based features, and enhances data quality.  
✅ **Exploratory Data Analysis (EDA):** Visualizes delay distributions, airline performance, and seasonal trends.  
✅ **Heatmaps & Correlations:** Displays delay trends across time using correlation matrices and heatmaps.  
✅ **Predictive Modeling:** Implements **Linear Regression** for classifying significant arrival delays.  
✅ **Model Performance Metrics:** Evaluates accuracy, precision, recall, F1-score, and AUC.  

## 🔍 Dataset  
The dataset used is from **2018 U.S. flight records**, containing flight details such as departure and arrival times, airline carrier, delay reasons, and distances.  
[2018.csv](https://www.kaggle.com/datasets/sherrytp/airline-delay-analysis/data)

📂 **Source:** U.S. Department of Transportation
**Purpose:** Tracks on-time performance, delays, cancellations, and diversions of domestic flights operated by large air carriers.
**Volume:**
  - 7.2+ million observations.
  - 28 attributes covering performance, timing, and reasons for delays.

## 📦 Tech Stack  
🔹 **R** (for data manipulation, visualization, and modeling)  
🔹 **ggplot2** (for beautiful visualizations)  
🔹 **data.table & dplyr** (for efficient data handling)  
🔹 **caret** (for model training and evaluation)  
🔹 **corrplot & pROC** (for correlation analysis and ROC curves)  

## 🚀 Installation & Usage  
1️⃣ Clone the repository:  
```bash
git clone https://github.com/HareenaChowdary/Flight-Delay-Analyzer.git
cd Flight-Delay-Analyzer
```
2️⃣ Install required R packages:  
```r
install.packages(c("dplyr", "ggplot2", "tidyr", "caret", "corrplot", "data.table", "pROC"))
```
3️⃣ Run the script:  
```r
source("flight_delay_analysis.R")
```

## 📈 Results & Insights  
 **- Airlines with Highest Delays:** Frontier Airlines **(F9)** had the longest delays, while Alaska Airlines **(AS)** performed better.
 
 **- Time of Day & Delays:** Delays increase throughout the day, with **evening flights (after 6 PM)** experiencing the most delays.
 
 **- Weather & Distance Impact:** Weather had minimal impact on delays, while **short-haul flights** faced more frequent disruptions than long-haul flights.
 
 **- Predictive Model Performance:**
 
     - **Accuracy:** 95% | **Precision:** 94% | **F1-score:** 98% | **AUC:** 0.99
     
     - **Departure delay** was the strongest predictor, followed by **taxi-out time** and distance

## 🏆 Future Enhancements  
✔️ Incorporate more advanced machine learning models (Random Forest, XGBoost).  
✔️ Deploy a **Shiny Dashboard** for real-time flight delay predictions.  
✔️ Expand analysis to **international flights** for broader insights.  

## 🤝 Contributing  
Contributions are welcome! Fork the repository, create a new branch, and submit a pull request.  

## 🛠️ Author  
👤 **Hareena Chowdary Polavaram**  
📧 [LinkedIn Profile](https://www.linkedin.com/in/hareena-chowdary-polavaram)  

## ⭐ Show Your Support  
If you found this project useful, give it a ⭐ on GitHub!  

