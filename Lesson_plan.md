# Syllabus - options and references

I scanned and read a lot of books in preparing for this course. For each section, I've presented a selection of the books that I enjoyed. This is, of course, a very personal list - other instructors will have their own recommendations. Since this is part of a *professional* masters program, the recommended books are generally *non-academic* - meant more for practitioners than professors. 

There are also a *zillion* blog entries and tutorials on every conceivable topic in data science - I generally recommend reading a book to get a good perspective on a topic, and only then supplementing with shorter web resources to get another explanation of a tricky concept, reference the official documentation for a package, or to find out about the latest shiny toy. Relying only on the web will likely lead to a unsatisfying patchwork of random bits of knowledge.

The syllabus is a little idiosyncratic - I generally cover about 80% of the material with some depth, and for the remaining 20%, all you get is a suggestion that *this is a cool topic, and if you are interested, here is a good place to start*. *Which* 80% is covered varies from year to year - probably due to quantum fluctuations, or perhaps, ancient Mayan prophecies.

## Data Science

- Build a Career in Data Science - Emily Robinson, Jacqueline Nolis
- Fundamentals of Data Visualization -Claus O. Wilke
- Fluent Python (2nd edition) - Luciano Ramalho
- High Performance Python (2nd edition) - Micha Gorelick, Ian Ozsvald
- Data Science from Scratch: First Principles with Python (2nd Edition) - Joel Grus
- Python for Data Analysis (2nd edition) - Wes McKinney

### A01 Overview of syllabus and a data science career

Warm-up exercise:

- Find all unique Pythagorean triplets whose sum is less than 100. A Pythagorean triplet is a tuple of integers (a, b, c) such that $a^2 + b^2 = c^2$
- How many palindromic numbers are there between 1 and 1,000,000 with more than one unique digit (.e. 1331 is ok but 9999 is not)?

Data Science preamble

- Are our expectations for this course aligned?
- Which parts fo the syllabus excite or bore you?
- How do you want to be graded - weighting of homework, exams, projects
- What does a data scientist actually do?
  - Create recurring reports
  - Perform an analysis to answer a question
  - Create and deploy machine learning models
- What are the different roles in a data science team?
- How do you make yourself a competitive candidate?
- How do you build a data science portfolio?
- Basic requirements to thrive as a data scientist
  - Know your data
  - Know your model
  - Know your audience
  - Be aware of the big picture
- What should you look for in the working environment?

### A02 Data wrangling

Warm-up exercise:

