# Task 1 - Image classification + OOP
In this task, you need to use a publicly available simple MNIST dataset and build 3 classification models around it. It should be the following models:
 - Random Forest;
 - Feed-Forward Neural Network;
 - Convolutional Neural Network;

Each model should be a separate class that implements MnistClassifierInterface with 2 abstract methods - train and predict. Finally, each of your three models should be hidden under another MnistClassifier class. MnistClassifer takes an algorithm as an input parameter.
Possible values for the algorithm are: cnn, rf, and nn for the three models described above.


## 📌 Overview
This repository contains a **Jupyter Notebook** that provides a solution to **Task 1**, completed by **Opalinskyi Ivan**.  
It includes **data analysis, preprocessing, and visualization**.

## 📂 Project Structure
```plaintext
│── Task_1_Opalinskyi_Ivan.ipynb   # Jupyter Notebook with the solution
│── requirements.txt                # List of dependencies
│── README.md                       # Project documentation
```
## ⚙️ Setup
```plaintext
1️⃣ Prerequisites
   - Ensure you have Python 3.x installed.
   - Check your Python version by running:
     $ python --version

2️⃣ Install Dependencies
   - If a `requirements.txt` file is available, install dependencies using:
     $ pip install -r requirements.txt
   - If no `requirements.txt` file is available, manually install required libraries:
     $ pip install numpy pandas matplotlib seaborn scikit-learn

3️⃣ Run Jupyter Notebook
   - Start Jupyter Notebook:
     $ jupyter notebook
   - Open `Task_1_Opalinskyi_Ivan.ipynb` and execute the cells.

```

## 📝 Solution Explanation

The solution follows a structured approach to solving the given task:

1️⃣ **Problem Understanding**  
   - The task involves data analysis and preprocessing.  
   - The goal is to clean and analyze the dataset.  

2️⃣ **Data Loading & Preprocessing**  
   - The dataset is loaded using `pandas.read_csv()` (if applicable).  
   - Missing values are handled appropriately.  
   - Data is transformed for further analysis.  

3️⃣ **Exploratory Data Analysis (EDA)**  
   - Summary statistics are generated using `pandas.describe()`.  
   - Data distributions are visualized using `matplotlib` and `seaborn`.  
   - Correlations and patterns are identified.  

4️⃣ **Algorithm Implementation**  
   - The program applies machine learning techniques.  
   - If applicable, the data is split into training and testing sets.  
   - The implemented model is evaluated based on performance metrics.  

5️⃣ **Results & Conclusion**  
   - Key findings are summarized.  
   - Recommendations are made based on the results.

## 👤 Author

**Opalinskyi Ivan**  
 - 📧 Email: ivanopaliskij@gmail.com
 - 💼 LinkedIn: https://www.linkedin.com/in/ivan-opalinskyi/
 - 📌 GitHub: https://github.com/IvanOpalinskij
