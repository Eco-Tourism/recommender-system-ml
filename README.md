# recommender-system-ml
M322DSX0427 - Alvin Sengkey \
M172DSX1748 - Hilmi Reza Muhammad 

## Description
In this project, we build a recommender system model using TensorFlow and RecommenderNet architecture that can accept the city and category preferred by the user as the input and then output the probability that each village will be liked by the user. \
The probabilities will later be sorted to find the village to be recommended.

We convert the model that has been trained using TensorFlow Lite so that it can be deployed to Android mobile applications.


## Our project
We use Google Colab in the development process. To run our project, some libraries are needed, such as:

```
* tensorflow  2.12.0
* pandas      1.5.3
* numpy       1.22.4
* matplotlib  3.7.1
```

Our notebook that was used to train the recommender system is `/GreenTrails_CapstoneProject_C23_PS259_RecommenderSystem.ipynb` 

The model saved using TensorFlow format is `/model_recomm_system/model-citcat-new/` 

The TensorFlow model converted into TensorFlow Lite is `/model_recomm_system/model-citcat-new.tflite`

## Datasets
We took our dataset from Kaggle, then filtered it so that it only shows the data for tourist village destinations

Dataset : https://www.kaggle.com/aprabowo/indonesia-tourism-destination \
Filtered dataset : https://drive.google.com/file/d/1KgvCTJlBWL-owTJep-ey6pvmlRch1vkK/view?usp=drive_link or `/archive/all.csv`
