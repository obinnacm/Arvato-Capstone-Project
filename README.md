# Arvato-Capstone-Project


### Table of Contents

1. [Installation](#installation)
2. [Project Motivation](#motivation)
3. [File Descriptions](#files)
4. [Results](#results)
5. [Licensing, Authors, and Acknowledgements](#licensing)

## Installation <a name="installation"></a>

 To run this project Anaconda distribution of Python and python 3.x is required.

 Also, updated versions of scikit-learn and seaborn on notebook.

```
!pip install --user scikit-learn --upgrade

!pip install --user --upgrade seaborn

```

## Project Motivation <a name="motivation"></a>

My intention in this project was to understand Arvato Financial Services general population data and compare it with the customer data. The comparision is done to determine the people overrepresented or underrepresented in the customer and general population data. Lastly, predicting which recipients are most likely to become a customer for the mail-order company using the provided train and test data.

## File Descriptions <a name="files"></a>

There are seven data files associated with this project and required to run it:

- `Udacity_AZDIAS_052018.csv`: Demographics data for the general population of Germany; 891 211 persons (rows) x 366 features (columns).
- `Udacity_CUSTOMERS_052018.csv`: Demographics data for customers of a mail-order company; 191 652 persons (rows) x 369 features (columns).
- `Udacity_MAILOUT_052018_TRAIN.csv`: Demographics data for individuals who were targets of a marketing campaign; 42 982 persons (rows) x 367 (columns).
- `Udacity_MAILOUT_052018_TEST.csv`: Demographics data for individuals who were targets of a marketing campaign; 42 833 persons (rows) x 366 (columns).
- `feature_unknown_or_missing_values.csv`: Contains features and their corresponding unknown or missing values encoding. 
- `DIAS Information Levels - Attributes 2017.xlsx`: is a top-level list of attributes and descriptions, organized by informational category.
- `DIAS Attributes - Values 2017.xlsx`: is a detailed mapping of data values for each feature in alphabetical order. 

There is one code file associated with this project:

Arvato_Project_Workbook.ipynb: Jupyter notebook of all analysis.

## Results <a name="results"></a>

The main findings of the code can be found [here](https://medium.com/@charlesobinet7/ac0235432a39).

## Licensing, Authors, Acknowledgements <a name="licensing"></a>

My Previous Create Customer Segments with Arvato project in Introduction to Machine Learning with TensorFlow.

Thumbnail image of blog post was downloaded from pixabay using and can be found from this [link](https://www.istockphoto.com/en/photo/marketing-segmentation-geographic-demographic-income-and-generation-concept-gm1207733981-348819134?phrase=customer+segmentation)