
<h1 align="center">K-Means Clustering from scratch</h1>


<!-- --- -->

<p align="center"> Applies K-Means clustering to the indian pincodes dataset and tries to draw meaningful inferences from it.
    <br> 
</p>

## Table of Contents


- [Running](#running)
- [Usage](#usage)
- [Built Using](#built_using)
- [Authors](#authors)
- [Credits](#credits)

## Running <a name="running"></a>
To be able to run this file, you need to have `Python` installed on your system. Along with that, you'll also need to install the `pip-packages` mentioned in `requirements.txt`.

Once you have python installed, you can run
```
pip install -r requirements.txt
```

You'll also need the csv file containing the data and a map for better visualization


## Usage <a name="Usage"></a>

The functions are pretty self-explanatory.<br>
- The function `k_means_clustering` applies the kmeans clustering algorithm to given input points. It expects $3$ input features, namely `Latitude`, `Longitude` and `Delivery`.
- The function `apply_kmeans` takes in all the parameters along with the dataset, applies kmeans clustering, and plots the data.
- The function `calculate_WCSS` calcualtes and plots WCSS for values of $k$ ranging from $1$ to $\max\_k$
- The parameter `delivery_weight` defines how much does the column `Delivery` affect the cluster formation.
- If you are using it for some other state, you need to change the `state_name` variable to your state name. Also, you will need to modify the extent and the latitude-longitude limits for your state.





## Built Using <a name = "built_using"></a>

- [Python](https://www.python.org) 
- [NumPy](https://numpy.org)
- [pandas](https://pandas.pydata.org/pandas-docs/stable/index.html#)
- [matplotlib](https://matplotlib.org)

##  Author <a name = "authors"></a>

- [@harsh15044](https://github.com/harsh15044) - Implemented it from scratch as Epoch Spring-camp task.

## Credits <a name = "credits"> </a>
- Map image used for visualization is sourced from <a href="https://d-maps.com/carte.php?num_car=9041&lang=en" >d-maps.com </a>, used under their free-to-use policy. All rights belong to the original creator.



