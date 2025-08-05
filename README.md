  Naive Bayes Classifier - Social Network Ads 

This project implements the **Naive Bayes classification algorithm** to predict whether a user will purchase a product based on **Age** and **Estimated Salary**, using a dataset of social network advertisements.

---

##  Project Structure

NaiveBayes-SocialAds/
│
├── Social_Network_Ads.csv # Dataset
├── naive_bayes_classifier.py # Python code
├── README.md # Project documentation
└── visuals/ # (Optional) Contains saved plots




## Dataset Description

- **Source**: Kaggle / SuperDataScience
- **File**: `Social_Network_Ads.csv`
- **Features**:
  - `User ID` – Identifier (not used in training)
  - `Gender` – (Optional for classification)
  - `Age` – Independent variable
  - `EstimatedSalary` – Independent variable
  - `Purchased` – Dependent variable (0 or 1)



## 🛠Tech Stack

- **Language**: Python 3
- **Libraries**:
  - NumPy
  - Pandas
  - Matplotlib
  - Seaborn
  - scikit-learn

---

##  Objective

To build a **binary classification model** using Naive Bayes that predicts whether a user purchases a product based on demographic features.



## Workflow

1. **Data Preprocessing**
   - Import dataset
   - Handle missing values (if any)
   - Label encoding (if gender used)
   - Feature Scaling

2. **Train-Test Split**
   - 75% for training, 25% for testing

3. **Model Training**
   - Gaussian Naive Bayes: `sklearn.naive_bayes.GaussianNB`

4. **Evaluation**
   - Confusion Matrix
   - Accuracy Score
   - Classification Report

5. **Visualization**
   - Decision boundary visualization (Train/Test)
   - Confusion matrix heatmap



##  Results

- Trained model using **Age** and **EstimatedSalary**
- Accuracy: ~88–90% (varies slightly with random state)
-  Confusion Matrix confirms good performance
-  Naive Bayes handles Gaussian-distributed features effectively


## Sample Output

Accuracy Score: 0.89
Confusion Matrix:
[[65 3]
[ 7 25]]



##  How to Run

1. **Clone the repository**:

```bash
git clone https://github.com/yourusername/naive-bayes-social-ads.git
cd naive-bayes-social-ads
Install dependencies:

bash
Copy
Edit
pip install numpy pandas matplotlib seaborn scikit-learn
Run the code:

bash
Copy
Edit
python naive_bayes_classifier.py
Possible Enhancements
Add Gender as a feature (with encoding)

Try different models: SVM, KNN, Decision Trees

Tune parameters using GridSearchCV

Deploy using Flask/Streamlit

 References
Scikit-learn Naive Bayes

Original Dataset - Social Network Ads

Machine Learning A-Z™ Course

🙋‍♀️ Author
Bhavageetha S
Technical Coordinator | ML & Web Development Enthusiast
🔗 LinkedIn • 💻 GitHub

---










Ask ChatGPT
