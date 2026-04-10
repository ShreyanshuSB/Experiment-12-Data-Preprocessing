# Experiment-13
# Name: Shreyanshu Swastik Behera
# PRN: 25070123149
# Batch: ENTC A1

# Title
Python Implementation for Data Binning and Formatting

# Aim
To explore and execute data preprocessing methods using Pandas—specifically Data Binning and Data Formatting—in order to convert raw numerical datasets into organized categorical groups and standardized structures.

# Objectives
To grasp the underlying principles of Data Binning (Binned Analysis).

To categorize continuous numerical data into discrete, manageable "bins."

To implement Data Formatting techniques for maintaining uniform data types and measurement units.

To utilize Pandas methods, such as pd.cut(), for effective data segmentation.

To graphically represent the distribution of binned data utilizing histograms.

# Theory: Data Binning
Data binning, also known as bucketing, is a preprocessing strategy utilized to mitigate minor observational discrepancies by grouping continuous numerical figures into a restricted set of categories or "bins."

# Types of Binning

Equal Width Binning: Divides the variable's overall range into N intervals of identical width.

Equal Frequency Binning: Structures intervals so that an approximately equal number of data points fall into each bin.

Why Binning is Used

Simplification: It groups similar values, making complex datasets easier to interpret.

Noise Reduction: It smooths out minor, insignificant variations in the data.

Categorical Analysis: It translates numerical values into categorical formats, which is highly beneficial for specific machine learning algorithms.

Theory: Data Formatting
Data formatting is the procedure of standardizing and refining data to enable accurate comparisons. Since raw data from diverse sources often varies in type, unit, or structure, formatting ensures consistency.

# Common Formatting Tasks

Unit Standardization: Aligning all measurements to a single standard (e.g., converting miles per gallon to liters per 100km).

Data Type Conversion: Modifying columns to their appropriate data types, such as shifting "Object" strings into "Float" or "Integer" formats for mathematical computation.

Standardization: Ensuring string formats and categorical names follow a consistent case to avoid duplication.

Data Wrangling Operations
Based on the implemented logic, the following wrangling techniques are applied:

Binning Numerical Data: Continuous values (like Student CGPA or Car Prices) are grouped into distinct brackets (e.g., "Low", "Medium", "High") via the pd.cut() function.

Formatting & Type Casting: The .astype() method is employed to convert string-based numbers into functional integers or floats, allowing for statistical operations like .mean() and .max(). Categorical labels are also standardized to ensure accurate frequency counts in .value_counts().

Key Applications
Education: Translating raw exam scores into standard letter grades (A, B, C).

Economics: Segmenting continuous income figures into distinct demographic or tax brackets.

Industry: Categorizing continuous sensor outputs into discrete operational states like "Normal" or "Critical."

# Conclusion
This experiment highlights the critical role of Data Binning and Formatting in the data preparation phase. While binning simplifies complex numerical data and aids in distribution visualization, formatting guarantees that multi-source data is standardized and computationally viable. Together, these preprocessing techniques are vital for maintaining high data quality in any analytical workflow.
