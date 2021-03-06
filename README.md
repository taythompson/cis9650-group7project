# Google Play Store
## An In-Depth Analysis on Google Play Store App Installations </center>
<img src="https://i.pinimg.com/originals/1a/49/22/1a49226d155846acb790eeb919f63c8e.jpg" width="100" height="100" />

# About The Project
This project aims to use statistical analysis tools to determine the factors that contribute to a profitable Android application. The raw data will be cleaned and then analyzied using the Pandas library. Graphical representations of our findings are also included in this project. The goal is to provide useful insights for developers on how to stand-out in the ever-evolving app development market. 

# Scope of Research
The following factors were focused on for this research:
1. Impact of Price of an App on its Ratings
2. Total Number of Installs of an App per Category
3. Comparison of Percentage of Free Applications vs. Percentage of Paid Applications
4. Total Number of Applications in Each Category
5. Average Rating in Each Category
6. Average Price in Each Category
7. Max Number of App Installations
8. Paid Applications with the Lowest Installs

# Prerequistes 
The project was made using Python. 

The following open source packages are used in this project:
* Pandas
* Numpy
* Matplotlib
* Seaborn 

# User Guide
The dataset used for this project was upload to Amazon S3 for ease of use. In order to use our code, users simply just need to clone this repo and run the source code in a Python friendly IDE.

# Dataset
The Google Play Store Apps dataset provided by Kaggle provides application data on various categories such as categories and ratings from the apps found on the Google Play Store. This dataset contains data on approximately 10,000 applications. The dataset can be found here: [Kaggle](https://www.kaggle.com/lava18/google-play-store-apps). A sample of the dataset is provided below: 
![dataset_image](https://user-images.githubusercontent.com/48069159/118328797-2dd60800-b4d4-11eb-9fa5-66ce39d8f850.png)


# Results 
Our analysis yielded results that can help developers make smarter app development decisions. Based on the results, while the game category has the most installs, it might not be the most profitable app to develop because the average price of games tend to be on the lower side. 

<img src="https://user-images.githubusercontent.com/48069159/118333059-0afa2280-b4d9-11eb-9b6e-d9162d26bc52.png" width="500" height="550" />

If a developer is looking to develop a profitable application, they might want to consider the financial category as this category has the highest average price and does not fall to low on the list of most app installations.

<img src="https://user-images.githubusercontent.com/48069159/118333067-0e8da980-b4d9-11eb-8fa1-27fbc3b3abcf.png" width="500" height="550"/>

The price of an app has a strong influence on an applications rating. Apps that are lower in price tend to have a higher rating with an approcimate average of 4.5. Higher priced apps tend to fall below this average. 

![price_vs_rating_graph](https://user-images.githubusercontent.com/48069159/118333592-fc603b00-b4d9-11eb-956d-3bec1b3db16c.png)

In conclusion, there is a happy medium developers need to find between price and category in order to have an app that is not only profitable but also has high user ratings. 

For additional analysis, please see the presentation slide deck also attached in this repo. 


