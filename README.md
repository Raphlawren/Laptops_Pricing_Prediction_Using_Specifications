![laptops](https://github.com/Raphlawren/Laptops_Pricing_Prediction_Using_Specifications/assets/130583230/3067b04c-726d-4ff4-a9f7-39bfc07459fa)



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


Fig 6: Category vs Price
![category box](https://github.com/Raphlawren/Laptops_Pricing_Prediction_Using_Specifications/assets/130583230/f3cb69cf-642a-4636-a091-f7e71949ab3d)

In Fig 6, we see that the distribution of price between the different category are quite distinct enough to make category a good predictor

Fig 7: GPU vs Price
![GPU](https://github.com/Raphlawren/Laptops_Pricing_Prediction_Using_Specifications/assets/130583230/b2f3236d-b676-41ac-8a5c-4ff6ed02e8bb)

In Fig 7, we see that the distribution of price between the different GPU is quite distinct to make GPU a good predictor of price.

Fig 8: OS vs Price
![OS](https://github.com/Raphlawren/Laptops_Pricing_Prediction_Using_Specifications/assets/130583230/76ee2524-f1c5-44f5-bc25-48040497abf2)

In Fig 8, we see that the distribution of price between the different OS is quite distinct to make OS a good predictor of price.

Fig 9: CPU_core vs Price
![CPU_core](https://github.com/Raphlawren/Laptops_Pricing_Prediction_Using_Specifications/assets/130583230/655e0501-dfaa-4ac0-bf90-fdb8b04f2752)

In Fig 9, we see that the distribution of price between the different CPU_core are quite distinct enough to make CPU_core a good predictor, in such a way that the higher the CPU the higher the price

Fig 10: RAM_GB vs Price
![RAM_GB](https://github.com/Raphlawren/Laptops_Pricing_Prediction_Using_Specifications/assets/130583230/8c89f1b6-2119-4793-a912-998ca5fd189f)

In Fig 10,we see that the distribution of price between the different RAM_GB are quite distinct enough to make RAM_GB a good predictor, in such a way that there the higher the RAM_GB the higher the price.

Fig 11: Storage_GB vs Price

![Storage_gb_ssd](https://github.com/Raphlawren/Laptops_Pricing_Prediction_Using_Specifications/assets/130583230/aa21c292-73b7-4b80-91d4-e171bc50e6ea)

In Fig 11, we see that the distribution of price between the differnet Storage_GB_SSD  is quite distinct enough to make Storage_GB_SSD a good predictor


Fig 12: Using CPU_frequency as a means of prediction ![CPU_freq prediction](https://github.com/Raphlawren/Laptops_Pricing_Prediction_Using_Specifications/assets/130583230/b4e99e9c-004e-451e-948e-e5c7ed85974a)  

In FIg 12, I predicted the price of the laptop using just the CPU_frequency, the blue line is the predicted price, while the red line is the actual price. we will see they don't fit well, let's continue and check with other specifications

Fig 13:
![multipot for linear](https://github.com/Raphlawren/Laptops_Pricing_Prediction_Using_Specifications/assets/130583230/c0597973-5afa-4619-a21f-efc4ae34d425)
In Fig 13, I predicted the price of a laptop using this specifications CPU_frequency, Category, GPU, OS, CPU_core, RAM_GB, Storage_GB_SSD and then compared the predicted price with the actual price. We can see multiple specifications as a prediction gives a better prediction than Fig 12. The blue line is the predicted price and the red line is the actual data, but there is still room for improvement.

Fig 14:
![poly1](https://github.com/Raphlawren/Laptops_Pricing_Prediction_Using_Specifications/assets/130583230/b4913d99-feae-4314-b028-153b8b47bf33)
![poly2](https://github.com/Raphlawren/Laptops_Pricing_Prediction_Using_Specifications/assets/130583230/3d3db71e-6ef8-4ff1-8628-e1032b7e7ad4)
![poly3](https://github.com/Raphlawren/Laptops_Pricing_Prediction_Using_Specifications/assets/130583230/5931a854-5a84-43ba-9c70-aaa5981e00fc)


Fitting a polymonial model give us a a better fitting,

In Fig 14, we can see that the line touched more dots compared to Fig 3 which is a good improvement

Fig 15: ![overfit](https://github.com/Raphlawren/Laptops_Pricing_Prediction_Using_Specifications/assets/130583230/9d2f85f2-1c1f-4b3c-b8e8-d65b1de51d2f)

In Fig 15, we plot a graph to look at the best degree to use to test our data to reduce overfitting and modeling noise



## CONCLUSION

* We can now say CPU_frequency, RAM_GB, Storage_GB_SSD, CPU_core, OS, GPU, Category is a good predictor of price

Thank you.
