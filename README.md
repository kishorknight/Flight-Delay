**Author:** Kishor K S

**Training Program:** SkilloVilla Data Science & Machine Learning

**Tools Used:** Python, Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn

# Predicting Flight Delay Using Advanced Machine Learning Algorithms

# Project Overview
This project focuses on predicting flight delays using advanced machine learning techniques. Flight delays cause significant inconvenience for passengers and airlines, making it crucial to develop an accurate 
predictive model. The dataset used for this project includes various flight-related features that help in determining the likelihood of a delay.

# About the Dataset
The dataset consists of 22 features related to flight schedules, airline information, and delay indicators. Below is a brief description of each column:
- Day of Month – The day of the month when the flight occurred.

- Day of Week – The weekday of the flight (starting from Monday).

- Unique Carrier Code – A unique code assigned to each airline.

- Carrier Identification Number – A number assigned by US DOT to identify an airline.

- IATA Carrier Code – Code commonly used to identify airlines.

- Tail Number – A unique identifier for each aircraft.

- Flight Number – The assigned flight number.

- Origin Airport ID – Unique identifier assigned by US DOT for an airport.

- Origin Airport Sequence ID – Sequential ID for the origin airport.

- Origin Airport – Name of the origin airport.

- Destination Airport ID – Unique identifier for the destination airport.

- Destination Airport Sequence ID – Sequential ID for the destination airport.

- Destination Airport – Name of the destination airport.

- Actual Departure Time – Local departure time in hhmm format.

- Departure Delay Indicator – Binary indicator (1=Yes, 0=No) if departure delay is 15 minutes or more.

- Departure Time Block – Hourly interval of departure times.

- Actual Arrival Time – Local arrival time in hhmm format.

- Arrival Delay Indicator – Binary indicator (1=Yes, 0=No) if arrival delay is 15 minutes or more.

- Cancelled Flight Indicator – Binary indicator (1=Yes, 0=No) for flight cancellations.

- Diverted Flight Indicator – Binary indicator (1=Yes, 0=No) for diverted flights.

- Distance – Distance between origin and destination airports (in miles).

- Unnamed: 21 – No description available.

## Methodology 
- Data Preprocessing – Cleaning and handling missing values.

- Exploratory Data Analysis (EDA) & Feature Engineering – Understanding patterns and extracting important features.

- Statistical Analysis – Identifying relationships and significance of different features.

- Model Building & Training – Using various machine learning algorithms to build predictive models.

- Model Evaluation Metrics – Analyzing model performance using accuracy, AUC, precision, recall, etc.

- Hyperparameter Tuning – Optimizing model performance through parameter adjustments.

- Results & Insights – Interpreting results and deriving meaningful conclusion

## Conclusion 
After training and evaluating multiple models, it was found that the Decision Tree classifier performed best on the test dataset with:
- Accuracy: ~93%
- AUC (Area Under Curve): 0.90

