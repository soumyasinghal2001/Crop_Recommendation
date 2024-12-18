# **Crop Recommendation System**

## **Overview**
The **Crop Recommendation System** is a machine learning-based project designed to help farmers and agricultural professionals recommend the most suitable crop to grow based on environmental and soil conditions. This system utilizes data-driven insights to optimize crop yield and enhance agricultural sustainability.

---

## **Objectives**
1. **Predict the best crop** to cultivate based on soil and environmental parameters.
2. Enable informed decision-making to maximize productivity.
3. Promote sustainable agriculture by reducing uncertainties in crop selection.

---

## **Dataset Description**
The dataset contains various environmental and soil attributes crucial for crop prediction:

### **Features**
- **N:** Nitrogen content in the soil (kg/ha).
- **P:** Phosphorus content in the soil (kg/ha).
- **K:** Potassium content in the soil (kg/ha).
- **Temperature:** Average temperature (°C).
- **Humidity:** Relative humidity (%).
- **pH:** Soil pH value.
- **Rainfall:** Rainfall (mm).

### **Target Variable**
- **Recommended Crop:** The type of crop most suitable for the given conditions.

---

## **Project Workflow**
1. **Data Preprocessing:**
   - Handled missing or inconsistent values.
   - Scaled and normalized data for better model performance.

2. **Exploratory Data Analysis (EDA):**
   - Analyzed relationships between features and crop recommendations.
   - Visualized trends and patterns using heatmaps and scatter plots.

3. **Model Development:**
   - Trained and evaluated the following machine learning models:
     - Logistic Regression (Log_R)
     - Decision Tree (DT)
     - Random Forest (RF)
     - K-Nearest Neighbors (KNN)
     - Naive Bayes (NB)
     - Gradient Boosting (GB)

---

## **Results**

The machine learning models were evaluated on **Accuracy**, **Precision**, **F1 Score**, and **Recall**. The table below summarizes the performance metrics for each model:

| **Metric**     | **Logistic Regression (Log_R)** | **Decision Tree (DT)** | **Random Forest (RF)** | **K-Nearest Neighbors (KNN)** | **Naive Bayes (NB)** | **Gradient Boosting (GB)** |
|-----------------|---------------------------------|-------------------------|-------------------------|-------------------------------|-----------------------|----------------------------|
| **Accuracy**    | 94.55%                         | 98.86%                 | **99.32%**             | 97.05%                       | **99.54%**           | 98.18%                    |
| **Precision**   | 94.55%                         | 98.86%                 | **99.32%**             | 97.05%                       | **99.54%**           | 98.18%                    |
| **F1 Score**    | 94.55%                         | 98.86%                 | **99.32%**             | 97.05%                       | **99.54%**           | 98.18%                    |
| **Recall**      | 94.55%                         | 98.86%                 | **99.32%**             | 97.05%                       | **99.54%**           | 98.18%                    |

### **Key Observations**
- **Naive Bayes** achieved the highest performance across all metrics, with an accuracy, precision, F1 score, and recall of **99.54%**.
- **Random Forest** closely followed, achieving **99.32%** across all metrics.
- **K-Nearest Neighbors** had a strong performance, though slightly lower than the top models, maintaining accuracy and precision above **97%**.

---

## **Future Scope**
1. Include additional environmental data, such as real-time weather and soil conditions, to improve predictions.
2. Expand the dataset to cover more regions and crop types.
3. Incorporate advanced ensemble techniques to improve prediction accuracy further.

---


## **Acknowledgments**
- The dataset was sourced from Kaggle and adapted for this project.
- Special thanks to the agricultural and data science communities for their insights and resources.

