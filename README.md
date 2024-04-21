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

In Fig 4, we can see that the weight is also not a good predictor of price, we can see the dots set is spread all over the in between the line.

Fig 5: Correlation of  Screen_Size, CPU_frequency, Weight_pounds against Price
![Screenshot 2024-04-20 at 4 01 53 PM](https://github.com/Raphlawren/Laptops_Pricing_Prediction_Using_Specifications/assets/130583230/df40c81f-41b4-4a26-900c-7f4bacd39fbc)

In Fig 5, this is showing the correlation between the 3 variables against price.  
Here is the percentage of the correlation between them to price  
Screen_Size vs Price   = 11%  
CPU_frequency vs Price = 36%  
Weight_pounds vs Price = 5%  


Fig 6: ![category box](https://github.com/Raphlawren/Laptops_Pricing_Prediction_Using_Specifications/assets/130583230/f3cb69cf-642a-4636-a091-f7e71949ab3d)
In Fig 6, we see that the distribution of price between the different category are quite distinct enough to make category a good predictor

Fig 7: ![GPU](https://github.com/Raphlawren/Laptops_Pricing_Prediction_Using_Specifications/assets/130583230/b2f3236d-b676-41ac-8a5c-4ff6ed02e8bb)

In Fig 7, we see that the distribution of price between the different GPU is quite distinct to make GPU a good predictor of price.

Fig 8:![OS](https://github.com/Raphlawren/Laptops_Pricing_Prediction_Using_Specifications/assets/130583230/76ee2524-f1c5-44f5-bc25-48040497abf2)

In Fig 8, we see that the distribution of price between the different OS is quite distinct to make OS a good predictor of price.

Fig 9:![CPU_core](https://github.com/Raphlawren/Laptops_Pricing_Prediction_Using_Specifications/assets/130583230/655e0501-dfaa-4ac0-bf90-fdb8b04f2752)

In Fig 9, we see that the distribution of price between the different CPU_core are quite distinct enough to make CPU_core a good predictor, in such a way that the higher the CPU the higher the price

Fig 10:![RAM_GB](https://github.com/Raphlawren/Laptops_Pricing_Prediction_Using_Specifications/assets/130583230/8c89f1b6-2119-4793-a912-998ca5fd189f)

In Fig 10,we see that the distribution of price between the different RAM_GB are quite distinct enough to make RAM_GB a good predictor, in such a way that there the higher the RAM_GB the higher the price.

Fig 11:![Storage_gb_ssd](https://github.com/Raphlawren/Laptops_Pricing_Prediction_Using_Specifications/assets/130583230/aa21c292-73b7-4b80-91d4-e171bc50e6ea)

In Fig 11, we see that the distribution of price between the differnet Storage_GB_SSD  is quite distinct enough to make Storage_GB_SSD a good predictor
