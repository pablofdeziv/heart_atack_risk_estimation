# Heart Attack Risk Expert System❤️

Rule-based expert system for estimating heart attack risk based on user input regarding medical and lifestyle factors. Developed as part of the course *Softcomputing* (3rd year of Engineering degree).

## 🚀 Features

- Interactive form with the following inputs:
  - Age and Gender
  - Blood Pressure (systolic & diastolic)
  - LDL Cholesterol levels
  - Smoking habits
  - Diabetes diagnosis
  - Physical activity level
  - Family history of heart disease
- Risk assessment output: Low, Moderate, or High
- Activated rules are displayed for transparency

## 🧠 Inference Engine

- Rule-based system implemented with the `rule_engine` Python library
- Predefined expert rules based on medical guidelines
- Risk level determined by the number and type of activated rules

## 🔍 Example Rules

- **Low risk**: 
  - Age ≤ 40 and not smoker
  - LDL < 100 and not diabetic
  - Active lifestyle (≥150 min/week)

- **Moderate risk**: 
  - Blood pressure in pre-hypertension range
  - LDL ≥ 130 and low activity

- **High risk**:
  - Age > 50 (male) or > 60 (female)
  - LDL ≥ 130 and smoker
  - Family history and low activity

## 📊 Results

- Dynamic feedback per submission
- Displays activated rules and final estimated risk level
- Two example test cases validate the system logic

## 🛠️ Technologies

- Python
- Google Colab
- `rule_engine` for rule evaluation
- `ipywidgets` for form interaction

## ⚙️ How to Run

1. Open the notebook in Google Colab.
2. Fill in the interactive form with your personal data.
3. Press the evaluation button to receive the estimated risk level and the activated rules.

> 📌 This project was developed and tested entirely in **Google Colab**.

> ⚠️ Note: The notebook uses `ipywidgets` and may not render properly on GitHub.  
> We recommend opening it directly in [Google Colab](https://colab.research.google.com) or downloading it and opening in Jupyter Notebook.


## 📝 License

This project is released under the MIT License.
