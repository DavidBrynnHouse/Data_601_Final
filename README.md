# David House 601 Final due 12/8/2020

## How to Navigate this Project

---

* **Code** - Folder for Jupyter notebooks.
    * [Spotify Jit Classifier.ipynb](https://github.com/DavidBrynnHouse/Data_601_Final/blob/master/Code/Spotify%20Hit%20Classifier.ipynb) - Jupyter notebook used to clean and organize data.
* **Data** - Dataset that was analysed in this project.
    * [dataset-of-00s.csv](https://github.com/DavidBrynnHouse/Data_601_Final/blob/master/Data/dataset-of-00s.csv)
    * [dataset-of-10s.csv](https://github.com/DavidBrynnHouse/Data_601_Final/blob/master/Data/dataset-of-10s.csv)
    * [dataset-of-60s.csv](https://github.com/DavidBrynnHouse/Data_601_Final/blob/master/Data/dataset-of-60s.csv)
    * [dataset-of-70s.csv](https://github.com/DavidBrynnHouse/Data_601_Final/blob/master/Data/dataset-of-70s.csv)
    * [dataset-of-80s.csv](https://github.com/DavidBrynnHouse/Data_601_Final/blob/master/Data/dataset-of-80s.csv)
    * [dataset-of-90s.csv](https://github.com/DavidBrynnHouse/Data_601_Final/blob/master/Data/dataset-of-90s.csv)
* [LICENSE](https://github.com/DavidBrynnHouse/Data_601_HW-1/blob/master/LICENSE) - MIT License
* [README.md](https://github.com/DavidBrynnHouse/Data_601_Final/blob/master/README.md) - A brief overview of the project.


## My goals for this project

---

My goal for this project is to train an ML algorithm which can accuratly predict whether a song is a hit or not. 


## Overview

---

For this project I used data from the spotify API and used it to train an ML algoritm that would predict, based on attributes of a song, if it would be a hit or not. Using a decision tree I achived an accuracy of 82 +/- 2% accuracy. 



## Data

---

The data I trained the algorithm on was collected from the Spotify API. It included songs recorded between 1960 and 2019. Each song was arow in the dataset and had features such as energy, key, loudness, acousticness.

## Requirements

---

The software used in this analysis included:

1) Python
2) Pandas package for python
3) The python sklearn library