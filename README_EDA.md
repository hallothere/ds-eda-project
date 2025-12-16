
# King County Housing Market — Exploratory Data Analysis (EDA)

## Project Overview

This project presents an exploratory data analysis (EDA) of the **King County housing market**. The goal was twofold:

1. to understand the key drivers of house prices and market behavior, and
2. to identify the **best investment opportunities** for a specific client profile.

---

## Project Steps

### 1. Data Collection and Integration

We collected housing data for King County from two sources:

* **King County house details**
* **King County house sales**

Both tables were fetched, downloaded, and **joined into a single DataFrame**, forming the basis for all subsequent analysis.

---

### 2. Data Cleaning and Preparation

We performed a comprehensive data cleaning process, including:

* Standardizing and unifying column names
* Removing duplicate records
* Identifying and handling missing values
* Correcting data types
* Fixing human errors and inconsistencies in the data

This step ensured data quality and reliability for further analysis.

---

### 3. Initial Exploration and Outlier Handling

We explored each column individually to understand distributions and ranges.
Key actions included:

* Visualizing all variables
* Identifying and removing outliers in continuous variables
* Gaining a clearer understanding of realistic value ranges
* Imputing missing values based on insights gained during exploration

---

### 4. Feature Relationships and Price Drivers

With a cleaned dataset, we focused on **relationships between variables**, especially:

* Factors influencing **house prices**
* The role of **house grade**, and which attributes most strongly affect grading

Correlation analysis and visualizations were used to identify the most impactful features.

---

### 5. Geographic Analysis

We analyzed geographic variables to uncover spatial patterns, including:

* Zip code
* Latitude and longitude

This helped identify **location-based trends**, particularly those related to pricing and market concentration.

---

### 6. Client-Focused Filtering and Selection

After developing a strong understanding of the data, we moved to the second part of the assignment: **finding the best offers for our client**.

The client, **Jennifer Montgomery**, had the following requirements:

* High budget
* Prestige-focused (“show-off”) properties
* Waterfront location
* Recently renovated
* High house grade
* Purchase within one month
* Resale within one year

Using these criteria, we applied a step-by-step filtering process to narrow down the original **21,597 listings** to the **top 3 recommended properties**.

---

### 7. Presentation and Insights

In the final stage, we created a presentation for the client that:

* Provided an overview of the relevant housing market
* Confirmed or challenged initial assumptions about pricing and availability
* Explained the filtering logic transparently
* Positioned the final three properties in comparison to the overall market

This allowed the client to clearly understand both the **market context** and the **rationale behind the recommendations**.

---

## Outcome

The project combines structured EDA with a real-world client scenario, demonstrating how data-driven insights can support **strategic real estate investment decisions**.

Link to the [presentation](https://www.canva.com/design/DAG7SX4wvMY/Vq7v3jn8a2q1x5RjuFqeWw/edit?utm_content=DAG7SX4wvMY&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton)

---

