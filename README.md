# DSND-Capstone-Sparkify

### Table of Contents

1. [Installation](#installation)
2. [Project Motivation](#motivation)
3. [File Descriptions](#files)
4. [Licensing, Authors, and Acknowledgements](#licensing)

## Installation <a name ='installation'></a>

This project was executed on an AWS EMR Cluster. The cluster was configured the following way:
* The EMR release label was emr-5.29.0
* Installed application: Spark 2.4.4, Livy 0.6.0, Zeppelin 0.8.2, JupyterHub 1.0.0
* This project was run on 1 x5.large master node and 2 x5.large core nodes
* each node was configured to maximize resource allocation [(AWS Docu)](https://docs.aws.amazon.com/emr/latest/ReleaseGuide/emr-spark-configure.html#emr-spark-maximizeresourceallocation)

Beyond the configuration above, the notebooks uses:
* pandas 0.25.1
* matplotlib 3.1.1
* seaborn 0.11.1

in the notebook the code for installing these libraries is included.

## Project Motivation<a name="motivation"></a>
This project was created as part of my Udacity Data Science Nano Degree project and is my capstone project for my Nano Degree course. Within the project, the dataset was provided with the task to predict customer churn.


## File Descriptions <a name="files"></a>

This repository includes:
* Sparkify.ipynb
* Sparkify - Full Dataset.ipynb
* Sparkify.html
* Spakify - Full Dataset.html

The Sparkify.ipynb and Sparkify.html include the project approach for a subset (approx. 1% of the whole dataset) of the Sparkify dataset as a Jupyter Notebook and as a html. The Sparkify - Full Dataset versions include the project approach for the whole dataset provided within the Sparkify project.

There are slight differences in the approach between the Sparkify file and the Sparkify - Full Dataset file.

The Sparkify - Full Dataset.ipynb takes about 3 hrs to run on the EMR cluster configured as stated above.

## Licensing, Authors, Acknowledgements<a name="licensing"></a>

Must give credit to ['Udacity'](https://www.udacity.com/) for the opportunity of this challenging project. It was a pleasure working on it.
If you like the project and got inspired, feel free to use the code here as you would like!
