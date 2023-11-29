# Resume Screening with Python

## Overview
This project involves the application of machine learning techniques for the screening of resumes. The goal is to categorize resumes into different job categories using natural language processing and classification algorithms.

## Prerequisites
Ensure you have the following libraries installed:
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- NLTK
- Wordcloud

You can install them using the following command:
```bash
pip install numpy pandas matplotlib seaborn scikit-learn nltk wordcloud
```

## Data
The dataset (`UpdatedResumeDataSet.csv`) contains resumes along with their respective categories. The project involves cleaning the resume text, visualizing the data distribution, and applying machine learning algorithms for classification.


### Resume Screening with Python

#### 1. **Objective:**
   The goal of this project is to develop a system that can automatically categorize and screen resumes based on their content. This can be particularly useful for HR professionals or recruitment teams to efficiently handle a large volume of resumes.

#### 2. **Libraries Used:**
   The project utilizes several Python libraries for data analysis, visualization, and machine learning. These include:
   - `numpy` and `pandas` for data manipulation.
   - `matplotlib` and `seaborn` for data visualization.
   - `sklearn` for machine learning tasks, including the Naive Bayes classifier (`MultinomialNB`), K-Nearest Neighbors (`KNeighborsClassifier`), and other relevant modules.
   - `nltk` for natural language processing tasks.
   - `wordcloud` for creating word clouds.

#### 3. **Data Loading and Exploration:**
   - The project starts by loading a dataset containing resume information (`UpdatedResumeDataSet.csv`).
   - The dataset is explored to understand the distribution of different resume categories.

#### 4. **Data Cleaning:**
   - A new column, `cleaned_resume`, is created to store cleaned versions of the resume text. The cleaning process involves removing URLs, mentions, punctuation, and extra whitespace.

#### 5. **Data Visualization:**
   - Visualizations are created to show the distribution of resume categories and the number of records for each category.

#### 6. **Text Analysis:**
   - Text analysis is performed to identify the most common words in the resumes.
   - Word clouds are generated to visually represent the frequency of words in the cleaned resume text.

#### 7. **Label Encoding:**
   - The 'Category' column is label-encoded to convert categorical labels into numerical format.

#### 8. **Text Vectorization:**
   - The cleaned resume text is converted into numerical features using TF-IDF (Term Frequency-Inverse Document Frequency) vectorization.

#### 9. **Machine Learning Model:**
   - A K-Nearest Neighbors (KNN) classifier is trained using the TF-IDF features to predict the category of a resume.
   - The project uses the One-vs-Rest (OvR) strategy to extend the KNN classifier for multi-class classification.

#### 10. **Model Evaluation:**
   - The accuracy of the KNN classifier is evaluated on both the training and test sets.
   - A classification report is generated to provide additional metrics such as precision, recall, and F1-score for each category.

#### 11. **Conclusion:**
   - The project concludes by providing insights into the performance of the resume screening model and its ability to categorize resumes accurately.



## Usage
1. Clone the repository:
   ```bash
   git clone https://github.com/raghavendranhp/Resume_screening.git
   cd your-repository
   ```

2. Install dependencies:
3. Run the Jupyter Notebook:
4. Follow the instructions in the notebook to execute code cells and explore the project.

## Results
The project achieves [mention accuracy or any other relevant metrics] on the test set. The model has been trained using [algorithm] and exhibits robust performance in categorizing resumes.

## Contributing
I welcome contributions! If you have suggestions, improvements, or new features to add, please fork the repository and submit a pull request.

## License
This project is under the MIT License.

## Author
Raghavendran S,  
Aspiring Data Scientist  
[LinkedIN Profile](https://www.linkedin.com/in/raghavendransundararajan/)  
raghavendranhp@gmail.com  

Thank You !  
Happy Enjoying !


