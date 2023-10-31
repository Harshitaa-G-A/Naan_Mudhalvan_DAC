# Naan_Mudhalvan_DAC
Project 7: COVID-19 using Cognos

**Data Preprocessing**
-Import Libraries:
       import numpy as np
       import pandas as pd
-Load the Dataset: 
       data = pd.read_csv('your_dataset.csv')
-Exploratory Data Analysis (EDA):
      data.head()           # View the first few rows of the dataset
      data.info()           # Get information about data types and missing values
      data.describe()       # Generate summary statistics
-Handling Missing Data:
      data.dropna()              # Remove rows with missing data
      data.fillna(value)         # Fill missing values with a specific value
      data.interpolate()         # Use interpolation to fill missing values
-Data CleaningData Cleaning:
      data.drop_duplicates()     # Remove duplicate rows
      data.replace(wrong, right)  # Replace incorrect values with correct ones
-Data Transformation:
      data = pd.get_dummies(data, columns=['categorical_feature'])  # One-hot encoding
      data['numeric_feature'] = preprocessing.scale(data['numeric_feature'])  # Scaling
-Save Processed Data

**Visualization using IBM Cognos**
Step 1: Data Source Connection:
        Launch IBM Cognos and connect to your data source. You can connect to various data sources, including databases, spreadsheets, and web services.
Step 2: Data Exploration:
        After connecting to your data source, explore and select the dataset you want to visualize. This may involve identifying the specific tables, views, or data files 
        to use.
Step 3: Create a New Report:
        Start a new report by selecting the report authoring tool within IBM Cognos. This tool allows you to design and customize your report.
Step 4: Data Items:
        Add data items to your report. Data items are the fields or columns from your dataset that you want to include in your visualization. You can add dimensions 
        (categories) and measures (values) to your report.
Step 5: Visualization Components:
        Choose the type of visualization components you want to use in your report. IBM Cognos offers various options, including charts, graphs, tables, and more.
Step 6: Drag and Drop:
        Drag and drop data items onto the visualization components to map them. For example, you can drag a date field to the x-axis and a numeric field to the y-axis of a 
        chart.
Step 7: Customize Visualizations:
        Customize your visualizations by changing colors, labels, legends, and other design elements to make them more informative and visually appealing.
Step 8: Filters and Prompts:
        Add filters and prompts to your report to allow users to interact with the data. Filters enable users to refine the data they see, and prompts allow for dynamic 
        selections.
Step 9: Aggregations and Calculations:
        Perform aggregations and calculations on your data, such as sum, average, or custom calculations. These can be applied to your data items to derive new insights.
Step 10: Layout and Formatting:
        Adjust the report layout and formatting to make it more user-friendly. You can arrange the visualizations, add titles, and insert headers and footers.

**Visualization Output**

<img width="418" alt="IBMCognosVisualization3" src="https://github.com/Harshitaa-G-A/Naan_Mudhalvan_DAC/assets/146211436/577837d7-b248-4b8f-9b30-8bfc9c420060">
<img width="422" alt="IBMCognosVisualization2" src="https://github.com/Harshitaa-G-A/Naan_Mudhalvan_DAC/assets/146211436/74c096a2-a1b4-42b5-bd6b-8a6cef20c5e3">
<img width="423" alt="IBMCognosVisualization1" src="https://github.com/Harshitaa-G-A/Naan_Mudhalvan_DAC/assets/146211436/fe78df1c-62a7-47b1-896e-c00b86dc1d05">
<img width="370" alt="IBMCognosVisualization4" src="https://github.com/Harshitaa-G-A/Naan_Mudhalvan_DAC/assets/146211436/44670004-0c99-4373-bcfb-62da77413609">


