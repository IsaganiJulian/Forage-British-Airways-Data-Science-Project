# British Airways Data Science Project

## Overview
This project is part of the British Airways Data Science Virtual Experience Program. It focuses on leveraging data science techniques to gain actionable insights from customer feedback and predict booking behavior. The project is divided into two tasks:

1. **Task 1: Customer Feedback Analysis**
   - Scraping customer reviews from online platforms.
   - Performing sentiment analysis to classify reviews as positive, negative, or neutral.
   - Generating word clouds to visualize frequently mentioned terms.
   - Applying topic modeling to identify key themes in customer feedback.

2. **Task 2: Predictive Modeling for Booking Behavior**
   - Analyzing customer booking data.
   - Performing exploratory data analysis (EDA) to understand key trends and patterns.
   - Building machine learning models to predict whether a customer will complete their booking.

## Project Goals
- Enhance understanding of customer sentiments and preferences.
- Identify factors influencing customer booking behavior.
- Provide actionable insights to improve customer experience and optimize business operations.

## Technologies Used
- **Python Libraries:** `pandas`, `numpy`, `matplotlib`, `seaborn`, `scikit-learn`, `nltk`, `gensim`
- **Tools:** Jupyter Notebooks
- **Data Sources:** Customer reviews scraped from Skytrax; Booking data provided in CSV format.

## File Structure
Project Directory Structure
### data

- customer_reviews.csv — Scraped review data

- cleaned_skytrax_reviews.csv — Cleaned scraped data

- customer_booking.csv — Booking data

### notebooks

- Task_1_Customer_Feedback.ipynb — NLP analysis on customer reviews

- Task_2_Booking_Prediction.ipynb — Predictive modeling for bookings

### insights

- Task1.pdf — Task 1 insights

- Task2.pptx — Task 2 insights

  ### Other

- BritishAirways_cert.pdf - Completion certificate
  
- README.md — Project documentation

- requirements.txt — Required Python libraries

- LICENSE — License information




## Key Results

1. **Task 1: Customer Feedback Analysis**
- Sentiment analysis revealed that 57 of reviews were positive, while 42.7% were negative.
- Word clouds highlighted common terms like "flight", "food", "seat", and "service,".
- Topic modeling identified key themes such as punctuality, staff friendliness, and inflight amenities.

2. **Task 2: Predictive Modeling for Booking Behavior**
- The predictive model achieved an accuracy of 85% with a precision of 42% for completed bookings.
- Key features influencing bookings include purchase length of stay, purchase lead time, flight duration, and flight day.

## Future Work
- Incorporate more advanced machine learning models like XGBoost or deep learning techniques.
- Use additional datasets (e.g., demographic or loyalty program data) to improve predictions.
- Automate the review scraping process with APIs or web scraping tools.

## Contributors
Isagani Hernandez – Data Scientist  
[IsaganiHernandez@my.unt.edu]  



