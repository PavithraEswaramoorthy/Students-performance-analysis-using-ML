# Students Performance Analysis using Machine Learning

This project applies machine learning techniques to analyze student performance based on academic grades and predict their overall grade classification.

## Features
- **Data Analysis:** Uses Pandas, Seaborn, and Matplotlib for data visualization and exploration.
- **Machine Learning Models:** Implements multiple classification models to predict student performance.
- **Performance Evaluation:** Compares different models based on accuracy scores.

## Repository
[GitHub Repository](https://github.com/PavithraEswaramoorthy/Students-performance-analysis-using-ML)

## Installation & Setup

1. Clone the repository:
   ```sh
   git clone https://github.com/PavithraEswaramoorthy/Students-performance-analysis-using-ML.git
   cd Students-performance-analysis-using-ML
   ```
2. Install dependencies:
   ```sh
   pip install pandas seaborn matplotlib scikit-learn xgboost
   ```
3. Run the analysis script:
   ```sh
   python main.py
   ```

## Project Structure
```
Students-performance-analysis-using-ML/
│── AML_MINI_PROJECT.ipynb
│── README.md
```

## Dataset
- The dataset includes features such as CGPA scores for different academic years and the final grade classification.
- Preprocessing steps include dropping unnecessary columns and splitting data into training and testing sets.

## Models Implemented
| Model                  | Accuracy |
|------------------------|----------|
| DecisionTreeClassifier | 99.8%    |
| RandomForestClassifier | 99.8%    |
| XGBClassifier          | 99.8%    |
| LogisticRegression     | 90.2%    |
| AdaBoostClassifier     | 99.4%    |
| SVC                    | 96.4%    |
| GaussianNB             | 96.6%    |

## Technologies Used
- **Libraries:** Pandas, Seaborn, Matplotlib, Scikit-learn, XGBoost
- **Machine Learning Techniques:** Decision Trees, Naive Bayes, Random Forest, XGBoost, Logistic Regression, SVM, and AdaBoost.

## License
This project is licensed under the [LICENSE](LICENSE).
