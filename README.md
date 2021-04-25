# DATABASES PROJECT
## Analysis of Restaurants and their Inspection grades In New York
[![N|Solid](https://twilio-cms-prod.s3.amazonaws.com/images/jupyter_python_numpy.width-808.png)]()
[![N|Solid](https://cdn-images-1.medium.com/max/1200/1*6j17ZDuywkKu7TOa2yvAKg.png)]()
###### TOOLS USED
- PYHTON - Jupyter Notebook
- mongoDB - (Cloud client) MongoDB Atlas AWS cloud client
- PostgreSQL - (Cloud client) AWS RDS instance
###### PYTHON MODULES USED
- nbimporter
- sodapy
- pymongo
- pandas
- sqlalchemy
- psycopg2
- pandas
- numpy
- SciPy
- seaborn
- matplotlib

> This project analysis is being conducted to know the following research questions:
> 1. Which seating arrangement outside the restaurant influences the grades?
> 2. Does the type of Alcohol permit influence the grades?
> 3. Did the restaurant's special offer such as kid meal, shareable facility, regional food, and less nutritional content influence the food inspection grading of the restaurants?


# WORK FLOW
[![N|Solid](https://github.com/Rinub/DAP_project/blob/21e184349a9993e86d59cf4f8d0e0664754cae75/flow%20chart%20(2).png)](https://nodesource.com/products/nsolid)

## STEPS TO HANDLING FILES 
##### 1 Files for Making an http request and pull back a json string using API by accessing a database and pushing it to MongoDB atles AWS cloud client

>dataset 1 - data _1_push mongodb.ipynb<br />
>dataset 2 - data _2_push mongodb.ipynb<br />
>dataset 3 - data _3_push mongodb.ipynb<br />

##### 2 pulling the unstructured data from MongoDB atles AWS cloud client and Transforming  the data into a machine-learning-digestible format and loading it to PostgreSQL AWS RDS instance 
###### process done: data extraction, data cleaning, pre-processing, transforming, loading, data visualization

>dataset 1 - ETL_DATA_1.ipynb<br />
>dataset 2 - ETL_DATA_2.ipynb<br />
>dataset 3 - ETL_DATA_3.ipynb<br />


##### 3 pulling structured data 1, data 2, data 3  to merge all the datasets using inner joint and visualizing and storing the resultant dataset in PostgreSQL AWS RDS instance
###### process done: data extraction, data transforming,data visualization , loading
> merging dataset 1 and 2 - RESULTANT_DATA_1.ipynb<br />
> merging dataset 2 and 3 - RESULTANT_DATA_1.ipynb<br />

## MASTER_DO_NOTEBOOK
##### Run the MASTER_DO_NOTEBOOK.ipynb file to run all the files parallelly and see all the results and visualization. This handle separate files of an overall task. This file will run all the files sequentially and gives the visualized result of all the jupyter notebook files
> MASTER_DO_NOTEBOOK.ipynb

Note: Run the MASTER_DO_NOTEBOOK.ipynb file to run all the files sequentially and see all the results and visualization. This shows the outcome of all the separate files and their visualizations
