# Water Quality Prediction 💧


A recent study of Tata Energy Research Institute has shown that in the past 50 years, the availability of fresh water has declined by two-third. In India, nearly, 44 million people have been affected by poor quality of water caused by water pollution. Some poisons, pathogens pollute the water even in low concentration. Natural water pollution is due to silt, clay, animal wastes, minerals etc. Provision of clean water is the bare necessity of every human being. It ought to be the priority of all governments. It is the need of the hour to create public awareness.


## SCOPE ✊🏻
We all know water is one of the most essential resource for our living. But as the development is increasing, we are exploiting water by wasting it and treating it with harmful materials which makes water impure and unfit for use. This is the reason it is very important to know the quality of water. This project is based on water quality prediction. In this project, water quality index (WQI) and quality status of water is predicted through some parameters that affects water quality. In this notebook we have performed Data Cleaning steps and did Exploratory Data Analysis. Then we have did some calculations as the data does not contain the column which can be used for prediction. Then we have created 2 models for prediction. The first model is Linear Regression model and The second model is Logistic Regression model. We have done this project with pyspark and other spark packages.


## DISCLAIMER ⚠️
This is a POC(Proof of concept) kind-of project. The data used here comes up with no guarantee from the creator. So, don't use it for making environmental decisions. If you do so, the creator is not responsible for anything. However, this project is an analysis cum prediction made based on the data taken and presents the idea that how we can use pyspark to retrive and create a training model for prediction at large scale and with authentic and verified data.


## AIM 🏹
The main aim of this project is to predict the water quality index , the quality status of the water and various parameter influencing it, using spark machine learning packages.


## DATA SOURCE 📊
Water Quality dataset (custom built dataset)
Combined and Cleaned data for Historical Water Quality in certain locations of India . Pollutants measures in each column is the average values measured over a period of time. source: " Indian government websites ".
Source : https://www.kaggle.com/code/anbarivan/indian-water-quality-analysis-and-prediction/data

## IMPLEMENTATION 🚀
Implementation is done in PySpark on Ubuntu using a VM(Virtual Machine).


## SPARK ✨
Apache Spark is a lightning-fast cluster computing technology, designed for fast computation. It is based on Hadoop MapReduce and it extends the MapReduce model to efficiently use it for more types of computations, which includes interactive queries and stream processing. The main feature of Spark is its in-memory cluster computing that increases the processing speed of an application. Spark is designed to cover a wide range of workloads such as batch applications, iterative algorithms, interactive queries and streaming. Apart from supporting all these workload in a respective system, it reduces the management burden of maintaining separate tools.


## PYSPARK ✨✨
PySpark is a Python API to support Python with Apache Spark. PySpark provides Py4j library, with the help of this library, Python can be easily integrated with Apache Spark. PySpark plays an essential role when it needs to work with a vast dataset or analyze them. This feature of PySpark makes it a very demanding tool among data engineers. A large amount of data is generated offline and online. These data contain the hidden patterns, unknown correction, market trends, customer preference and other useful business information. It is necessary to extract valuable information from the raw data. We require a more efficient tool to perform different types of operations on the big data. There are various tools to perform the multiple tasks on the huge dataset but these tools are not so appealing anymore. It is needed some scalable and flexible tools to crack big data and gain benefit from it.


## HOW TO USE 💻
### PRE-REQUISITE 🛍️
· Ubuntu 20.0 or higher version running (install Ubuntu on Oracle VM (Virtual Machine) VirtualBox),
· Anaconda app with Jupyter notebook on Ubuntu. 

### STEPS TO INSTALL SPARK AND PYSPARK 🪜
1.  Install packages required for Spark.
2.  Verify the installed packages.
3.  Extract using tar.
4.  Move the unpacked directory.
5.  Now configure spark environment.
6.  Open profile using nano.
7.  Start standalone spark master server nd test Spark shell.
8.  Install PySpark and run it.


## Further Improvements 📈
This was my first PySpark project so there are lot of things to improve upon.
