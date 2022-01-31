# FRT-_PROJECT-Crop-Recommender
Utilizing the Student developer pack, using Azure Services Crop Recommender Application Was Created
## Implementation Of Project
Project was proceeded as 3 steps
### 1.Dataset
The dataset consists of data such as
-Nitrogen
-Phosphorus
-Potassium
-Humidity
-pH
-Rainfall
Based on all the above factors the crop was decided.

### 2.Model Construction
Azure ***Microsoft Azure Machine Learning Studio*** was utilized for model construction, I used *Automate ML* for model construction numerous models were generated each subsequent one greater in accuracy than the previous one.
The one with the highest accuracy was selected, deployed and endpoints were created.

### 3.Web Service Integration
I could have python FLASK and Azure web service to deploy them, but I do not have great expertise with web developing languages with just the basic and the crucial time left to turn the project on, I went with Node-RED to construct the dashboard for the model, the web service was deployed locally.
Refer the youtube video attached in the github to see the working of dashboard.
Image of Dashboard created.

![image](https://user-images.githubusercontent.com/71513343/151795804-418800da-5806-48b2-a9bc-a2f0566eda28.png)
