# Water Quality Exploratory Data Analysis and Prediction
# Objective
The objective is to evaluate the potability of a water sample for drinking purposes by conducting a thorough analysis of its content. This assessment will help determine whether the water meets the necessary quality and safety standards for human consumption.

# Water Quality Parameters
1. pH: pH is a measure of water's acidity or alkalinity, with a recommended range of 6.5 to 8.5 by WHO. The current study falls within this range at 6.52–6.83.
2. Hardness: Hardness in water is caused by calcium and magnesium salts, affecting soap's ability to lather.
3. TDS: Total dissolved solids in water indicate mineral content, with desirable levels below 500 mg/l for drinking water.
4. Chloramines: Chlorine and chloramine are common disinfectants in water, with safe levels up to 4 mg/L.
5. Sulfate: Sulfates occur naturally and are found in various sources, with concentrations ranging from 3 to 30 mg/L in freshwater.
6. Conductivity: The electrical conductivity of water increases with dissolved solids, with recommended levels below 400 μS/cm by WHO.
7. Organic Carbon: Total Organic Carbon (TOC) measures organic compounds in water, with limits set by US EPA.
8. Trihalomethanes:THMs can be present in chlorinated water, with safe levels up to 80 ppm.
9. Turbidity:Turbidity indicates the presence of solid matter in water, with WHO recommending levels below 5.00 NTU.
10. Potability:Indicates if water is safe for human consumption where 1 means Potable and 0 means Not potable.

# Data Cleaning and Preparation
The first step in this EDA project is to clean and prepare the data for analysis. This includes tasks such as handling missing values, detecting and correcting outliers, and transforming data into appropriate formats.
We use the following libraries to clean and prepare the data:
Pandas
Numpy

For Visualization:
Seaborn
Matplotlib

Initial Analysis
With the exception of the target feature, all other features within the dataset consist of floating-point values, indicating their continuous nature. 
A potential solution is to transform the Potability feature into a categorical variable, allowing for a more structured and meaningful representation in the analysis. 
This conversion can facilitate a better understanding of the data and its potential impact on the target variable.

# Conclusion
The performance metrics of the machine learning models employed in our analysis showcase varying degrees of accuracy. The Decision Tree model achieved an accuracy of 72%, while the Random Forest Classifier demonstrated a higher accuracy at 79%. 
These findings provide valuable insights into the predictive capabilities of these models, laying the foundation for informed decision-making in our analytical pursuits.



