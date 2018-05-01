# Hadoop_Project

# Hadoop Presentation:

https://docs.google.com/presentation/d/17CooF-cfo1g4TdGzIDgM92bdN_VIG2F-reo9zXcPMEc/edit?usp=sharing

# Hadoop installation:
https://github.com/ahmedhgh/hadoop_project/blob/master/Installing%20and%20Practicing%20Hadoop%20in%20Jupyter%20Notebook.ipynb

# Hadoop Project: 
# 1- Processing and Creating Predictive models for Academic Buildings by Using Bigdata Technology (Regression Problem)
https://github.com/ahmedhgh/Hadoop_Project/blob/master/Proj_part1_Ahmed_Ghareeb.ipynb

In this project the University of Dayton campus buildings selected to develop and validate the knowledge discovery models to understand the behavior of energy consumption, we will use the campus buildings to understand the underlying behavior and attempt to use knowledge discovery methods (KDD) to gain knowledge about various campus buildings.

Certainly, the behavior of building will depend on the activities that occur in it. For instance, the activities in the library building will appear to be more energy consuming during the weekends, classrooms more occupied during the class time which will vary roughly from 8 A.M to 12 P.M. and so on. One of the important values we can get from this project using the knowledge discovery in addition to the general building behavior is the range and the amount of energy for the specific hour. Another important task in buildings is accurate energy prediction; this is useful because the institution owners need to make sure that they have the amount of energy needed at the particular time. Due to energy deregulation plan the building owners need to submit the amount of energy needed for the next 24 hours to the utility providers (short-term prediction requirement), or they need to know how much energy needed at each building monthly (medium-term prediction), and the amount of energy needed if they plan to extend the institute or plan for policy. Before we describe the tasks we will use to accomplish the above-mentioned problems, we will describe the datasets.

Using Bigdata Technology (Hadoop and Spark) we can accelerate the process of predictive models by putting them in the external server or distribute them to be processed in parallel in and out core instead of traditional computing.


# 2 - Gas sensors for home activity monitoring Data Set (Classification Problem)
https://github.com/ahmedhgh/Hadoop_Project/blob/master/Database_Project.ipynb

STEPS (the objective and the appraoch)
In this task I tackled 3 aspects in the deep learning :

Increase the hidden layers (how much the dataset will improve increasing the hidden layers?)
Increase the dataset samples (increasing the number of observation how much will change the accuracy?)
increase the number of neurons (increase the number of neurons how much will impact the model?)
Becasue of huge number of observation (919438)First tested only 1000 sample (shown in subsetting section) from the dataset to make the model will run properly without loading the computer processor. Second tested 10000 instance, finally added all of the sample.

The data devided to ( training set, training set labels, test set, test set labels) at each tree partion. This partionong also provided some sense about the classification model behaviour while increasing the data

Also tested adding layer hidden layers more than 5 -starting from 5 hidden layers to 7 layers

A Multilayer Perceptron (Neural Network) implemented from example using TensorFlow library.

The accuracy of the model at each stage provided in the conclution part
