# Internship Report 

###### Aushpify Teachnology
---

<div align="center">

![Anaconda](https://img.shields.io/badge/Anaconda-%2344A833.svg?style=for-the-badge&logo=anaconda&logoColor=white)
![Jupyter Notebook](https://img.shields.io/badge/jupyter-%23FA0F00.svg?style=for-the-badge&logo=jupyter&logoColor=white)

![Python](https://img.shields.io/badge/python-%233670A0.svg?style=for-the-badge&logo=python&logoColor=ffdd54)
![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white)
![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)


</div>

## Table of content

1. [Installation Guide](#1.-Installation)
2. [About The Project](#2.-About)
3. [Data Insights](#3.-Data-Insights)
   - [3.1 Content type distribution](#3.1-Content-Type-Distribution)
   - [3.2 Movie and TV shows shares](#3.2-Movie-and-TV-shows-shares)


## 1. Installation

1. clone the repository in your local directory of your machine 

```code
git clone https://github.com/MohmmedFurqaan/
```

2. Let's setup the envinoment

In the project root directory, You will find the `project_config.yml` file. These file contains the envirnoment dependencies you can setup the envirnoment by the following :

```code 
conda env create -f project_config.yml
```

Then 

```code
conda activate netflix
```

## 2. About 

This project is an **Internship Report** focused on completing the assigned task by the organization. The data we have is about the netlfix data.

The project is built primarily to strengthen my understanding and practical implementation of the **Data Analytics using Python**, including exploratory data analysis as well as shipping up the quality report to the organization mentor.


## 3. Data Insights

As mention in the task pdf, below is the report based on the given netflix data.


### 3.1 Content Type Distribution
> AS per my analysis i founded that there are **6124 Movies** (which is of 69% of cleaned dataset). Alongside there is about **2663 TV shows** (which is about 30% of cleaned dataset)

![Content type frequency](data/output/figure/001_netlix_content_type.png)

### 3.2 Movie and TV shows shares
> Below graph shows about how many season for TV shows and how much duration of the movies is there in the dataset.

![Movie and TV shows shares](data/output/figure/002_runtime_distribution.png)
