
# Student Math Score Predictor

##  [Live]()

## Project Overview
This repository contains the implementation of a **web-based application** to predict students' math scores using various machine learning algorithms. The tool is designed to help educators, administrators, and parents understand potential academic outcomes based on demographic and performance factors.

### Key Features
- Predict students' math scores based on input factors such as:
  - Gender
  - Ethnicity
  - Parental education level
  - Test preparation course completion status
- User-friendly web interface with responsive design.
- Deployed on **AWS Elastic Beanstalk** for scalability and reliability.

## Skills and Technologies
- **Machine Learning:** CatBoost, scikit-learn, and more
- **Programming Language:** Python
- **Web Framework:** Flask
- **Frontend:** HTML, CSS
- **Cloud Services:** AWS Elastic Beanstalk, AWS CodePipeline

## Project Structure
```
MLPROJECT
├── .ebextensions
├── artifacts
│   └── data.csv
│   └── model.pkl
│   └── preprocessor.pkl
│   └── train.csv
│   └── test.csv
├── catboost_info
│   ├── learn
│   ├── tmp
│   └── catboost_training.json
├── logs
│   └── [Log files for training and debugging]
├── notebook
│   └── 1. EDA STUDENT PERFORMANCE.ipynb
│   └── 2. MODEL TRAINING.ipynb
├── src
│   ├── components
│   │   └── [Modules for data ingestion, transformation, and training]
│   ├── pipeline
│   │   └── [Training and prediction pipelines]
│   └── utils.py
├── static
│   └── styles.css
├── templates
│   └── home.html
├── application.py
├── requirements.txt
├── setup.py
├── Readme.md
```

## Installation Guide
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/student-math-score-predictor.git
   cd student-math-score-predictor
   ```
2. Create a virtual environment and activate it:
   ```bash
   python -m venv venv
   source venv/bin/activate  # For Linux/Mac
   venv\Scriptsctivate   # For Windows
   ```
3. Install the required packages:
   ```bash
   pip install -r requirements.txt
   ```
4. Run the application locally:
   ```bash
   python application.py
   ```
   Access the app at `http://127.0.0.1:5000`.

## Deployment
The project is deployed using various deployment techniques:

- [For Deployment Using AWS Beanstalk & Code Pipeline](https://github.com/vishalsinghblr/AWS-Deployment-EBN-CP)
  
## Logs
All training and application logs are stored in the `logs` folder for debugging and analysis.

## License
This project is licensed under the MIT License. See the `LICENSE` file for details.

## Contributing
Contributions are welcome! Please open an issue or submit a pull request to improve this project.

## Connect
Connect with me on [LinkedIn](https://www.linkedin.com/in/vishalsinghblr/).

---

Feel free to raise any issues or suggestions in the repository's **Issues** tab.
