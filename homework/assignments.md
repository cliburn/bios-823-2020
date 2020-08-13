# Homework Projects

You are expected to follow the Duke Honor Code. You can discuss ideas and approaches with your classmates, but you are not allowed to copy code or text from each other. Cite any resources you used to complete each assignment.

- Each project is worth 10 points.
- Any points you get over 50 will count as 1/2 point that can be used to boost your exam or final project score. For example, if you get a total of 70 points on the 8 assignments, you will effectively get an extra credit for 10 points.
- You need to do #1. 
- Assignments are due on Friday 11:59 PM every 2 weeks in the order listed.
- Every assignment must have code committed (with meaningful log messages) to GitHub.

## Assignments

1. Start a personal website on [GitHub Pages](https://pages.github.com) using a static site generator such as [`pelican`](https://blog.getpelican.com) or [`hugo`](https://gohugo.io). You can find tutorials for how to do on the web. This will be your data science project portfolio. The first project in your portfolio is to write a blog describing how you did this exercise.
2. Solve 3 problems from the [Euler Project](https://projecteuler.net/archives) using Python. Of the 3 problems, one must have been solved by fewer than 25,000 people, 1 fewer than 100,000 people and one fewer than 500,000 people. Write a function for each problem, and use [`nuympy`-styple docstrings](https://numpydoc.readthedocs.io/en/latest/format.html) to annotate each function. Write a blog page describing your solutions and how you approached each problem. 
3. Download the [Spotify songs](https://github.com/rfordatascience/tidytuesday/blob/master/data/2020/2020-01-21/readme.md) data set. Create a SQLite3 schema to store this data in at least 3rd normal form (3NF), and populate the tables. Use an SQL query to find the names of all playlists that contain instrumentals. Blog.
4. Using the `requests` library, download all the people in the Star Wars universe using the Star Wars API (https://swapi.dev/documentation). Show the name of the oldest person (or robot or alien) and list the titles of all the films they appeared in. Blog.
5. Download data of [PhDs awarded in the US](https://ncses.nsf.gov/pubs/nsf19301/data). Do some analysis in `pandas`. Make a dashboard visualization of a few interesting aspects of the data using [`dash`](https://plotly.com/dash/) or [`streamlit`](https://www.streamlit.io/). Blog.
6. Download 100 abstracts (at least 100 words per abstract) from PubMed that have `schizophrenia` and another 100 that have `dementia` in the title. Split randomly into 100 for a training set and 100 for a test set. Train a machine learning algorithm of your choice to predict the group (schizophrenia or dementia) from the abstract. Show a confusion matrix and ROC plot of the test sample predictions. Blog.
7. Train a deep learning model to classify beetles, cockroaches and dragonflies using these [images](https://www.dropbox.com/s/fn73sj2e6c9rhf6/insects.zip?dl=0). Note: Original images from https://www.insectimages.org/index.cfm. Blog about this, and *explain* how the neural network classified the images.
8. Provide a [Google AI Platform](https://cloud.google.com/ai-platform/prediction/docs/deploying-models) website using [TensorFlow Serving](https://www.tensorflow.org/tfx/guide/serving) that allows the user to get a predicted classification of an uploaded image as beetle, cockroach or dragonfly. (This assumes you have done #7).