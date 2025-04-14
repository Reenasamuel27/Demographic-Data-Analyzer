# Demographic-Data-Analyzer



This project is part of the freeCodeCamp.org Python curriculum challenge. The goal is to analyze demographic data using the `pandas` library in Python. The data is based on the 1994 U.S. Census database and is provided by the UCI Machine Learning Repository.

## 📁 Project Structure

- `demographic_data_analyzer.py`: Main script where all the data analysis functions are implemented.
- `main.py`: Entry point for running and testing the project manually.
- `test_module.py`: Contains unit tests to verify the correctness of your functions.
- `adult.data.csv`: Dataset file (make sure it's in the same directory or properly referenced).

## 🚀 Getting Started

You will be working on this project using **Gitpod** with the provided starter code.

### Prerequisites

- Python 3.x
- pip
- `pandas` library installed (`pip install pandas`)

### Setup

1. Clone the repository or open it in Gitpod.
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
Run the main script to test your functions:

bash
Copy
Edit
python main.py
📊 Dataset
Each record in the dataset includes demographic information such as age, education, occupation, race, and salary. Example:

age	workclass	education	marital-status	occupation	race	sex	hours-per-week	native-country	salary
39	State-gov	Bachelors	Never-married	Adm-clerical	White	Male	40	United-States	<=50K
✅ Tasks to Complete
Use pandas to answer the following:

How many people of each race are represented in the dataset?

What is the average age of men?

What percentage of people have a Bachelor's degree?

What percentage of people with advanced education (Bachelors, Masters, or Doctorate) make more than 50K?

What percentage of people without advanced education make more than 50K?

What is the minimum number of hours a person works per week?

What percentage of people working the minimum number of hours earn >50K?

Which country has the highest percentage of people earning >50K, and what is that percentage?

What is the most popular occupation for those earning >50K in India?

🔧 Implementation
Update the demographic_data_analyzer.py file to include the logic for these questions. All variables initially set to None should be replaced with your computations.

🔄 Round all decimals to the nearest tenth where appropriate.

🧪 Testing
Run tests to verify your solution:

bash
Copy
Edit
python main.py
All tests from test_module.py will be executed.

📬 Submission
When you're ready, copy the project’s URL from Gitpod and submit it to the freeCodeCamp platform.

📚 Resources
Python for Everybody (14 hrs)

Analyze Data with Python Pandas (10 hrs)

UCI Machine Learning Repository - Adult Dataset

