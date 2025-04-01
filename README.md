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
   df_car.head()
   df_car.colums
   df_car.info()
   df_car.isnull().sum()
![Screenshot 2025-04-01 at 15 37 54](https://github.com/user-attachments/assets/d85d2221-1060-46e0-8eef-f3b81cecb456)

![Screenshot 2025-04-01 at 15 38 28](https://github.com/user-attachments/assets/908a9474-658e-4dae-82cc-ec79c07d464a)


   
   
3. Data Type Conversion
![Screenshot 2025-04-01 at 15 34 46](https://github.com/user-attachments/assets/1dc10c9e-aed6-46a5-aefc-1a0b0f7bdccf)

   
5. Filtering Data
![Screenshot 2025-04-01 at 15 33 49](https://github.com/user-attachments/assets/8f17fce2-a782-4eac-b181-3804fb521ea3)

   
7. String Operations
![Screenshot 2025-04-01 at 15 32 09](https://github.com/user-attachments/assets/90f6b2b1-20dd-43f5-a1b3-5df283e44219)

   
9. Cleaned Dataset
![Screenshot 2025-04-01 at 15 39 36](https://github.com/user-attachments/assets/38f6836b-34dc-4255-8706-4545337bdebc)


    


###FEATURE ENGINEERING
1. Creating New Columns

   ![Screenshot 2025-04-01 at 15 30 28](https://github.com/user-attachments/assets/1f1f9001-d67a-4dbe-8ab4-b1fc1a5856df)



### EXPLORATORY DATA ANALYSIS (EDA)
1. Descriptive Statistics

![Screenshot 2025-04-01 at 15 28 48](https://github.com/user-attachments/assets/ca0396c8-fe2e-4b03-9b49-523780002bce)

   
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













     
