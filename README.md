# Data preprocessing - NYC City Trees Project

<img src="https://github.com/Louan-M/nyc-trees/blob/main/Images/USA_Parks_Autumn.jpg" width="550">

## What ?

### The Mission

The Department of Environmental Conservation, from New York city, has recently made the news by telling the people that they needed their help. Indeed, their request is simple: They needed the people of New York city, whether young or old, to go to the nearest tree in their street and gather information about that tree. This is all in an effort to make the population aware that nature is important, even in big Metropolis like NYC. Now that they have heard back from the people, the DEC noticed that they missed a crucial step. They forgot to give the people a data collection guide, and so the data they received back is a bit messy.

Can you help them clean the data so that they can begin to raise awareness to ecological issues, such as climate change ?

Must-have features

    The dataset contains no missing values ("" or null)
    No duplicates.
    Values are consolidated
    Data format is correct
    No blank spaces (ex: " I love python " => "I love python")

Nice-to-have features

    The more rows of data you use, the better. However, pay attention that the more data you have, the longer each operation needs to execute.


## Who ?

Carried out by **Louan Mastrogiovanni**,  Theano 2.27 promotion @BeCode


## Why ?

- Consolidate knowledge of pandas library
- Learn to clean a dataset

## When ?

This is a 1 day project. The dead line is on `12/03/2021 04:00 PM`.

## How ?

All the cleaning is based on the https://tree-map.nycgovparks.org/ website. As the time was limited, this website has been used as a reference for the final goal avec the cleaning process.

### Overal process
1) Download dataset with use of `download.py` script provided by Becode
2) Remove unnecessary columns
3) Change column names 
4) Reposition address column in the dataset
5) Replace NaN values
6) Further cleaning
7) Save DataFrame to external (compressed) csv file

## About the repository

This repository contains the cleaned dataset `Final_dataset.csv` and the source code (Notebook) `NYC_trees_project.ipynb`. 

*Shape of `Final_dataset.csv.xz` :* 
&nbsp;
**(683788 rows x 20 columns)**
&nbsp;
&nbsp;
## Thank you for reading!
