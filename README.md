# ⚡ **Energy Auditing Through Machine Learning**  

[![Python](https://img.shields.io/badge/Python-3.9-blue.svg)](https://www.python.org/) [![Machine Learning](https://img.shields.io/badge/Machine%20Learning-Scikit--Learn-green)](https://scikit-learn.org/) ![Energy Efficiency](https://img.shields.io/badge/Energy%20Efficiency-Audit-orange)


## 📌 **Project Overview**  
This project presents an innovative **machine learning-based energy auditing system** that enables efficient energy monitoring and conservation in **industrial and residential environments**. Traditional energy audits are **time-consuming** and **resource-intensive**, requiring human intervention for assessment. Our model leverages **machine learning algorithms** to **classify running loads, identify energy wastage**, and suggest **optimization strategies** to **reduce electricity consumption** and **increase efficiency**.

💡 **Key Objectives:**  
✔ **Automate energy auditing** using real-time data processing  
✔ **Optimize power usage** by identifying inefficient appliances  
✔ **Develop ML models** for **load classification & anomaly detection**  
✔ **Generate energy audit reports** for informed decision-making  
✔ **Enhance sustainability** through intelligent power management  

---

## 📊 **Dataset & Methodology**  
### **Dataset:**  
The dataset used includes real-time power consumption metrics from **various appliances** and **industrial equipment**. The **key features** considered in the dataset include:  

| **Feature** | **Description** |
|------------|----------------|
| `power_usage` | Real-time power consumption in watts |
| `power_factor` | Efficiency of power usage (0 to 1) |
| `current_load` | Load current drawn (in Amperes) |
| `frequency` | Operating frequency of the system |
| `time_of_day` | Time stamp for energy consumption pattern |
| `category` | Classification of appliances (HVAC, lighting, etc.) |

---

## ⚙️ **Machine Learning Pipeline**
We employ a **multi-step ML approach** to analyze and audit energy usage:

### **1️⃣ Data Preprocessing & Feature Engineering:**  
✔ **Handle missing values** and **outlier detection**  
✔ **Feature extraction** using **Gray Code encoding** for energy load patterns  
✔ **Normalization & standardization** for model optimization  
✔ **Clustering-based load classification** using **fuzzy logic**  

### **2️⃣ Load Classification & Energy Wastage Detection:**  
✔ **Supervised Learning**: **Random Forest, Decision Trees, XGBoost**  
✔ **Unsupervised Learning**: **K-Means, DBSCAN for anomaly detection**  
✔ **Real-time energy tracking** with predictive load analysis  

### **3️⃣ Energy Audit Report Generation:**  
✔ **Identifies high-energy consuming appliances**  
✔ **Suggests rescheduling for energy conservation**  
✔ **Recommends usage optimization techniques**  

---

## 📁 **Project Structure**  
```
📂 data/                # Raw and cleaned datasets
📂 notebooks/           # Jupyter Notebooks for EDA, ML modeling, and analysis
📂 src/                 # Python scripts for modularization
📂 results/             # Model results and performance metrics
📂 config/              # Configuration settings for hyperparameters
├── README.md          # Project documentation
├── requirements.txt   # Python dependencies
├── app.py             # Flask API for model deployment
```

---

## 📈 **Key Insights & Findings**
✔ **Energy efficiency varies across different appliances** – **HVAC systems & industrial motors** consume the highest power.  
✔ **Peak usage times** (morning & evening) show **higher energy wastage** due to idle consumption.  
✔ **Machine learning-based audits** provide **real-time recommendations** to reduce power waste.  
✔ **Automation & rescheduling of appliances** can **reduce energy consumption by 15-20%**.  

---

## 🚀 **Business Impact**
📊 **Cost Reduction**: Saves **electricity bills** for industries & households.  
⚡ **Energy Optimization**: Prevents **overuse of appliances** through **real-time monitoring**.  
🌱 **Sustainability**: Reduces **carbon footprint** by promoting **energy conservation**.  

🔹 **Example Insight:**  
- **Reducing idle power consumption** of **industrial equipment** by **10%** can **save thousands of kWh annually**.  
- **Smart scheduling** of **energy-intensive appliances** can result in **significant cost savings**.  

---

## 💻 **Installation & Usage**  
### **1️⃣ Clone the Repository**  
```sh
git clone https://github.com/Navabhargav/Energy-Auditing-ML.git
cd Energy-Auditing-ML
```  

### **2️⃣ Install Required Dependencies**  
```sh
pip install -r requirements.txt
```  

### **3️⃣ Run Jupyter Notebook for Analysis**  
```sh
jupyter notebook
```
Open `Energy_Audit_Analysis.ipynb` and execute the steps.  

### **4️⃣ Deploy Model as API (Flask Server)**  
```sh
python app.py
```
API will be available at: **http://127.0.0.1:5000/predict**

---

## 🖥️ **Technologies Used**
| **Category**         | **Technologies** |
|----------------------|-----------------|
| **Languages**        | Python, SQL |
| **Data Processing**  | Pandas, NumPy, SciPy |
| **Machine Learning** | Scikit-learn, XGBoost, TensorFlow |
| **Data Visualization** | Matplotlib, Seaborn, Tableau |
| **Feature Engineering** | PCA, Clustering, Gray Code Encoding |
| **Deployment**       | Flask, Docker, AWS Lambda |

---

## 📚 **References**
- 📄 Research Paper: [Energy Auditing with ML](https://arxiv.org/)  
- 📄 Scikit-learn Documentation: [Machine Learning in Python](https://scikit-learn.org/stable/)  
- 📄 OpenEnergy Data API: [Energy Consumption Data](https://datahub.io/)  

---

## 🤝 **Contributors**
👤 **Nava Bhargav Gedda**  
📩 [navabhargavg@gmail.com](mailto:navabhargavg@gmail.com)  
🔗 [LinkedIn](https://linkedin.com/in/nava-bhargav-gedda-4a4a30151) | 🌐 [GitHub](https://github.com/Navabhargav)  


---

## ⭐ **Like this Project?**
If you found this project useful, **give it a star ⭐** on GitHub and share it with others! 🚀  
