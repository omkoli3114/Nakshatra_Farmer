# Nakshatra


This project aims to empower small and marginal farmers in India by providing critical agricultural information through SMS-based services, ensuring accessibility even for those without advanced technology. The solution addresses challenges like unpredictable weather, pest infestations, poor soil health, and fluctuating market prices by delivering tailored advice on crops, weather, and market prices. Additionally, it offers a dual approach to cater to both traditional non-tech farmers and tech-savvy farmers, enhancing inclusivity and scalability.


Key Features:
- For Non-Tech Farmers:
  - SMS-based weather alerts, crop management tips, market price updates, government schemes info, automated irrigation schedules, and crop information updates.
  
- For Tech-Savvy Farmers:
  - Advanced features such as field mapping, resource optimization recommendations, learning resources, community features, IoT device integration, and crop pest and disease detection via image analysis.



## DATA SOURCE 📊
- [Crop recommendation dataset ](https://www.kaggle.com/atharvaingle/crop-recommendation-dataset) 
- [Fertilizer suggestion dataset](https://www.kaggle.com/datasets/gdabhishek/fertilizer-prediction) 
- [Disease detection dataset](https://www.kaggle.com/vipoooool/new-plant-diseases-dataset)

## Notebooks 📓
- [Crop Recommendation](https://www.kaggle.com/atharvaingle/what-crop-to-grow)
- [Fertilizer Prediction](https://github.com/rudrakshi99/Farmer-Call-Center/blob/ml/notebook/geeks-on-fire-fertiliser-prediction.ipynb)
- [Disease Detection](https://www.kaggle.com/atharvaingle/plant-disease-classification-resnet-99-2)


## How to use 💻
- Crop Recommendation system ==> enter the corresponding nutrient values of your soil, state and city. Note that, the N-P-K (Nitrogen-Phosphorous-Pottasium) values to be entered should be the ratio between them. Refer [this website](https://www.gardeningknowhow.com/garden-how-to/soil-fertilizers/fertilizer-numbers-npk.htm) for more information.
Note: When you enter the city name, make sure to enter mostly common city names. Remote cities/towns may not be available in the [Weather API](https://openweathermap.org/) from where humidity, temperature data is fetched.

- Fertilizer suggestion system ==> Enter the nutrient contents of your soil and the crop you want to grow. The algorithm will tell which nutrient the soil has excess of or lacks. Accordingly, it will give suggestions for buying fertilizers.

- Disease Detection System ==> Upload an image of leaf of your plant. The algorithm will tell the crop type and whether it is diseased or healthy. If it is diseased, it will tell you the cause of the disease and suggest you how to prevent/cure the disease accordingly.


# License :memo:

This project follows the [MIT License](https://choosealicense.com/licenses/mit/).

[![Uses Git](https://forthebadge.com/images/badges/uses-git.svg)](https://github.com/rudrakshi99/Jan-Dhan-Darshak) 
[![forthebadge](https://forthebadge.com/images/badges/made-with-javascript.svg)](https://github.com/rudrakshi99/Jan-Dhan-Darshak)
[![forthebadge](https://forthebadge.com/images/badges/made-with-python.svg)](https://github.com/rudrakshi99/Jan-Dhan-Darshak)
[![Built with love](https://forthebadge.com/images/badges/built-with-love.svg)](https://github.com/rudrakshi99/Jan-Dhan-Darshak.git) [![Built By Developers](https://forthebadge.com/images/badges/built-by-developers.svg)](https://github.com/rudrakshi99/Jan-Dhan-Darshak) 
