# Exploratory Data Analysis Project: Laptop Pricing Analysis






The Dataset is a filtered and modified dataset of the [Laptop Price Prediction using specifications](https://www.kaggle.com/datasets/arnabchaki/laptop-price-prediction?resource=download).

### Tools used
* Python
  
##  Laptop Pricing Prediction Using Specifications analysis

The dataset has 238 rows and 13 columns

Fig 1: Price Binning
![Binning](https://github.com/Raphlawren/Laptops_Pricing_Prediction_Using_Specifications/assets/130583230/a4e427ce-9d97-4488-8e82-2874cf2c0154)

In Fig 1, the 'Price' attribute is divided into three sectors to differentiate between values categorized as Low, Medium, and High.

FIg 2: Screen_Size vs Price ![screen_size](https://github.com/Raphlawren/Laptops_Pricing_Prediction_Using_Specifications/assets/130583230/fc1c638b-65a1-44b6-83aa-c7032f80631e)

In Fig 2, Screen_size is not a good predictor of price since the regression line is almost horizontal. We call it a weak predictor of price.

Fig 3: CPU_frequency vs Price
![CPU_frequency](https://github.com/Raphlawren/Laptops_Pricing_Prediction_Using_Specifications/assets/130583230/6db64a43-1358-41ea-8684-5f87f2079e97)


In Fig 3, we can see that CPU_frequency is a good predictor of Price, that is because we can see a positive incline on the regression line. The higher the CPU_frequency the higher the price.

Fig 4: Weight_pounds vs Price
![weight_pounds](https://github.com/Raphlawren/Laptops_Pricing_Prediction_Using_Specifications/assets/130583230/5e8f16e6-4817-4e49-86b2-816cf647e432)

In Fig 4, we can see that the weight is also not a good predictor of price.

Fig 5: Correlation of  Screen_Size, CPU_frequency, Weight_pounds against Price
![Screenshot 2024-04-20 at 4 01 53 PM](https://github.com/Raphlawren/Laptops_Pricing_Prediction_Using_Specifications/assets/130583230/df40c81f-41b4-4a26-900c-7f4bacd39fbc)

In Fig 5, this is showing the correlation between the 3 variables against price.  
Here is the percentage of the correlation between them to price  
Screen_Size vs Price   = 11%  
CPU_frequency vs Price = 36%  
Weight_pounds vs Price = 5%  
