
# Health Assistant

This is a Streamlit application that uses machine learning models to predict three different diseases: Diabetes, Heart Disease, and Parkinson's Disease.

## Getting Started

1. **Install dependencies:**

   ```bash
   pip install streamlit pickle
   ```

2. **Clone the repository:**

   ```bash
   git clone https://github.com/Abhay2132/health_assistant
   ```

3. **Navigate to the project directory:**

   ```bash
   cd health_assistant
   ```

4. **Run the application:**

   ```bash
   streamlit run app.py
   ```

## Usage

The application has a sidebar for navigation. Select the disease you want to predict from the options available. Each disease prediction page has a form where you can enter the required user data. After entering the data, click on the 'Test Result' button to get the prediction.

## File Structure

```
health-assistant/
├── appx.py        # The main script of the application
├── saved_models/  # Directory containing the saved models
│   ├── diabetes_model.sav
│   ├── heart_disease_model.sav
│   └── parkinsons_model.sav
README.md         # This file
```

## Requirements

* Python 3.6 or later
* Streamlit
* pickle

## Deployment

This application can be deployed to a cloud platform like Heroku or AWS for wider accessibility.

## Disclaimer

This application is for informational purposes only and should not be used as a substitute for professional medical advice. Always consult with a healthcare professional for diagnosis and treatment.