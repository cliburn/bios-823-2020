# Syllabus - options and references

I scanned and read a lot of books in preparing for this course. For each section, I've presented a selection of the books that I enjoyed. This is, of course, a very personal list - other instructors will have their own recommendations. Since this is part of a *professional* masters program, the recommended books are generally *non-academic* - meant more for practitioners than professors. 

There are also a *zillion* blog entries and tutorials on every conceivable topic in data science - I generally recommend reading a book to get a good perspective on a topic, and only then supplementing with shorter web resources to get another explanation of a tricky concept, reference the official documentation for a package, or to find out about the latest shiny toy. Relying only on the web will likely lead to a unsatisfying patchwork of random bits of knowledge.

The syllabus is a little idiosyncratic - I generally cover about 80% of the material with some depth, and for the remaining 20%, all you get is a suggestion that *this is a cool topic, and if you are interested, here is a good place to start*. *Which* 80% is covered varies from year to year - probably due to quantum fluctuations, or perhaps, ancient Mayan prophecies.

## Data Science

- Build a Career in Data Science - Emily Robinson, Jacqueline Nolis
- Analytical Skills for AI and Data Science - Daniel Vaughan
- Fluent Python (2nd edition) - Luciano Ramalho
- High Performance Python (2nd edition) - Micha Gorelick, Ian Ozsvald
- Data Science from Scratch: First Principles with Python (2nd Edition) - Joel Grus
- Python for Data Analysis (2nd edition) - Wes McKinney
- Fundamentals of Data Visualization -Claus O. Wilke

### A01 Overview of syllabus and a data science career

Warm-up exercise:

- Find all unique Pythagorean triplets whose sum is less than 100. A Pythagorean triplet is a tuple of integers (a, b, c) such that $a^2 + b^2 = c^2$
- How many palindromic numbers are there between 1 and 1,000,000 with more than one unique digit (.e. 1331 is ok but 9999 is not)?

Data Science preamble

- Are our expectations for this course aligned?
- Which parts fo the syllabus excite or bore you?
- How do you want to be graded - weighting of homework, exams, projects
- What does a data scientist actually do?
- What are the different roles in a data science team?
- How do you make yourself a competitive candidate?
- How do you build a data science portfolio?
- What should you look for in the working environment?


Exercise: Create a blog on GitHub pages using Pelican.

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

### A04 Data visualization and dashboards

### A05 Portable data formats

### A06 Working with APIs

## Data Management

- Mastering Large Dataset with Python - J. T. Wolohan
- The Enterprise Big Data Lake - Alex Gorelik
- Seven Databases in Seven Weeks (2nd Edition) - Luc Perkins, Eric Redmond, Jim Wilson
- Learning SQL (3rd edition) - Alan Beaulieu
- NoSQL for Mere Mortals - Dan Sullivan
- Graph Databases (2nd edition) - Ian Robinson, Jim Webber, Emil Eifrem

### B01 Relational databases and SQL

### B02 SQL Query language

### B03 Object-relational databases

### B04 Key-value databases

### B05 Document databases

### B06 Graph databases

## Machine Learning

- Hands-on Unsupervised Learning Using Python - Ankur A. Patel
- Feature Engineering for Machine Learning - Alice Zheng and Amanda Casari
- Machine Learning Pocket Reference - Matt Harrison
- Deep Learning with Python (2nd edition) - François Chollet
- Hands-on Machine Learning with Scikit-Learn, Keraaas and TensnorFlow (2nd edition) - Aurélien Géron
- [Deep Learning](https://www.deeplearningbook.org) - Ian Goodfellow, Yoshua Bengio, Aaron Courville

### C01 Unsupervised learning

### C02 Supervised learning

### C03 Pragmatic classical ML

### C04 Foundations of deep learning

### C05 Pragmatic deep learning

### C06 Explainable AI

## Data Engineering

- Learn Docker in a Month of Lunches - Elton Stoneman
- Python for DevOps - Kennedy Behrman, Noah Gift, Grig Gheorghiu, Alfredo Deza
- Introducing MLOps - Clément Stenac, Léo Dreyfus-Schmidt, Kenji Lefevre, Nicolas Omont, Mark Treveil
- Building Machine Learning Pipelines - Catherine Nelson and Hannes Hapke
- Learning Spark (2nd edition) - Jules S. Damji, Brooke Wenig, Tathagata Das, Denny Lee
- Spark: The Definitive Guide - Matei Zaharia
- Graph Algorithms - Mark Needham, Amy E. Hodler

### D01 Functional programming

### D02 Distributed computation

### D03 Distributed ML

### D04 Distributed Graph Algorithms

### D05 Data science operations

### D06 Workflow management

## Specialized Domains 

- Practical Time Series Analysis - Aileen Nielsen
- Natural Language Processing in Action - Hobson Lane, Cole Howard, Hannes Hapke
- Natural Language Processing with Spark NLP - Alex Thomas
- Deep Learning for the Life Sciences - Peter Eastman, Vijay Pande, Bharath Ramsundar, Patrick Walters
- Genomics in the Cloud - Geraldine A. Van der Auwera, Brian D. O'Connor

### E01 Time Series

### E02 Image Processing

### E03 Genomics

### E04 Natural Language Processing