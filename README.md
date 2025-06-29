# Zylentrix Data Analysis

Welcome to the **Zylentrix Data Analysis** project — a deep dive into understanding student learning behaviors, course engagement, and feedback trends. This project leverages real-world-style data to uncover insights that can help improve digital learning platforms.

## Project Objectives

- Analyze enrollment patterns and demographics of students.
- Study course activity: time spent, engagement, and completion rates.
- Derive insights from feedback ratings and text.
- Visualize key trends to support data-driven decision making.

## Project Structure

zylentrix-data-analysis/
├── data/ │
          ├── students.csv │
          ├── course_activity.csv 
          │── feedback.csv
├── zylentrix-analysis.ipynb
├── requirements.txt
└── README.md


## Datasets Used

1. **students.csv** – Basic demographic and enrollment details:
   - `Student_ID`, `Name`, `Age`, `Gender`, `Location`, `Enrolment_Date`

2. **course_activity.csv** – Daily activity logs:
   - `Student_ID`, `Course_ID`, `Date`, `Time_Spent_Minutes`, `Completion_Percentage`

3. **feedback.csv** – Student feedback after course completion:
   - `Student_ID`, `Course_ID`, `Rating`, `Feedback_Text`

> *Note: The data used here is anonymized and intended solely for demonstration/academic purposes.*

## Key Insights

- Certain locations showed consistently higher engagement levels.
- Students who spent more than **30 minutes/day** had **50% higher completion rates**.
- Feedback ratings positively correlated with time spent — more engaged students left better feedback.
- Text analysis of feedback revealed frequent keywords: *“helpful”*, *“too fast”*, *“need examples”*.

## How to Run

1. **Clone the repository**:
   ```bash
   git clone https://github.com/kiran86/zylentrix-data-analysis.git
   cd zylentrix-data-analysis
2. **Install dependencies**:
   ```bash
   pip install -r requirements.txt
3. **Launch the notebook**:
   ```bash
   jupyter notebook zylentrix-analysis.ipynb
