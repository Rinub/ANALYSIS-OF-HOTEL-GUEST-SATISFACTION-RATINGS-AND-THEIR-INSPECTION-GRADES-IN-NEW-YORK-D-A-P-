# DATABASES PROJECT
## Analysis of Restaurants and their Inspection grades In New York
[![N|Solid](https://twilio-cms-prod.s3.amazonaws.com/images/jupyter_python_numpy.width-808.png)](https://nodesource.com/products/nsolid)
[![N|Solid](https://th.bing.com/th/id/R0873b3f2509a3957f4b9a984398dbe3a?rik=ktrSTO4riuQzQQ&riu=http%3a%2f%2fdbaprof.com%2fwp-content%2fuploads%2f2018%2f08%2fAWS-RDS.png&ehk=mQo22Fxp2Iv0u53hiY8dmQLf1X25XmczK3v7Gea2Pe4%3d&risl=&pid=ImgRaw)](https://nodesource.com/products/nsolid)
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
##### Files for Making an http request and pull back a json string using API by accessing a database and pushing it to MongoDB atles AWS cloud client

>dataset 1 - data _1_push mongodb.ipynb<br />
>dataset 2 - data _2_push mongodb.ipynb<br />
>dataset 3 - data _3_push mongodb.ipynb<br />

##### pulling the unstructured data from MongoDB atles AWS cloud client and Transforming  the data into a machine-learning-digestible format and loading it to PostgreSQL AWS RDS instance 
###### process done: data extraction, data cleaning, pre-processing, transforming, loading, data visualization

>dataset 1 - ETL_DATA_1.ipynb<br />
>dataset 2 - ETL_DATA_2.ipynb<br />
>dataset 3 - ETL_DATA_3.ipynb<br />


##### pulling structured data 1, data 2, data 3  to merge all the datasets using inner joint and visualizing and storing the resultant dataset in PostgreSQL AWS RDS instance
###### process done: data extraction, data transforming,data visualization , loading
> merging dataset 1 and 2 - RESULTANT_DATA_1.ipynb<br />
> merging dataset 2 and 3 - RESULTANT_DATA_1.ipynb<br />
