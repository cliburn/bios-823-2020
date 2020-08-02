# Syllabus for BIOS-823-2020

BIOS 823 is designed for people who want to work in a data science team, especially in a healthcare setting. Hence the course focuses on the skils and knowledge needed to contribute to the main roles in a data science team:

- Making data available and accessible for analysis
- Processing data and performing exploratory data analysis
- Statistical inference and machine learning
- Scaling up to big data and deploying automated workflows

You will learn how to use the essential tools for each of these roles effectively. The emphasis is on conceptual understanding, and we will highlight only selected software packages that exemplify each role. Once you understand the concepts, it should be simple to self-learn other similar packages, and you have the opportunity to do so in projects. Applications of data science to the analysis of structured, semi-structured and unstructured data, especially from biomedical contexts, will be interleaved into the course. 

**Prerequisites**

- You have a background in calculus and linear algebra
- You have a background in basic statistics inference
- YOu have a background in basic machine learning
- You are fluent in Python
- You are familiar with the use of `git` for version control
- YOu enjoy coding and playing with data

Course repository is at https://github.com/cliburn/bios-823-2020

Due to the wide-ranging nature of the syllabus, there is no course textbook. However, recommendations for useful books for each major topic will be suggested for those who want to explore the topic in more depth.


## Learning objectives

- How to contribute as a data science team member

- How to process data and perform exploratory data analysis
- How to manage data with SQL and NoSQL databases
- How to build machine learning pipelines
- How to scale and deploy data science products

## Grading

- 40% homework
- 30% exams
- 30% final project

For letter grade

- A: 90 - 100
- B: 75 - 89
- C: 60 - 74
- F: 59 and below

## Data Science

### Data processing and EDA

Typical packages: `pandas`, `plotnine`, `plotly`, `streamlit`

- Data manipulation with `pandas`
- Exploratory data analysis with `plotnine` and `plotly`
- Dashboards with `streamlit`

## Portable data formats

Typical packages: `json`, `ElementTree`, `h5py`, `pyarrow`, `parquet`

- Text files
- Tabular data
- Structured data


### Modern API design

Typical packages:  `graphene`, `fastapi`

- REST APIs
- Graph Query Language

## Data Management


### SQL databases

Typical packages: `sqlite`, `sqlalchemy`

- Relational databases are based on set theory
- Tables, rows, columns, keys, relations, constraints
- Database schema and normalization
- CRUD
- SQL queries
    - Single table queries
    - Window function
    - Joins
    - User defined functions

### NoSQL databases

Typical packages:`redis`, `mongodb`, `neo4j`

- Key-value
    - Uses
    - Collections
- Document 
    - Uses
    - Queries
- Graph 
    - Graph concepts with `networkx`
    - Uses
    - The Cypher language

## Machine Learning

### Understanding ML

Typical packages: `scikit-learn`, `pycaret`, `tune-sklearn`,  `yellowbrick`, `auto-sklearn`

- Unsupervised learning
    - Dimension reduction
    - Clustering
    - Recommender systems
- Supervised learning
    - Basic framework for training and evaluation
    - Model families
    - Preprocessing and feature engineering
    - Hyperparameter tuning
    - Model evaluation
    - Explaining models


### Modern ML frameworks

Typical packages: `tensorflow2`, `keras`, `tune`, `autokeras`, `dalex`

- Neural network concepts
- Working with data sets
- Effective training 
- Explainable AI (XAI)

## Data Engineering

### Functional programming

Typical packages: `itertools`, `functional`, `toolz`

- Recursion
- Lazy evaluation and iterators
- Comprehensions and generators
- Anonymous functions
- Partial application and currying
- Higher order functions: map, filter, reduce, decorators
- Pipes and chaining operations
- A digression: `coconut`

### Distributed computing

Typical packages: `spark`, `dask`, `vaex`

- Concurrent, parallel, distributed
- Simple multi-core processing
- Spark concepts
- Spark SQL
- Spark ML
- Spark Streaming
- GraphFrames
- Alternatives to Spark - `dask` and `vaex`

### Workflow management

Typical packages: `py.test`, `Singularity`, `airflow`

- Literate programming
- Source code version control
- Testing code
- Continuous integration
- Using containers
- Automating complex workflows
- Life in the cloud