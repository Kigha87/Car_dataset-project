# Car_dataset-project


## Table of Content
1. [Project Objectives](#project-objectives)
2. [Project Overview](#project-overview)
3. [Data Sources](#data-sources)
4. [Insights](#insights)


### Project Objectives
- The objectives here is to clean, transform and perform analysis using python as the tool.

### Project Overview

### DATASET CLEANING
1. Handling Missing Data

   
3. Data Type Conversion

   
5. Filtering Data

   
7. String Operations

   
9. Cleaned Dataset

    


###FEATURE ENGINEERING
1. Creating New Columns

   


### EXPLORATORY DATA ANALYSIS (EDA)
1. Descriptive Statistics


   
3. Group Analysis

![Screenshot 2025-04-01 at 15 27 14](https://github.com/user-attachments/assets/568a7116-43e2-42f3-b1ef-4bb54a4958de)

   
5. Visualizations

<img width="884" alt="Screenshot 2025-04-01 at 15 22 10" src="https://github.com/user-attachments/assets/83ecf707-0a57-4a0b-b286-95013939467a" />

<img width="927" alt="Screenshot 2025-04-01 at 15 22 32" src="https://github.com/user-attachments/assets/2bff8432-2719-4e15-a264-6928565e7d13" />

<img width="932" alt="Screenshot 2025-04-01 at 15 22 51" src="https://github.com/user-attachments/assets/85e5f0d2-d525-4d8a-9e3f-644d9c709613" />

<img width="927" alt="Screenshot 2025-04-01 at 15 24 49" src="https://github.com/user-attachments/assets/07fc38e2-57c2-47d1-bacb-7fcc63083a9f" />

   
7. Correlation Analysis

![Screenshot 2025-04-01 at 15 19 12](https://github.com/user-attachments/assets/fa156bf5-e31c-4245-bce0-7d44278693da)


### Data Sources
  import numpy as np
  import pandas as pd
  import matplotlib.pyplot as plt
  import seaborn as sn
  from google.colab import drive
  drive.mount('/content/drive')

  ### Loading Data
  df_car = pd.read.csv('/content/drive/Mydrive/Datasets/data.csv')


### Insights
1. Written Summary
   - The analysis reveals distinct trends in pricing, performance, driventrain influence and fuel efficiency across different
     vehicles categories. Larger vehicles, such as SUVs and Trucks, tend to have higher MSRPs,
     suggesting that size plays a significant role in determining vehicle price. Also, smaller
     vehicles are more affordable, making them attractive to budget-concious. Additionally,
     horsepower is strongly correlated with MSRP, indicating that vehicles with more powerfull engines tend to cost more.
     However, some outliers exist, particularly in the high performance and Luxury Segments.

     Drivetrain configuration also show a noticeable impact on price. All-Wheel Drive and Rear-Wheel Drive
     vehicles generally have higher mSRPs, likely due to their presence in premium, performance
     or off-road-focused models. Front-Wheel Drive vehicles cars tend to be more affordable,
     making them common in economy vehicles. When analyzing fuel efficiency, the results indicate that manual
     and CVT vehicles often have better city and highway mpg compared to traditional automatic transmissions.













     
