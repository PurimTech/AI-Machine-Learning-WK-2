# 🏙️ Urban Vulnerability Mapper  
### **AI for SDG 11: Sustainable Cities and Communities**

---

## 🌍 Overview  
The **Urban Vulnerability Mapper** is an AI-driven machine learning project that identifies **informal settlements** and evaluates **climate vulnerability** across urban environments.  
It supports decision-makers and urban planners to **prioritize interventions**, enhance **resilience**, and promote **sustainable city development** — directly advancing **UN Sustainable Development Goal 11**.

This project uses **synthetic urban data** to simulate features such as housing density, flood risk, and access to infrastructure — similar to what could be extracted from **satellite imagery** and **IoT-based environmental sensors**.

---

## 🎯 Project Objectives
- Detect informal settlements using supervised learning (Random Forest Classifier).  
- Cluster and rank vulnerable areas using unsupervised learning (K-Means).  
- Generate actionable insights for sustainable city planning.  
- Apply ethical AI principles for fairness, transparency, and sustainability.

---

## 🧠 Technologies Used
- **Python 3.10+**
- **NumPy** – numerical computation  
- **Pandas** – data processing and analysis  
- **Matplotlib / Seaborn** – visualization and reporting  
- **Scikit-learn** – machine learning algorithms (classification & clustering)

---

## ⚙️ Setup Instructions

### 1️⃣ Clone the Repository
git clone https://github.com/<your-username>/<your-repo-name>.git
cd <your-repo-name>

2️⃣ Install Dependencies
Make sure Python is installed, then install dependencies:
pip install -r requirements.txt

3️⃣ Run the Project
Open the notebook in Google Colab or Jupyter Notebook:
Urban_Vulnerability_Mapper.ipynb
Then run all cells sequentially to reproduce results and visualizations.

📂 Repository Structure
File	Description
UrbanMapper.ipynb	Main Google Colab Notebook containing the project code
requirements.txt	Project dependencies
README.md	Project documentation and overview
urban_vulnerability_analysis.png	Visualization output generated from notebook

📊 Outputs and Results
The notebook automatically generates several key outputs:

Feature Importance Graph – identifies critical factors for informal settlements

Confusion Matrix – model accuracy visualization

Vulnerability Clusters – highlights different risk zones

Priority Distribution Bar Chart – summarizes intervention levels

Example Screenshot 
![Urban Vulnerability Analysis](urban_vulnerability_analysis.png)

📈 Impact Metrics
Metric	Description
Informal Settlements Identified	Total number of high-risk informal regions detected
Critical Priority Areas	Areas with highest combined climate & infrastructure vulnerability
High-Risk Informal Zones	Informal settlements exposed to multiple stress factors
Estimated Population Affected	Based on average density of 1,000 residents per settlement

🧩 Ethical Reflection
Key Ethical Considerations:
Data Bias – Use open and diverse datasets (UN-Habitat, World Bank) to ensure fair outcomes.

Privacy – Only anonymized, open-source data is used; no personal or location-traceable data.

Fairness – Promotes equitable access to basic services through transparent AI insights.

Sustainability – Encourages evidence-based, environmentally responsible city planning.

🪙 License
This project is licensed under the MIT License — free to use and modify with attribution.

👩‍💻 Author
PurimTech
AI for Sustainable Development – SDG 11 Project
(Google Colab • GitHub • 2025)

