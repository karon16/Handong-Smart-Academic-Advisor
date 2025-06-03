

# Smart Academic Advisor for Handong Students

## Project Overview

This project aims to build a smart academic advising system for students at Handong Global University. The system provides AI-driven recommendations to help students plan their academic journey more effectively. Features include lab matching, GPA prediction, course suggestions, and study tips—all tailored to individual profiles.

GitHub Repository: [https://github.com/karon16/Handong-Smart-Academic-Advisor](https://github.com/karon16/Handong-Smart-Academic-Advisor)

## Project Goals

- Recommend research labs using clustering and student interests
- Predict GPA using supervised learning (Linear Regression or Decision Tree Regression)
- Classify study patterns using Decision Tree Classifier to offer actionable advice
- Recommend future courses based on course history and semester progression

## Features

- Cluster-based lab recommendation
- GPA prediction using regression models
- Study tip generation using decision tree classification
- Course planning logic based on Handong's coursebook and academic structure

## Technologies

- Python 3.x
- pandas, numpy
- scikit-learn
- matplotlib, seaborn
- Jupyter Notebooks

## Repository Structure

```

Handong-smart-academic-advisor/
├── README.md
├── data/              # CSV files (students, courses, labs)
├── notebooks/         # Jupyter notebooks (exploration, regression)
├── src/               # Python scripts (lab recommender, GPA model, etc.)
├── requirements.txt   # Python packages used
├── report/            # Final PDF report and assets
└── slides/            # Final presentation slides


```

## How to Clone

```

git clone [https://github.com/karon16/Handong-Smart-Academic-Advisor.git](https://github.com/karon16/Handong-Smart-Academic-Advisor.git)
cd Handong-Smart-Academic-Advisor

```

## How to Use

1. Set up a Python virtual environment:
```

python -m venv venv
source venv/bin/activate      # For Mac/Linux
venv\Scripts\activate         # For Windows

```

2. Install dependencies:
```

pip install -r requirements.txt

```

3. Run and test:
- Use notebooks in `notebooks/` to explore or debug
- Run the full pipeline using `src/main.py`

## Authors

- Team of 4 students, Introduction to AI Class
- Department of Computer Science and Engineering, Handong Global University

 1. Sebastian Sulumo
 2. 윤요한
 3. Sailesh Lama
 4. Christopher Buhendwa Lulando




