# AI Data Center Energy Consumption Prediction Using Machine Learning

## 📌 Project Overview

As Artificial Intelligence continues to expand, AI data centers require enormous computational power, resulting in high electricity consumption and increased cooling demands. Efficient energy management has become one of the biggest challenges in building sustainable AI infrastructure.

This project develops a Machine Learning model that predicts **energy consumption (kWh)** of an AI data center using operational and environmental parameters. The objective is to understand the factors associated with energy usage and support smarter, more sustainable resource management.



## 🎯 Problem Statement

Modern AI data centers consume significant amounts of electricity due to heavy CPU/GPU workloads and cooling requirements. Predicting energy consumption can help organizations:

- Optimize resource utilization
- Reduce operational costs
- Improve cooling efficiency
- Support sustainable AI infrastructure
- Make data-driven operational decisions



## 📊 Dataset Features

The dataset includes:

- Date & Hour
- CPU Utilization (%)
- GPU Utilization (%)
- Active Servers
- Outside Temperature (°C)
- Humidity (%)
- Cooling Method
- Cooling Efficiency (%)
- AI Workload
- Renewable Energy (%)
- Power Usage Effectiveness (PUE)

### 🎯 Target Variable

- **Energy Consumption (kWh)**



## ⚙️ Project Workflow

1. Data Loading
2. Data Cleaning
3. Feature Engineering
4. Label Encoding
5. Exploratory Data Analysis (EDA)
6. Data Visualization using Matplotlib
7. Train-Test Split
8. Linear Regression Model
9. Model Evaluation
10. Prediction and Performance Analysis



## 🧩 Feature Engineering

Additional features were created to improve the model's ability to represent data center operations:

- **Total Computation Power**
- **Energy Per Server**
- **Cooling Load**



## 📈 Model Performance

| Metric | Score |
|---|---:|
| MAE | 24.10 |
| MSE | 805.89 |
| RMSE | 28.39 |
| R² Score | 0.9924 |

The model achieved an **R² score of 0.9924**, meaning it explained approximately 99.24% of the variation in energy consumption on the evaluated dataset. This result depends on the dataset and evaluation method and does not guarantee the same performance on real-world data.



## 📊 Visualizations

The project includes visual analysis of:

- Energy Consumption Distribution
- CPU Utilization vs. Energy Consumption
- GPU Utilization vs. Energy Consumption
- Temperature vs. Energy Consumption
- Cooling Method vs. Energy Consumption
- AI Workload vs. Energy Consumption
- Actual vs. Predicted Energy Consumption



## 💡 Key Insights

- CPU and GPU utilization help represent the computational workload of a data center.
- Outside temperature and humidity provide important environmental context for cooling requirements.
- Cooling methods and cooling efficiency help describe thermal management conditions.
- AI workload categories help explore differences in computational demand.
- Feature engineering introduces additional information that may help the model identify patterns in the data.

These observations describe relationships within the available dataset and do not necessarily establish cause and effect.



## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Jupyter Notebook



## 🚀 Future Improvements

This project can be extended further by:

- Adding real-time energy consumption prediction using user inputs.
- Deploying the model as an interactive **Streamlit web application**.
- Comparing Linear Regression with Random Forest, XGBoost, and Gradient Boosting.
- Evaluating the model using real-world data center datasets.
- Integrating relevant weather data to explore the impact of environmental conditions.
- Developing a recommendation system to investigate energy-efficient cooling and resource allocation strategies.
- Building an energy analytics dashboard using Tableau or Power BI.



## 🎯 Conclusion

This project demonstrates how Machine Learning can be used to predict AI data center energy consumption based on operational and environmental parameters. By exploring patterns in the data and estimating energy demand, it highlights the potential of predictive analytics to support more informed decisions about sustainable AI infrastructure.

Although the model does not directly reduce energy consumption, it provides a starting point for further research into energy forecasting, operational efficiency, and sustainable data center management.

---

**Project Focus:** Machine Learning | Predictive Analytics | AI Sustainability | Energy Efficiency
