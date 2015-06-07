# Cluster cereals by nutritional values

## Description

Using K-means clustering (or another clustering algorithm), find clusters
of cereals and explain the clusters.

## Objectives

### Learning Objectives

After completing this assignment, you should be able to:

* Distinguish pertinent features in a data set
* Demonstrate the use of K-means clustering
* Modify original data into data better suited to clustering using Pandas
  and NumPy
* Combine multiple machine learning algorithms

## Details

### Deliverables

* A Git repo called honey-nut-clusters containing at least:
  * a `requirements.txt` file
  * An IPython notebook with your code and findings

### Requirements  

* Passing unit tests
* No PEP8 or Pyflakes warnings or errors

## Normal Mode

Read in the data in `cereals.csv` and cluster the cereals by the features you
choose.

Try different amounts of clusters to see what works best, starting with 3.

Once you have your final clusters, analyze their contents. Give each cluster
a name and a description explaining how the cereals in it are similar.

Write up all your analysis, complete with any graphs that may be helpful to
understand it.

Note that there are a few pieces of missing data in the cereals data. You may
want to fill these in using linear regression or another technique.

Two other notes:

1. This data is by serving size. You might consider changing it to be by
   weight or volume.
2. See [this answer on Stack Overflow about normalizing data and other tips](http://stats.stackexchange.com/a/21226). You may want to consider normalizing your data before clustering or that answer's idea about order randomization.

## Hard Mode

1. Get data from other cereals you know of. Use the clusters you came up with
   to create a classification algorithm and classify those cereals.

2. Read [this article on mean shift clustering](http://spin.atomicobject.com/2015/05/26/mean-shift-clustering/)
(warning: math-heavy) and then try using mean shift clustering on your cereals.
What is different about your clusters using mean shift?
