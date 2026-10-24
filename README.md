# Femora — Explainable AI for PCOS Risk Assessment

**Understand • Predict • Live Better**

Femora is a research prototype that uses an Artificial Neural Network (ANN) to estimate PCOS-associated risk from selected health and lifestyle inputs. It combines an interactive Streamlit application with explainable AI techniques and lifestyle guidance.

> **Disclaimer:** Femora is an academic research prototype, not a medical diagnostic tool. Its outputs are not a substitute for professional medical evaluation.

## 🌐 Live Application

**Try Femora:** https://femora-pcos-wellness-abydthkx4jaash5hv8zedk.streamlit.app/

## 🎯 Project Objectives

- Develop an ANN-based approach for PCOS-associated risk estimation.
- Provide an interactive interface for entering relevant health and lifestyle information.
- Explore model explanations using SHAP and LIME.
- Present general lifestyle guidance related to nutrition, physical activity, sleep, and stress management.
- Make the research workflow accessible through a web application.

## ✨ Key Features

- **Interactive assessment:** Collects user-provided health and lifestyle inputs.
- **ANN prediction:** Uses a trained Artificial Neural Network to generate a model output.
- **SHAP analysis:** Examines feature contributions to model predictions.
- **LIME explanation:** Provides a local explanation for an individual prediction.
- **Lifestyle guidance:** Displays general wellness recommendations.
- **Streamlit interface:** Provides a browser-based application.

## 🧠 Methodology

The project workflow consists of:

1. **Data preparation:** Load and inspect the dataset, handle missing values where required, and prepare features for modelling.
2. **Preprocessing:** Apply the encoding and scaling procedures used during model development.
3. **Model development:** Train an Artificial Neural Network for the project's prediction task.
4. **Evaluation:** Assess performance using the evaluation metrics calculated during experimentation.
5. **Explainability:** Apply SHAP and LIME to examine model behaviour.
6. **Application development:** Integrate the saved model and preprocessing artifacts into Streamlit.
7. **Deployment:** Host the application using Streamlit Community Cloud.

## 🏗️ Project Structure

```text
Femora-PCOS-Wellness/
├── app.py
├── requirements.txt
├── pcos_ann_model.keras
├── pcos_scaler.pkl
├── feature_names.pkl
├── README.md
├── notebooks/
│   └── Femora_ANN_Development.ipynb

```


## 🛠️ Technologies Used

- Python
- TensorFlow / Keras
- Streamlit
- NumPy and Pandas
- Scikit-learn
- SHAP
- LIME
- Joblib
- Google Colab
- GitHub
- Streamlit Community Cloud

## 🚀 Run Locally

### 1. Clone the repository

```bash
git clone <YOUR_GITHUB_REPOSITORY_URL>
cd Femora-PCOS-Wellness
```

### 2. Create a virtual environment (recommended)

```bash
python -m venv .venv
```

Activate it on Windows:

```powershell
.venv\Scripts\Activate.ps1
```

### 3. Install dependencies

```bash
python -m pip install -r requirements.txt
```

### 4. Launch the application

```bash
python -m streamlit run app.py
```

Open the local URL displayed in the terminal.

## 📊 Dataset and Evaluation

- **Dataset name/source:** [Add the actual dataset name and source]
- **Prediction target:** [Describe the target variable used during training]
- **Preprocessing:** [Document the actual encoding, scaling, and missing-value handling]
- **Evaluation metrics:** [Add the measured test and validation results]
- **Known limitations:** The model's predictions and probability calibration require appropriate validation. Extreme output values should not be interpreted as medically confirmed risk.

Include only metrics and dataset details verified from the actual experiments.

## 🔍 Explainable AI

Femora incorporates two complementary explanation methods:

- **SHAP:** Used to investigate how input features contribute to model output.
- **LIME:** Used to approximate model behaviour locally around an individual input.

These explanations describe model behaviour; they do not establish medical causation.

## ⚠️ Limitations and Responsible Use

- The application is intended for research and educational demonstration.
- Model outputs depend on the dataset, preprocessing, and training procedure.
- Prediction reliability and probability calibration require further evaluation.
- SHAP and LIME explanations may be affected by model limitations and data quality.
- Users should consult qualified healthcare professionals for medical assessment and advice.

## 📁 Research Materials

- **Source code:** Available in this repository.
- **Model-development notebook:** `notebooks/Femora_ANN_Development.ipynb`
- **IEEE DataPort:** [Add the actual dataset or project URL, if applicabl]
- **Project presentation:** [Add the presentation link when available]

## 👩‍💻 Project Information

- **Project:** Femora — An Explainable ANN-Based PCOS Risk Assessment and Lifestyle Guidance Research Prototype
- **Author(s):** Chittaloori Likhitha
- **Institution:** Amrita Vishwa Vidyapeetham, Coimbatore
- **Project type:** Academic research project

## 📜 License

[Add the license selected for this project. If no license has been selected, leave this section pending.]

---

Femora is intended to support research and exploration of explainable AI in women's health. It is not intended to diagnose, treat, or prevent any medical condition.# Femora-PCOS-Wellness
Femora — An Explainable ANN-Based PCOS Risk Assessment and Lifestyle Guidance Research Prototype
