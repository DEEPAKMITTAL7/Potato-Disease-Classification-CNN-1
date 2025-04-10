# Potato-Disease-Classification-CNN-1

Working on Image Classification Problem and would be using CNN for it.

I haved picked Agriculture problem because I feel the problem for farmers are very under rated and needs attention.

Loss of economics in farming can be a disaster for any country, this needs to addressed quickly.

I am taking the responsiblity here to work on it for Potato Farmers.

Subsquently, I will be working on other verticals of Agriculture as well.


Target Classes has -> 1. Early Blight 2. Late Blight 3. Normal/Healthy

Approach

1. Data Collection followed by processing -> Data Augmenation (we might not get the enough data images through dataset)

2. Model Building -> CNN (as this is image classificatiion problem) 

3. Exporting the model and will use tf_serving for different versions via Fast API.

4. Building a website, for interaction to prediction.

5. Building a mobile application as well, for easiness, and will use quantization required for edge device model.

6. Deploy the model to Google Cloud, so our application will take input from here and will give us the prediction.


# Getting the data.

1. Getting data from third party who sells images data.
2. Create a team, and work manually on ground. (this is costly and time taking)
3. Web scrapping (getting data from google, but use tool to annotate it)

but I believe getting data from third party is reliable, wasting time in data collection and processing is not good.

for this, I am taking data from Kaggle.
https://www.kaggle.com/datasets/arjuntejaswi/plant-village

This dataset has data about Potato, Tomato and Pepper. But Potato is our target this time. 
