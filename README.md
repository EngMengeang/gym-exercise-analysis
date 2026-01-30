# Gym Members Exercise Tracking Analysis

## Project Overview
This project analyzes gym member exercise and fitness data to uncover insights about workout patterns, health metrics, and member demographics. The analysis is part of Week 3 coursework for Introduction to Data Science.

**Group**: Group 1 (Eng_Mengeang)

## Dataset Description
The dataset (`gym_members_exercise_tracking.csv`) contains fitness tracking data for 973 gym members across 15 variables:

### Variables
| Column | Description |
|--------|-------------|
| Age | Age of the gym member |
| Gender | Gender of the gym member (Male or Female) |
| Weight (kg) | Member's weight in kilograms |
| Height (m) | Member's height in meters |
| Max_BPM | Maximum heart rate (beats per minute) during workout sessions |
| Avg_BPM | Average heart rate during workout sessions |
| Resting_BPM | Heart rate at rest before workout |
| Session_Duration (hours) | Duration of each workout session in hours |
| Calories_Burned | Total calories burned during each session |
| Workout_Type | Type of workout performed (Cardio, Strength, Yoga, HIIT) |
| Fat_Percentage | Body fat percentage of the member |
| Water_Intake (liters) | Daily water intake during workouts |
| Workout_Frequency (days/week) | Number of workout sessions per week |
| Experience_Level | Level of experience (1=beginner, 2=intermediate, 3=expert) |
| BMI | Body Mass Index, calculated from height and weight |

## Analysis Components
- **Descriptive Statistics**: Min, max, mean calculations for numerical variables
- **Data Classification**: Identification of categorical vs numerical variables
- **Data Visualization**: Charts and plots to explore patterns and relationships
- **Health Metrics Analysis**: Heart rate, calories burned, and BMI trends

## Technologies Used
- **Python 3.x**
- **Pandas**: Data manipulation and analysis
- **Matplotlib**: Data visualization
- **Seaborn**: Statistical graphics

## Setup Instructions
1. Clone the repository
2. Create a virtual environment:
   ```bash
   python -m venv data_pre
## Install Package  : 
pip install -r requirements.txt
## Project Structure 
├── [Eng_Mengeang_Group1_Week3.ipynb](http://_vscodecontentref_/0)   # Main analysis notebook
├── [gym_members_exercise_tracking.csv](http://_vscodecontentref_/1)  # Dataset
├── [requirements.txt](http://_vscodecontentref_/2)                    # Python dependencies
├── data_pre/                          # Virtual environment (not tracked)
└── .gitignore                         # Git ignore rules