- Create a DataFrame containing the famous `iris` data set from this [url](https://gist.githubusercontent.com/curran/a08a1080b88344b0c8a7/raw/639388c2cbc2120a14dcf466e85730eb8be498bb/iris.csv). Find the mean value for each measurement by species.

What you should know

- Do you know basic text operations?
  - download 3 books from Project Gutenberg
  - for each book, remove punctuation, convert to lower case, and split into words
  - create a table of unique word counts for each book
  - calculate the total count of each word (i.e. sum over 3 books)
  - create a log-log graph of the frequency of each word against its rank (rank 1 = most frequent word)
  - estimate the slope of the best linear fit to the graph
- Do you know basic `numpy` operations?
  - create arrays
  - index arrays
  - apply `ufunc` to arrays
  - reduce arrays along 1 or more axes
  - perform broadcast operations
- Do you know basic `pandas` operations?
  - select columns
  - rename columns
  - reorder columns
  - filter rows
  - transform cells
  - sort columns
  - summarize columns
  - calculate conditional statistics
  - convert from wide to tall
  - convert from tall to wide
  - split a string column into two or more columns based on a delimiter
  - replace specific entries in some columns using a dictionary lookup
  - join two or more DataFrames
  - apply window functions

Exercise: Working with `pandas` DataFrames

### A03 Accelerated data processing

- Interpreter bound
- I/O bound
- CPU bound
- Memory bound
- Making `numpy` faster
- Making `pandas` faster
- Using `vaex`

Exercise: Wrapping a C++ function

### A04 Data visualization and dashboards

- Grammar of graphics review
  - Data mapping - aesthetics, geometry, coordinates, scale
  - Metadata - labels, guides
  - Design - themes
- Some topics in visualization
  - Distributions
  - Nested proportions
  - Handling overlapping points
  - Geography
  - Multi-panel figures

Exercise: Create a dashboard with live updates

### A05 Portable data formats

Human readable
- Text files
- Tabular data
- JSON
- YAML
- XML

Binary
- Pickle and Dill
- HDF5
- Arrow and Parquet
- Protocol buffers

### A06 Working with APIs

- What is an API?
- Why use APIs?
- REST API
- GraphQL API
- Other APIs
- Command line API (`click` and `typer`)
- Web API (`fastapi`)

## Data Management

- Mastering Large Dataset with Python - J. T. Wolohan
- The Enterprise Big Data Lake - Alex Gorelik
- Seven Databases in Seven Weeks (2nd Edition) - Luc Perkins, Eric Redmond, Jim Wilson
- Learning SQL (3rd edition) - Alan Beaulieu
- NoSQL for Mere Mortals - Dan Sullivan
- Graph Databases (2nd edition) - Ian Robinson, Jim Webber, Emil Eifrem

### B01 Relational databases and SQL

- Why use a relational database?
- Using `sqlite`
- Basic concepts
  - Tables
  - Columns
  - Rows
  - PK and FK
  - Constraints
  - Set operations
- Relations between tables
  - 1:1
  - 1:N
  - N:1
- Normalization and Normal Forms
- De-normalization and data warehouses
- ETL operations

### B02 SQL Query language

- SQL is declarative
- Database compilers and optimization
- SQL standard daa types
- Basic CRUD operations
- Basic SQL query syntax
- Joins
- Aggregate functions
- Window functions
- User defined functions (UDF)
- SQL and `pandas`

### B04 Key-value databases

- Why use a key-value database?
- Using `redis`
- Data types and collections
- Streams
- Pipelines
- Publish/Subscribe

### B05 Document databases

- Why document databases?
- Using `mongodb`
- JSON revisited
- CRUD
- Geo-spatial queries

### B06 Graph databases

- Why graph databases?
- Using `neo4j`
- Basic graph concepts
- The Cypher query language
- CRUD
- Some graph algorithms

## Machine Learning

- Hands-on Unsupervised Learning Using Python - Ankur A. Patel
- Feature Engineering for Machine Learning - Alice Zheng and Amanda Casari
- Machine Learning Pocket Reference - Matt Harrison
- Deep Learning with Python (2nd edition) - François Chollet
- Hands-on Machine Learning with Scikit-Learn, Keraaas and TensnorFlow (2nd edition) - Aurélien Géron
- [Deep Learning](https://www.deeplearningbook.org) - Ian Goodfellow, Yoshua Bengio, Aaron Courville

### C01 Overview 

- Why ML?
- ML concepts
- Popular ML packages in Python
- Examples in `scikit-learn`
- Examples in `pycaret`
- Examples in `tf2-keras`
- Examples in `pytorch`

## C02 Unsupervised learning

- Why unsupervised learning?
- Warning: Signal from noise
- Dimension reduction
- Clustering
- Feature extraction
- Self-supervised learning
- Semi-supervised learning

### C03 Supervised learning

- Memorization and generalization
  - Bias-variance trade-off
  - Under- and over-fitting
  - In-sample and out-of-sample evaluation
  - Cross-validation
  - Regularization
-  Algorithm families
  - Neighbor methods
  - Classical statistics methods
  - Ensembles based on decision trees
  - Support vector machines
  - Neural networks

### C04 Pragmatic classical ML

- Data preparation
- Feature engineering
- Using pipelines
- Hyperparameter tuning and "auto ML"
- Model evaluation
- Machine learning visualization
- End-to-edn ML
- Deployment
- Monitoring and updating

### C05 Foundations of deep learning

- Anatomy of a unit (inputs, outputs, activation function)
- Layers
- Weight matrices
- The loss function
- Reverse mode auto-diff
- Workarounds for collapsing and exploding gradients
  - Activation functions
  - Batch normalization
  - Skip connections
- Optimization for deep learning
  - What is the problem?
  - Why not 2nd order?
  - Gradient descent - batch, mini-batch, SGD
  - Hacks for gradient descent: momentum, Nesterov, RMSprop, ADAM
- Avoiding over-fitting
  - Regularization
  - Drop-off
  - Early stopping
- Probabilistic deep learning

### C06 Pragmatic deep learning

- TensorFlow data sets
- Training a deep network
- Data augmentation
- Transfer learning
- Hyperparameter selection
- Automatic machine learning
- Explainable AI (XAI)

## Data Engineering

- Learn Docker in a Month of Lunches - Elton Stoneman
- Python for DevOps - Kennedy Behrman, Noah Gift, Grig Gheorghiu, Alfredo Deza
- Introducing MLOps - Clément Stenac, Léo Dreyfus-Schmidt, Kenji Lefevre, Nicolas Omont, Mark Treveil
- Building Machine Learning Pipelines - Catherine Nelson and Hannes Hapke
- Learning Spark (2nd edition) - Jules S. Damji, Brooke Wenig, Tathagata Das, Denny Lee
- Spark: The Definitive Guide - Matei Zaharia
- Graph Algorithms - Mark Needham, Amy E. Hodler

### D01 Functional programming

- Why functional programming?
- Pure and impure functions
- Imperative shell functional core
- Recursion
- Lazy evaluation
- Iterators and generators
- Higher order functions
- Decorators
- Anonymous functions
- Pipelines
- Using `functional`, `itertools`, `operator`
- Using `toolz`

Exercise: More functional concepts with `coconut`

### D02 Distributed computation

- Why distributed computing?
- The Hadoop ecosystem
- Spark architecture
- Data flow graphs
- Transforms and actions
  
### D03 Spark applications

- Spark SQL for distributed data processing
- Using Spark ML for distributed machine learning 
- Using Spark Streaming for streaming data
- Using GraphFrames for distributed graph computations

### D05 Data science operations

- Development and Operations (DevOps)
- Version control
- Packaging
- Testing
- Automating workflows
- Monitoring
- CI/CD

## Specialized Domains 

- Practical Time Series Analysis - Aileen Nielsen
- Natural Language Processing in Action - Hobson Lane, Cole Howard, Hannes Hapke
- Natural Language Processing with Spark NLP - Alex Thomas
- Deep Learning for the Life Sciences - Peter Eastman, Vijay Pande, Bharath Ramsundar, Patrick Walters
- Genomics in the Cloud - Geraldine A. Van der Auwera, Brian D. O'Connor

### Mostly projects?