# Exploratory Data Analysis Project: Laptop Pricing Analysis
The Dataset is a filtered and modified dataset of the [Laptop Price Prediction using specifications](https://www.kaggle.com/datasets/arnabchaki/laptop-price-prediction?resource=download).

##  Description
Parameters
The parameters used in the dataset are:
1. Manufacturer:
The company that manufactured the laptop
2. Category:
The category to which the laptop belongs: This parameter is mapped to numerical values in the
following way:

| Category    | Assigned Value |
|-------------|----------------|
| Gaming      | 1              |
| Netbook     | 2              |
| Notebook    | 3              |
| Ultrabook   | 4              |
| Workstation | 5              |



3. GPU
The manufacturer of the GPU. This parameter is mapped to numerical values in the following way:


| GPU    |Assigned Value|
|------  |--------------|
|AMD     |1             |
|Intel   |2             |
|NVidia  |3             |

5. OS
The operating system type (Windows or Linux): This parameter is mapped to numerical values in the
following way:


| OS     | Assigned Value|
| ---    | ---
|Windows | 1             |
|Linux   | 2             |

7. CPU_core
The type of processor used in the laptop: This parameter is mapped to numerical values in the
following way:

|CPU_core| Assigned Value|
|---     | ---           |
|Intel Pentium i3|  3    |
|Intel Pentium i5 |  5    |
|Intel Pentium i7 | 7 |
8. Screen_Size_cm
The size of the laptop screen is recorded in cm.
9. CPU_frequency
The frequency at which the CPU operates, in GHz.
10. RAM_GB
The size of the RAM of the system in GB.
11. Storage_GB_SSD
The size of the SSD storage in GB is installed in the laptop.
12. Weight_kg
The weight of the laptop is in kgs.
13. Price
The price of the laptop is in USD

## Installation
To load this dataset in your notebook follow this steps below:

1. Open your Jupyter notebook
2. Import pandas
3. Import and download the csv file  <a href='https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBMDeveloperSkillsNetwork-DA0101EN-SkillsNetwork/labs/Data%20files/automobileEDA.csv'>here</a>.

   
## Tools Used
* Jupyter Notebook

## Objectives
I am trying to confirm the relevance of some specifications on a laptop to be able to predict price.


1. The data has 238 rows and 13 column.
2. Displayed the data information to see if the data types are right.
* ![Screenshot 2024-04-19 at 10 51 49 PM](https://github.com/Raphlawren/Laptops_Pricing_Prediction_Using_Specifications/assets/130583230/001cd7f8-349c-4a92-8223-144ec8d28b78)
3. Rounded up the values of the Screen_Size_cm to the nearest 2 decimal number and also displayed the top 5 rows of the data.
  ![Screenshot 2024-04-19 at 10 57 53 PM](https://github.com/Raphlawren/Laptops_Pricing_Prediction_Using_Specifications/assets/130583230/6cda5815-2cd2-4355-9e55-2a8336697910)
4. Identifying the missing data in the dataset.
  ![Screenshot 2024-04-19 at 11 02 09 PM](https://github.com/Raphlawren/Laptops_Pricing_Prediction_Using_Specifications/assets/130583230/e0b6c8a1-55ba-4048-a33d-81a0e8b6fc90)
5. Counting the number of missing data in the dataset, discovered that the following data are missing:
  
  |Missing Column| Missing Values|
  | ---| ---|
  |Screen_Size_cm| 4|
  |Weight_kg|5|
  
  ![Screenshot 2024-04-19 at 11 10 32 PM](https://github.com/Raphlawren/Laptops_Pricing_Prediction_Using_Specifications/assets/130583230/f74c9b5c-1dfc-4028-9f05-de1a0acdfb7e)
6. Replacing the missing values in Weight_kg by the average and the Screen_Size_cm by the highest most frequent value
  ![Screenshot 2024-04-19 at 11 52 02 PM](https://github.com/Raphlawren/Laptops_Pricing_Prediction_Using_Specifications/assets/130583230/365552fb-b377-4bb7-b6dc-2f1d1782cf4e)
7. The value of screen_size is in cm which is modified to inches, and the weight_kg is in kg which is also modified to pounds and their names is updated as well
This is the unit of conversation used:
1 inch = 2.54 cm
1 kg   = 2.205 pounds
![Screenshot 2024-04-20 at 12 00 34 AM](https://github.com/Raphlawren/Laptops_Pricing_Prediction_Using_Specifications/assets/130583230/9af155f2-ec4a-482c-be97-782540c5b810)
8. Displaying the number of unique value for each column in the dataframe
![Screenshot 2024-04-20 at 12 04 43 AM](https://github.com/Raphlawren/Laptops_Pricing_Prediction_Using_Specifications/assets/130583230/db7b5014-907b-4afa-9ee3-d4c326b38156)

9. Normalizing the CPU_frequency variables so the value ranges from 0 to 1
    ![Screenshot 2024-04-20 at 12 15 43 AM](https://github.com/Raphlawren/Laptops_Pricing_Prediction_Using_Specifications/assets/130583230/18a61393-d7ca-4bb5-8f96-edde9c07c216)

10. We only care about the prices of laptop, so we divide the prices into 3 bins name: Low, Medium, High.  and also named the new attribute 'Price-binned':
    ![Screenshot 2024-04-20 at 12 46 43 AM](https://github.com/Raphlawren/Laptops_Pricing_Prediction_Using_Specifications/assets/130583230/1447cc51-d1e0-4315-a54e-ee6109d78c6c)
    
