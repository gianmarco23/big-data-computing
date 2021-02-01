# Big Data Computing (2020-2021)

[News](#News) | [General Information](#General-Information) | [Syllabus](#Syllabus) | [Environment Setup](#Environment-Setup) | [Class Schedules](#Class-Schedules) | [Previous Years](#Previous-Years)

## News
- Students who are planning to submit their project **after** the January 2021 session should refer to the [Big Data Computing 2020-21 Moodle page](https://elearning.uniroma1.it/course/view.php?id=12771), rather than the current one (i.e., Big Data Computing 2019-20). This is to align exam sessions to the correct academic year, since academic year 2019-20 formally ends on January, 31 2021. As such, starting **from February 2021 until January 2022** all the exam sessions will be displayed on the newly created Moodle page indicated above, where students will be allowed to submit their work on the corresponding Project Submission Week that will be opened along the way, as usual.<br/>
(**NOTE:** _Only students who expect to complete the exam in one of the upcoming 2020-21 sessions must subscribe to the Big Data Computing 2020-21 Moodle page!_)
- **February 2021 Exam Session**<br/>
Registrations to the February 2021 exam session are now open on Infostud (id **752692**), and so they will until **February 7, 2021**.
Project submission week opens up on **February 1, 2021 at 00:00 CEST** ([Central European Summer Time](https://time.is/CEST)) and closes on **February 7, 2021 at 23:59 CEST**.<br/>
(_Please, see the announcement above for additional details on how to submit your project during this session, which is the first one of the academic year 2020-21._)

## General Information

Welcome to the Big Data Computing class!

This is a first-year, second-semester course of the [MSc in Computer Science of Sapienza University of Rome](https://www.studiareinformatica.uniroma1.it/master-course-computer-science).

This repository contains class material along with any useful information for the 2020-2021 academic year.

### Class Schedule
- **Tuesday** from **5:00PM** to **7:00PM** (Room G50, Building G in viale Regina Elena 295)
- **Wednesday** from **4:00PM** to **7:00PM** (Room G50, Building G in viale Regina Elena 295)

### Office Hours
- **Tuesday** from **2:00PM** to **4:00PM**, Room G39 located at the 2nd floor of Building G in viale Regina Elena 295.
(**NOTE:** Due to the COVID-19 emergency, office hours will be exclusively held **online** via Google Meet or Zoom upon email request message sent to the following address: tolomei@di.uniroma1.it)

### Moodle Web Page
Students must subscribe to the Moodle web page using the same credentials (username/password) to access Wi-Fi network and Infostud services, at the following link: https://elearning.uniroma1.it/course/view.php?id=12771

### Description and Goals
The amount, variety, and rate at which data is being generated nowadays both by humans and machines are unprecedented. This opens up a number of challenges on how to deal with those data, as traditional computing paradigms are not conceived to operate at such a scale.

"Big Data" is the umbrella term that has rapidly become popular to describe methodologies and tools specifically designed for collecting, storing, and processing very large or complex data sets. In addition to addressing foundational computer science problems, such as searching and sorting, big data computing mainly focuses on extracting knowledge - thereby value - from large-scale data sets using advanced data analysis techniques, such as machine learning.

This course is intended to provide graduate-level students with a deep understanding of programming models and tools that are suitable for the large-scale analysis of data distributed across clusters of computers. More specifically, the course will give students the ability to proficiently develop big data/machine learning solutions on top of industry standard frameworks, such as Hadoop and Spark, to tackle real-world problems faced by the so-called "Big Five" tech companies (i.e., Apple, Amazon, Google, Microsoft, and Facebook): text/graph analysis, classification/regression, and recommendation, just to name a few.

### Prerequisites
The course assumes that students are familiar with the basics of data analysis and machine learning, properly supported by a strong knowledge of foundational concepts of calculus, linear algebra, and probability and statistics. In addition, students must have non-trivial computer programming skills (preferably using Python programming language). Previous experience with Hadoop, Spark, or distributed computing is not required.

### Exams
Students must prove their level of comprehension of the subject by developing a software project, leveraging the set of methodologies and tools introduced during classes. Projects must of course refer to typical Big Data tasks: e.g., clustering, prediction, recommendation using very-large datasets in _any_ application domain of interest. The topic of the project must anyway be agreed with the professor in advance; references where to select interesting projects from will be however suggested throughout the course (e.g., [Kaggle](https://www.kaggle.com/)).
Projects can be done either **individually** or in group of **at most 2 students**, and they should be accompanied by a brief presentation written in english (e.g., a few PowerPoint slides). Finally, there will be an oral exam where submitted projects will be discussed in english; other questions on _any_ topic addressed during the course may also be asked, but those can be answered either in english or in italian, as the student prefers.<br/>
A document containing the main guidelines for the final project is available [here](./extra/Final_Project_Guidelines.pdf).

### Recommended Textbooks
No textbooks are mandatory to successfully follow this course. However, there is a huge set of references which may be worth mentioning, especially to those who wants to dig deeper into some specific topics. Among those, some readings I would like to suggest are as follows:
- _Mining of Massive Datasets_ [Leskovec, Rajaraman, Ullman] [available online](http://infolab.stanford.edu/~ullman/mmds/book.pdf).
- _Big Data Analysis with Python_ [Marin, Shukla, VK]
- _Large Scale Machine Learning with Python_ [Sjardin, Massaron, Boschetti]
- _Spark: The Definitive Guide_ [Chambers, Zaharia]
- _Learning Spark: Lightning-Fast Big Data Analysis_ [Karau, Konwinski, Wendell, Zaharia]
- _Hadoop: The Definitive Guide_ [White]
- _Python for Data Analysis_ [Mckinney]
 
<hr>

## Syllabus
**Introduction**
- The Big Data Phenomenon
- The Big Data Infrastructure
    - Distributed File Systems (HDFS)
    - MapReduce (Hadoop)
    - Spark
- PySpark + Google Colaboratory

**Unsupervised Learning: Clustering**
- Similarity Measures
- Algorithms: K-means
- Example: Document Clustering

**Dimensionality Reduction**
- Feature Extraction
- Algorithms: Principal Component Analysis (PCA)
- Example: PCA + Handwritten Digit Recognition

**Supervised Learning**
- Basics of Machine Learning
- Regression/Classification
- Algorithms: Linear Regression/Logistic Regression/Random Forest
- Examples: 
    - Linear Regression -> House Pricing Prediction (i.e., predict the price which a house will be sold)
    - Logistic Regression/Random Forest -> Marketing Campaign Prediction (i.e., predict whether a customer will subscribe a term deposit of a bank)

**Recommender Systems**
- Content-based vs. Collaborative filtering
- Algorithms: k-NN, Matrix Factorization (MF)
- Example: Movie Recommender System (MovieLens)

**Graph Analysis**
- Link Analysis
- Algorithms: PageRank
- Example: Ranking (a sample of) the Google Web Graph

**Real-time Analytics**
- Streaming Data Processing
- Example: Twitter Hate Speech Detector

<hr>

## Environment Setup
In this course, we will be using the Python application programming interface to the Apache Spark framework (a.k.a. [PySpark](https://spark.apache.org/docs/latest/api/python/index.html)), in combination with [Google Colaboratory](https://colab.research.google.com/) (or "Colab" for short). This will allows you to write and execute PySpark (as well as pure Python, for that matters) in your browser, with:
- Zero configuration required;
- Free access to Google's powerful cloud infrastructure (including GPUs);
- Easy sharing.

Of course, the same can be achieved also on your own local machine but that would require: _(i)_ dealing with clumsy installation issues that are very specific to your platform, and _(ii)_ sticking to "small" rather than real "big" data, as your machine cannot compare with Google's infrastructure!

Still, in case you would like to perform _also_ local mode installation, the following are the steps (along with some references) you need to take. [local](./oldest/2019-20.md#Local-Mode-Setup)

### Local Mode Setup

#### **Prerequisites:**
- Install Python 3.6 (or later) via [Anaconda](https://www.anaconda.com/distribution/#download-section) along with Jupyter Notebook
- Install [Java 8](https://www.oracle.com/java/technologies/javase-downloads.html)
    - If your system has multiple JDK installations, use jenv to manage them (e.g., for macOS users, please refer to this [link](https://medium.com/@brunofrascino/working-with-multiple-java-versions-in-macos-9a9c4f15615a))
    - In your ```~/.profile```, ```~/.bash_profile```, or ```~/.bashrc```, let ```jenv``` for managing multiple JDKs by adding the following two lines: 
        - ```export PATH="$HOME/.jenv/bin:$PATH"```
        - ```eval "$(jenv init -)"```
    - Run ```jenv enable-plugin export``` to allow ```jenv``` to automatically set ```JAVA_HOME``` upon changes to Java local/shell/global versions
    - In your ```~/.profile```, ```~/.bash_profile```, or ```~/.bashrc```, set default ```JAVA_HOME``` (system-wide) as follows:
        - ```export JAVA_HOME=$(/usr/libexec/java_home -v $(jenv version-name))```

#### **Installation:**
- Create a ```conda``` environment specifically for PySpark in combination with Python 3.6 (or later), and call it for instance "<code>PySpark</code>" (although you can choose any name you want):
    - ```conda create -n PySpark python=3.6```
    - Install required packages inside the newly created conda environment either via ```conda``` or via ```pip```:
        - ```conda activate PySpark```
        - ```conda install pip```
        - ```conda install numpy```
        - ```conda install scipy```
        - ```conda install pandas```
        - ```conda install scikit-learn```
        - ```conda install seaborn```
        - ```conda install ipykernel```
        - ```conda install findspark```
    - Install any additional packages:
        - ```conda install autopep8```
        - ```...```
        - ```conda deactivate```
    - Prepare a kernel for the newly created environment on Jupyter Notebook:
        - ```conda activate PySpark```
        - ```python -m ipykernel install --user --name PySpark --display-name "PySpark"```
        - ```conda deactivate```
    - Download from Apache the latest version of [Spark](https://spark.apache.org/downloads.html) (e.g., 2.4.5)
    - Untar the downloaded archive:
        - ```tar -xzf spark-2.4.5-bin-hadoop2.7.tgz```
    - Move the directory to a local folder (e.g., ```/opt/```, ```/opt/local/```, ```/usr/local/```, etc.) [might require sudo/administrator's password]:
        - ```mv spark-2.4.5-bin-hadoop2.7 /usr/local/spark-2.4.5```
    - Create a symlink so as to allow multiple versions of Spark:
        - ```ln -s /usr/local/spark-2.4.5 /usr/local/spark```
    - Update your ```~/.profile```, ```~/.bash_profile```, or ```~/.bashrc``` file as follows:
        - ```export SPARK_HOME=/usr/local/spark```
        - ```export PATH=$SPARK_HOME/bin:$PATH```
    - **NOTE: THIS STEP IS ONLY NEEDED IF YOU HAVE MULTIPLE JDK VERSIONS INSTALLED**
        - Go to ```/usr/local/spark/conf``` and create a ```spark-env.sh``` file (copying it from the template provided)
        - Enforce Spark to run on top of JDK 1.8 by copy-pasting the following into ```spark-env.sh```:
            - ```export JAVA_HOME=$(/usr/libexec/java_home -v 1.8)```

#### **Usage:**
You can start running your local Spark installation either interactively by typing the shell command `pyspark`, or using Jupyter Notebook in combination with the virtual environment created as indicated above. Either way, before being able to import any PySpark library you will need to use `findspark` to allow Python to correctly locate your own PySpark installation. To do so, just type the following (again, either at the prompt after you have executed `pyspark`, or in the first code cell of your Jupyter Notebook, or anyway at the top of your Python script):

`import findspark`

`findspark.init("${SPARK_HOME}")`

where `${SPARK_HOME}` contains the path to your local Spark installation (e.g., `/usr/local/spark`).

<hr>

## Class Schedules

| Lecture \#  | Date       | Topic                                         | Material        | 
|-------------|------------|-----------------------------------------------|-----------------|
<!--| Lecture 1   | 03/03/2020 | Introduction to Big Data: Motivations and Challenges | [slides: <a href="./slides/01_Intro.pdf" target="_blank">PDF</a>] |
| Lecture 2   | 03/04/2020 | MapReduce Programming Model | [slides: <a href="./slides/02_MapReduce.pdf" target="_blank">PDF</a>] |
| Lecture 3   | 03/10/2020 | Apache Spark + PySpark Tutorial (Part I) | [slides: <a href="./slides/03_Spark.pdf" target="_blank">PDF</a>, notebook: <a href="./notebooks/03_PySpark_Tutorial.ipynb" target="_blank">ipynb</a>] |
| Lecture 4   | 03/11/2020 | PySpark Tutorial (Part II) + Clustering: Data Representation | [slides: <a href="./slides/04_Clustering.pdf" target="_blank">PDF</a>, notebook: <a href="./notebooks/04_The_Curse_Of_Dimensionality.ipynb" target="_blank">ipynb</a>] |
| Lecture 5   | 03/17/2020 | Clustering: Distance Measures | [slides: <a href="./slides/04_Clustering.pdf" target="_blank">PDF</a>] |
| Lecture 6   | 03/18/2020 | Clustering Algorithms: K-means | [slides: <a href="./slides/05_Clustering_Algorithms.pdf" target="_blank">PDF</a>] |
| Lecture 7   | 03/24/2020 | Document Clustering with PySpark | [slides: <a href="./slides/06_Document_Clustering.pdf" target="_blank">PDF</a>, notebook: <a href="./notebooks/06_Document_Clustering.ipynb" target="_blank">ipynb</a>] |
| Lecture 8   | 03/25/2020 | Dimensionality Reduction (Principal Component Analysis) | [slides: <a href="./slides/07_Dimensionality_Reduction_(Principal_Component_Analysis).pdf" target="_blank">PDF</a>, notes: <a href="./extra/Notes_on_Principal_Component_Analysis.pdf" target="_blank">PDF</a>] |
| Lecture 9   | 03/31/2020 | Principal Component Analysis with PySpark | [notebook: <a href="./notebooks/07_Principal_Component_Analysis.ipynb" target="_blank">ipynb</a>] |
| Lecture 10  | 04/01/2020 | Supervised Learning | [slides: <a href="./slides/08_Supervised_Learning.pdf" target="_blank">PDF</a>] |
| Lecture 11  | 04/07/2020 | Linear Regression | [slides: <a href="./slides/09_Linear_Regression.pdf" target="_blank">PDF</a>] |
| Lecture 12  | 04/08/2020 | Linear Regression with PySpark | [notebook: <a href="./notebooks/09_Linear_Regression.ipynb" target="_blank">ipynb</a>] |
| Lecture 13  | 04/15/2020 | Logistic Regression | [slides: <a href="./slides/10_Logistic_Regression.pdf" target="_blank">PDF</a>, notes: <a href="./extra/Notes_on_Logistic_Regression.pdf" target="_blank">PDF</a>] |
| Lecture 14  | 04/21/2020 | Gradient Descent | [slides: <a href="./slides/10_Logistic_Regression.pdf" target="_blank">PDF</a>]|
| Lecture 15  | 04/22/2020 | Decision Trees and Ensembles | [slides: <a href="./slides/11_Decision_Trees_and_Ensembles.pdf" target="_blank">PDF</a>]|
| Lecture 16  | 04/28/2020 | Evaluation Metrics for Classification | [slides: <a href="./slides/12_Evaluation_Metrics_for_Classification.pdf" target="_blank">PDF</a>]|
| Lecture 17  | 04/29/2020 | Classification with PySpark | [notebook: <a href="./notebooks/10_Classification.ipynb" target="_blank">ipynb</a>] |
| Lecture 18  | 05/05/2020 | Recommender Systems (Part I) | [slides: <a href="./slides/13_Recommender_Systems_(Part_I).pdf" target="_blank">PDF</a>]|
| Lecture 19  | 05/06/2020 | Recommender Systems (Part II) | [slides: <a href="./slides/13_Recommender_Systems_(Part_II).pdf" target="_blank">PDF</a>]|
| Lecture 20  | 05/12/2020 | Recommender Systems (Matrix Factorization) with PySpark | [notebook: <a href="./notebooks/13_MF_Recommender_Systems.ipynb" target="_blank">ipynb</a>] |
| Lecture 21  | 05/13/2020 | Graph Link Analysis | [slides: <a href="./slides/14_Graph_Link_Analysis.pdf" target="_blank">PDF</a>]|
| Lecture 22  | 05/20/2020 | PageRank with PySpark | [slides: <a href="./slides/15_PageRank.pdf" target="_blank">PDF</a>, notes: <a href="./extra/Notes_on_PageRank.pdf" target="_blank">PDF</a>, notebook: <a href="./notebooks/15_PageRank.ipynb" target="_blank">ipynb</a>]|
| Lecture 23  | 05/26/2020 | Streaming Data Processing | [slides: <a href="./slides/16_Streaming_Data_Processing.pdf" target="_blank">PDF</a>]|
| Lecture 24  | 05/27/2020 | Streaming Classification with PySpark + The Last Take Home Message | [notebook: <a href="./notebooks/16_Streaming_Classification.ipynb" target="_blank">ipynb</a>, slides: <a href="./slides/17_The_Last_Take_Home_Message.pdf" target="_blank">PDF</a>]|-->

# Previous Years
In the following, you can quickly navigate through Big Data Computing class information and material from previous years.

**NOTE:** _The folder containing the class material is **unique** and it is subject to changes and/or updates; as such, there may be differences between the content displayed on this website and what have been shown in class in the past._

-   [2019-20](./oldest/2019-20.md)
