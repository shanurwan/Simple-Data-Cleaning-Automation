# Simple-Data-Cleaning-Automation

🧹 Real Estate Data Cleaning Pipeline (Python)

Overview
This project presents a modular and reusable data cleaning pipeline for a real estate dataset, written in Python using pandas and scikit-learn. The pipeline performs a sequence of preprocessing tasks to prepare raw property listings data for analysis or machine learning models.

💡 Key Features

Location Cleaning: Removes redundant mentions of "Kuala Lumpur".

Price Parsing: Converts price strings like "RM 350,000" into float values.

Room Count Normalization: Handles inconsistent room count formats (e.g., "3+").

Missing Value Imputation: Fills in missing values for numerical features like bathrooms, car parks, and size.

Size Extraction: Extracts numerical size values from text (e.g., "1,200 sqft").

Furnishing Encoding: Encodes furnishing status into numeric categories.

Final Cleanup: Removes any remaining rows with missing values.
