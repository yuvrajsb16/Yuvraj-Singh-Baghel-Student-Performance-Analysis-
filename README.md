# AI-Assisted Student Performance Analysis and Prediction

**Student:** Yuvraj Singh Baghel  
**Programme:** AICTE | IBM SkillsBuild Data Analytics with AI Internship 2026

## Description
This beginner-level project uses a generated synthetic dataset to demonstrate a small data analytics and machine-learning workflow. It explores study hours, attendance, assignment completion and marks, then trains a Random Forest classifier to demonstrate pass/fail prediction.

> The dataset is synthetic and is only for learning. It does not contain real student records and should not be used for real educational decisions.

## Files
- `YuvrajSinghBaghel_StudentPerformanceAnalysis.ipynb` — notebook with code, charts and explanations.
- `requirements.txt` — Python dependencies.
- `YuvrajSinghBaghel_ProjectReport.docx` — project report.

## Dataset
The notebook generates 250 synthetic rows with a fixed random seed, so no external dataset download is required. For future development, a real dataset could be sourced from the [UCI Machine Learning Repository](https://archive.ics.uci.edu/), after checking its licence and suitability.

## Technologies
- Python
- pandas and NumPy
- Matplotlib
- scikit-learn
- Jupyter Notebook

## Setup and run
1. Install Python 3.10 or newer.
2. Open a terminal in the project folder.
3. (Recommended) Create and activate a virtual environment.
4. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

5. Start Jupyter:

   ```bash
   jupyter notebook
   ```

6. Open `YuvrajSinghBaghel_StudentPerformanceAnalysis.ipynb` and run cells from top to bottom.

## Method
1. Generate a synthetic dataset.
2. Inspect data types, summary statistics and missing values.
3. Plot simple relationships.
4. Split the data into training and testing sets.
5. Train a Random Forest classifier.
6. Evaluate it using accuracy, classification report and confusion matrix.

## Limitations
The dataset is artificial and the model is a learning demonstration only. Reported metrics are not evidence of real-world predictive performance. Real deployment would require representative data, validation, consent, privacy protection and fairness checks.
