# Food Delivery Analysis

## Project Overview

This project aims to analyze the delivery time efficiency within the food delivery ecosystem, focusing on the timely pickup of meals from restaurants. By investigating various factors that influence pickup times, we aim to provide actionable recommendations for optimizing delivery operations and enhancing customer satisfaction.

## Dataset

- **Name:** Call Center Restaurant Orders Dataset
- **Description:** This dataset contains details of the orders placed by customers and includes information such as the time the customer placed the order, the time the order was placed at the restaurant, the time the driver arrived at the restaurant, delivery time, and more.
- **Source Link:** [Dataset Source](https://github.com/firodiaPurva/Food-Delivery-Analysis/blob/main/call-center_restaurant-dataset.xlsx)

## Key Questions Addressed

1. How many times do drivers take more than 30 minutes to arrive at the restaurant?
2. What are the factors influencing pickup times, including restaurant location, kitchen preparation times, traffic conditions, and delivery partner availability?

## Possible Sources of Bias

- **Location Bias:** Bias towards or against certain delivery locations based on factors such as safety concerns, familiarity, or perceived tipping habits.
- **Customer Bias:** Prioritization of deliveries to specific customers perceived as more generous with tips.
- **Time-of-Day Bias:** Preferences for working during specific times of the day or week.
- **Weather Bias:** Impact of adverse weather conditions on driver behavior.
- **Operational Bias:** Bias in the allocation of resources and operational decisions, such as prioritizing profitability over service quality.

## Procedure

1. **Renaming Columns for Consistency**
2. **Removing Dollar Signs**
3. **Dealing with Missing Values**
   - Dropped rows with missing values.
4. **Defining Function to Calculate Time Difference in Seconds**
5. **Calculating Time Taken by Driver to Arrive at the Restaurant**
   - Added columns for time taken in seconds and minutes.
6. **Removing Negative Values**
7. **Resetting the Index**

## Visualization and Analysis

1. **Line Plot:** Time taken by the driver to arrive at the restaurant in minutes for each record.
2. **Histogram:** Distribution of time taken by the driver to arrive at the restaurant.
3. **Kernel Density Estimation:** Smooth estimate of the probability density function for the dataset.

## Key Findings

- **23.09%** of the time, drivers arrive 30 minutes late for food or order pickup from a restaurant after the food is ready for pickup.

## Conclusion

This project provides valuable insights into the dynamics of meal pickups in the food delivery industry. By understanding the challenges and opportunities in this phase of the delivery process, food delivery platforms and restaurants can make informed decisions and implement effective strategies to enhance customer satisfaction.

## Running the Jupyter Notebook

To run the Jupyter Notebook for this project, follow these steps:

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/firodiaPurva/Food-Delivery-Analysis
   cd Food-Delivery-Analysis
   ```

2. **Create a Virtual Environment:**

   ```bash
   python -m venv env
   ```

3. **Activate the Virtual Environment:**

   - On Windows:

     ```bash
     .\env\Scripts\activate
     ```

   - On macOS and Linux:

     ```bash
     source env/bin/activate
     ```

4. **Launch Jupyter Notebook:**

   ```bash
   jupyter notebook
   ```

5. **Open and Run the Notebook:**

   Open the `Food Delivery Analysis.ipynb` notebook file and run the cells to execute the analysis.

