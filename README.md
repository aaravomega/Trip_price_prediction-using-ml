# Trip_price_prediction-using-ml
## Overview
Planning a trip can be overwhelming, especially when it comes to budgeting for flights, accommodations, and transportation. That's where Trip Price Prediction steps in. This tool uses multiple machine learning models to make accurate predictions for flights, hotels, and cabs. You can easily and quickly adjust input parameters such as destination city, duration of stay, and accommodation preferences to instantly receive estimates until it perfectly aligns with your budget, empowering you to craft the ideal itinerary without breaking the bank. 
## Features
Multi-city Support: Currently featuring six major cities and more cities can easily be added in the future.  
Dynamic Input Parameters: Quickly adjust trip details such as source and destination cities, days left until departure, hotel ratings, and trip duration to get tailored predictions that fit your budget.  
Flight Price Prediction: Utilizes Random Forest Regression to estimate flight prices based on the number of days left until departure.  
Hotel Price Estimation: Employs machine learning to predict hotel prices, considering factors such as hotel ratings and user reviews.  
Transportation Cost Calculation: Determines taxi fares based on predicted distances to landmarks.  
## How It Works
Data Preprocessing: Cleans and organizes datasets for flights, hotels, and taxi fares.  
Model Training: Trains machine learning models using relevant features such as days left until departure, hotel ratings, and distance to landmarks.  
User Interaction: Collects user input regarding trip details.  
Prediction Generation: Utilizes trained models to predict flight prices, hotel costs, and taxi fares.  
Output Presentation: Presents estimated expenses for flights, hotels, and transportation, providing a comprehensive view of the trip's total expense.  
## Usage
Go to the google collab link, import the datasets and run the script.  
or  
Clone the repository to your local machine.  
Run the Python script, providing input parameters for your trip.  
Plan your trip with confidence, knowing your budget is in check.  
##Contribution
Contributions to enhance dataset coverage, improve model accuracy, and expand features are welcome. Please submit pull requests with detailed descriptions of changes.

## Future Enhancements
+Datasets of more cities can be easily added in the future without needing to changing the code.  
+More sophisticated machine learning algorithms for improved accuracy.  
+Development of a user-friendly web interface for easier interaction.  
### +Scraping social media and using setiment analysis to show the user the current views of people who are also on trips to the same cities.  
## Disclaimer
Trip Price Prediction is intended for informational purposes only. Actual prices may vary. Always verify prices and availability through official sources before making travel arrangements.
<p align="center">
Happy planning and safe travels!
</p>
