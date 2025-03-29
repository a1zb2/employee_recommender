# Employee Recommender System

## Overview
A Streamlit application that helps match employees based on their skills, profession, and expertise. This tool allows users to find colleagues with similar skills and professional backgrounds, making it ideal for team formation or mentorship pairing.

## Features
- Create a profile with your skills and professional information
- Find colleagues with matching skills and expertise
- Filter employees by department
- Visual representation of match scores
- Download recommendations as CSV

## Installation
1. Clone this repository
2. Install the required packages:
   ```
   pip install -r requirements.txt
   ```
3. Run the application:
   ```
   streamlit run app.py
   ```

## Usage
1. Enter your profile information including name, profession, skills, and email
2. Submit the form to find matching colleagues
3. View the recommendations and match scores
4. Download recommendations as needed

## Technologies Used
- Streamlit for the web application
- pandas and NumPy for data manipulation
- scikit-learn for similarity calculations
- Faker for generating demo data

## Example
The application comes pre-loaded with a database of sample employees with various skills and professions, allowing you to immediately test the recommendation engine.
