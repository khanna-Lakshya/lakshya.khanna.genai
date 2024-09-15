# COVID-19 Symptom Data Generation and Sorting

## Project Overview
This project generates random data for COVID-19 symptoms, stores the data in an Excel file, and sorts it based on a specified symptom parameter. The parameters used in the model include:
- Fever (in °C)
- Cold (intensity on a scale of 0 to 10)
- Shivering (intensity on a scale of 0 to 10)
- Weight loss (in kg)

The dataset includes 100 randomly generated records, and the data can be sorted by any of the parameters.

## Features
- Generate 100 random records of COVID-19 symptoms.
- Save the data in an Excel file (`covid_symptoms_data.xlsx`).
- Sort the data by a chosen symptom parameter (e.g., fever, cold, shivering, weight loss).
  
## Technologies Used
- **Python** for data generation and processing.
- **Pandas** library for data manipulation and saving to an Excel file.
- **Random** module for generating random symptom values.

## Code Overview
### Data Generation
The data is generated with the following ranges:
- **Fever**: Random body temperature between 36°C and 40°C.
- **Cold**: Cold intensity is randomly selected between 0 and 10.
- **Shivering**: Shivering intensity is randomly selected between 0 and 10.
- **Weight Loss**: Random weight loss between 0 and 10 kg.

### Sorting Functionality
The data is sorted based on an input parameter using the `sort_values()` method from the Pandas library.

### Saving to Excel
The generated data is saved to an Excel file using the `to_excel()` method from Pandas.

## Usage Instructions
1. Clone the repository to your local machine.
2. Ensure you have Python installed (preferably version 3.x).
3. Install the required dependencies by running:
   ```bash
   pip install pandas
