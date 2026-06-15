# 💊 Pharma Sales Forecasting & Analytics  

A Data Science project applied to the pharmaceutical sector.  
We analyze and predict medication sales using Machine Learning models and time series forecasting, featuring interactive visualizations in Streamlit.  

---

## 📂 Repository Structure

```plaintext
├── data/
│   ├── raw/              # Original data (Kaggle)
│   ├── processed/        # Processed data
│   ├── train/            # Training set
│   └── test/             # Testing set
├── docs/
│   ├── artifacts/        # KPIs, rankings, metrics
│   ├── plots/            # Generated plots
│   ├── negocio.pptx      # Business presentation
│   └── ds.pptx           # Technical presentation
├── notebooks/
│   ├── 01_Fuentes.ipynb
│   ├── 02_LimpiezaEDA.ipynb
│   └── 03_Entrenamiento_Evaluacion.ipynb
├── src/
│   ├── utils.py
│   ├── data_processing.py
│   ├── training.py
│   ├── evaluation.py
│   ├── generate_kpis.py
│   └── plots.py
├── app_streamlit/
│   ├── app.py            # Interactive dashboard
│   └── requirements.txt  # Dependencies
├── models/
│   └── final_model.pkl   # Trained model
├── memoria.md            # Technical report
└── README.md

# 1. Clone the repository
git clone [https://github.com/YourUsername/pharma-sales-forecasting.git](https://github.com/YourUsername/pharma-sales-forecasting.git)
cd pharma-sales-forecasting

# 2. Create and activate a virtual environment
python -m venv venv
source venv/bin/activate  # on Windows: venv\Scripts\activate

# 3. Install dependencies
pip install -r requirements.txt

# 4. Process data, train, and evaluate
python src/data_processing.py
python src/training.py
python src/evaluation.py

# 5. Generate KPIs file
python src/generate_kpis.py

# 6. Launch the dashboard
streamlit run app_streamlit/app.py


Here is the fully translated English version of your `README.md` file. You can copy the code block below and paste it directly over your current README file:

```markdown
# 💊 Pharma Sales Forecasting & Analytics  

A Data Science project applied to the pharmaceutical sector.  
We analyze and predict medication sales using Machine Learning models and time series forecasting, featuring interactive visualizations in Streamlit.  

---

## 📂 Repository Structure

```plaintext
├── data/
│   ├── raw/              # Original data (Kaggle)
│   ├── processed/        # Processed data
│   ├── train/            # Training set
│   └── test/             # Testing set
├── docs/
│   ├── artifacts/        # KPIs, rankings, metrics
│   ├── plots/            # Generated plots
│   ├── negocio.pptx      # Business presentation
│   └── ds.pptx           # Technical presentation
├── notebooks/
│   ├── 01_Fuentes.ipynb
│   ├── 02_LimpiezaEDA.ipynb
│   └── 03_Entrenamiento_Evaluacion.ipynb
├── src/
│   ├── utils.py
│   ├── data_processing.py
│   ├── training.py
│   ├── evaluation.py
│   ├── generate_kpis.py
│   └── plots.py
├── app_streamlit/
│   ├── app.py            # Interactive dashboard
│   └── requirements.txt  # Dependencies
├── models/
│   └── final_model.pkl   # Trained model
├── memoria.md            # Technical report
└── README.md

```

---

## ⚙️ Installation and Execution

```bash
# 1. Clone the repository
git clone [https://github.com/YourUsername/pharma-sales-forecasting.git](https://github.com/YourUsername/pharma-sales-forecasting.git)
cd pharma-sales-forecasting

# 2. Create and activate a virtual environment
python -m venv venv
source venv/bin/activate  # on Windows: venv\Scripts\activate

# 3. Install dependencies
pip install -r requirements.txt

# 4. Process data, train, and evaluate
python src/data_processing.py
python src/training.py
python src/evaluation.py

# 5. Generate KPIs file
python src/generate_kpis.py

# 6. Launch the dashboard
streamlit run app_streamlit/app.py

```

---

## 📊 Implemented Models

* ARIMA and SARIMAX
* Random Forest
* Gradient Boosting
* XGBoost
* **CatBoost (Winner 🏆)** - KMeans Clustering
* *(Prophet reserved for future work)* ---

## ✨ Key Results

* MAPE < 2% in sales forecasting (**CatBoost**).
* Identification of dominant categories via Pareto analysis.
* Temporal segmentation and clustering to detect consumption patterns.
* Interactive dashboard with granularity filters, date ranges, and business visualizations.

---

## 📌 Dataset

[Kaggle: Pharma Sales Data](https://www.kaggle.com/datasets/milanzdravkovic/pharma-sales-data)

---

## 📜 License

No license.

```

