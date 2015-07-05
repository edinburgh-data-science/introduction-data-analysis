# Python for Data Analysis

This course would build on the first-year *Foundations of Data Science* course and teach students data analysis skills using Python and [pandas](http://pandas.pydata.org/). Students would be expected to bring their own computers to class. Ideally I would like to have a ["flipped classroom"](https://en.wikipedia.org/wiki/Flipped_classroom): I would assign readings, video lectures, and problem sets for students to cover on their own outside of class; lectures meanwhile would focus entirely on practical applications.

While *R* is currently the more widely used language for data analysis...

![Python vs R data analysis jobs](http://www.indeed.com/trendgraph/jobgraph.png?q=python+and+%22data+analysis%22%2C+R+and+%22data+analysis%22)

...Python is quickly gaining ground!

![Python vs R data analysis jobs growth](http://www.indeed.com/trendgraph/jobgraph.png?q=python+and+%22data+analysis%22%2C+R+and+%22data+analysis%22&relative=1)

## Course syllabus
Course text will be [*Python for Data Analysis*](http://shop.oreilly.com/product/0636920023784.do). Book is getting a bit dated so I will supplement as necessary.

### Week 1: Introductory examples
This course teaches you the Python tools to work productively with data. Data analysis tasks generally fall into a number of different broad groups:

* Interacting with the outside world: reading and writing with a variety of file formats and databases.
* Preparation: cleaning, munging, combining, normalizing, reshaping, slicing and dicing data for analysis.
* Transformation: applying mathematical and statistical operations to groups of data sets to derive new data sets. For example, aggregating a large table by group variables.
* Modeling and computation: connecting your data to statistical models, machine learning algorithms, or other computational tools.
* Presentation: creating interactive or static graphical visualizations or textual summaries.

This week I will show you a few data sets and some things we can do with them. These examples are just intended to pique your interest and thus will only be explained at a high level. 

### Week 2: IPython

### Week 3: NumPy
[NumPy](http://www.numpy.org/), short for Numerical Python, is the fundamental package required for high performance scientific computing and data analysis. It is the foundation on which nearly all of the higher-level Python data analysis tools are built. 

### Week 4: Getting started with pandas
The [pandas](http://pandas.pydata.org/) library will be the primary library of interest throughout much of the course. It contains high-level data structures and manipulation tools designed to make data analysis fast and easy in Python.

### Week 5: Data loading, storage, and file formats
The tools in this book are of little use if you can’t easily import and export data in Python. I’m going to be focused on input and output with pandas objects, though there are of course numerous tools in other libraries to aid in this process. Input and output typically falls into a few main categories: reading text files and other more efficient on-disk formats, loading data from databases, and interacting with net- work sources like web APIs.  We will cover each in turn.

### Week 6: Data wrangling
Much of the programming work in data analysis and modeling is spent on data preparation: loading, cleaning, transforming, and rearranging. The pandas librart along with the Python standard library provide you with a high-level, flexible, and high-performance set of core manipulations and algorithms to enable you to wrangle data into the right form without much trouble.

### Week 7: Plotting and visualization
Making plots and static or interactive visualizations is one of the most important tasks in data analysis. This chapter is quite dated and probably needs to be skipped. Instead we will briefly cover the basics of [Matplotlib](http://matplotlib.org/) and instead spend most of our time  on the next generate of Python data visualization tools:

 * [plot.ly](https://plot.ly/)
 * [ggplot](http://ggplot.yhathq.com/)
 * [seaborn](http://stanford.edu/~mwaskom/software/seaborn/)
 * [bokeh](http://bokeh.pydata.org/en/latest/)
 * [mpld3](http://mpld3.github.io/)

### Week 8: Data aggregation and group operations
Categorizing a data set and applying a function to each group, whether an aggregation or transformation, is often a critical component of a data analysis workflow. After loading, merging, and preparing a data set, a familiar task is to compute group statistics or possibly pivot tables for reporting or visualization purposes. pandas provides a flex- ible and high-performance groupby facility, enabling you to slice and dice, and sum- marize data sets in a natural way.

### Week 9: Time series
The pandas library provides a standard set of time series tools and data algorithms. With this, you can efficiently work with very large time series and easily slice and dice, aggregate, and resample irregular and fixed frequency time series. As you might guess, many of these tools are especially useful for financial and economics applications

### Week 10: Financial and Economic data applications