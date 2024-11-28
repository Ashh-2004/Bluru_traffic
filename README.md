# **Vehicle Accident Analysis in Bangalore (1980-2001)**

## **Overview**
This project provides a detailed analysis of vehicle accidents in Bangalore from 1980 to 2001. Using a dataset of accident records, it explores patterns in fatalities, injuries, and vehicle types, while also employing predictive modeling to forecast future trends.

### **Key Highlights**
- **Data Cleaning:** Addressed missing values, created aggregated metrics, and categorized vehicle types.
- **Data Visualization:** Highlighted trends in fatalities, injuries, and accident severity.
- **Predictive Modeling:** Used linear regression to predict future accident statistics.

---

## **Dataset Description**
The dataset includes the following columns:
- **year:** Year of the accident.
- **vehicle_type:** Type of vehicle involved.
- **fatal_male:** Number of male fatalities.
- **fatal_female:** Number of female fatalities.
- **severe_cases:** Severe injury cases.
- **total_fatalities:** Total number of fatalities.
- **total_severe_injuries:** Severe injuries.
- **total_minor_injuries:** Minor injuries.
- **total_non_injured_cases:** Non-injured cases.
- **vehicle_category:** Broader categories (e.g., Two Wheeler, Public Transport, etc.).

---

## **Data Cleaning**
1. **Handling Missing Values:**  
   - Replaced `NaN` values with zeros or removed rows where appropriate.

2. **Column Aggregation:**  
   - Generated new metrics such as `total_fatalities` and `total_injuries` for enhanced analysis.

3. **Vehicle Categorization:**  
   - Grouped vehicles into broader categories:  
     - *Two Wheeler, Public Transport, Four Wheeler, Goods Vehicle, Other.*

---

## **Exploratory Data Analysis (EDA)**
### **Visual Insights**
- **Fatal Accidents Over Time:**  
   Line plots to illustrate trends in fatalities across the years.  
- **Accidents by Vehicle Category:**  
   Pie charts to show the distribution of accidents among different vehicle categories.  
- **Fatal Crashes by Gender:**  
   Histograms comparing male vs. female fatalities.  
- **Non-Injured Cases:**  
   Scatter plots to highlight trends in non-injured cases over time.

---

## **Predictive Modeling**
- **Technique Used:**  
   Linear regression was applied to forecast future male and female fatalities (e.g., predictions for 2024).  
- **Key Findings:**  
   Predictive models demonstrated the potential for future expansion with additional variables.

---

## **Future Work**
- **Enhance Predictive Models:**  
   Introduce advanced machine learning techniques like time series analysis or ensemble methods.
- **Expand Dataset:**  
   Include recent years or other regions for a broader perspective.
- **Additional Variables:**  
   Incorporate factors like road conditions, weather, and driver demographics to refine predictions.

---

## **Acknowledgments**
- **Data Source:**  
   Bangalore Traffic Police Records.  
- **Libraries Used:**  
   Thanks to the Python community for tools like Pandas, Matplotlib, and Scikit-Learn.

---

## **Contact**
For queries or contributions, 
contact:  **[M Ashish Ramana]**  
Email: **[ashishramana2004@gmail.com]**

---