# Emotion detection from audio Using machine learning

## Motivation
Emotion recognition technologies have been widely used in a variety of different applications in the past few years and seem to be only growing more popular in today’s industry. from psychological studies to advanced analysis of customer needs, it seems like the potential of these technologies is inexhaustible. Yet, these methods are still perceived as incredibly complex and inaccessible for the average data scientist who do not hold the privilege of being an expert in analysis of audio frames and sound waves.
## Screenshots
![1](https://user-images.githubusercontent.com/100093143/178966587-7a84c8c2-d980-407e-b58a-024360624add.PNG)
![2](https://user-images.githubusercontent.com/100093143/178966602-63f0c21e-4c09-413a-885a-cf518a7e42eb.PNG)
![3](https://user-images.githubusercontent.com/100093143/178966612-61bd01da-ea53-466f-8cdb-8522248cb5b0.PNG )
## Tech/Framework used
jupyter notebook
## Installation
inside jupyter notebook run the following commands:\
pip install librosa\
pip install numpy\
pip install pandas\
pip install seaborn\
pip install -U scikit-learn
## Tests
![Accuracy](https://user-images.githubusercontent.com/100093143/178971592-7f991b9e-7d7e-4841-be4f-ed3c15dc615f.PNG)
## How to Use?
After opening jupyter notebook, 
* open first **Data_Processing.ipynb**
* install *libraries* in section above **Installation** 
* in **Load Data and convert it to array** you should add the path where you have file **data** loaded
* after executing all cells 
* tha last cell **Load DATA into csv file** add your own path where you want to save the **csv** file because you well need it after
* now open file **Classification.ipynb**
* in the section **Reading and exploring Data** you should add the path where you saved the **csv** file 
* run all cells and observe the performance of different models
## Contribute
### Improving the features
in **Data_Processing** file section of **Extracting Features**,
there is many *features* like {**MFCC**, **Centroid**, **ZCR**, ...}
when we apply some of these *features*, as an output value we have an array, then we apply **functions** like *sum* and *mean* etc, to get one value as a result instead of an array. 

  * change this functions
  * using more than one function on the same feature like getting 3 value sum, mean, max from MFCC
  * add new features\
all these things can help to give us more features, and those help models to train better and perform a good accuracy
### Improving accuracy by using Neural network instead of classification method

