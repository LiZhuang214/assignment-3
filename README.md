# Assignment #3

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/MUSA-620-Spring-2019/assignment-3/master)

### Due Date: 2/27 by the start of class

In this assignment, we'll explore spatial trends evictions in Philadelphia using data from the [Eviction Lab](https://evictionlab.org/) and building code violations using data from [OpenDataPhilly](https://www.opendataphilly.org/).

We'll be exploring the idea that evictions can occur as retaliation against renters for reporting code violations. Spatial correlations between evictions and code violations from the City's Licenses and Inspections department can offer some insight into this question.

### Topics covered

- geopandas and spatial operations
- hvplot
- APIs

#### Background readings

- [HuffPost article](https://www.huffingtonpost.com/entry/cities-are-starting-to-pay-attention-to-the-eviction-crisis-thats-devastated-poor-tenants_us_5b1a7b21e4b0bbb7a0dbd59e)
- [PlanPhilly article](http://planphilly.com/articles/2018/04/12/philly-landlords-evict-more-people-than-owners-in-other-large-cities)
- [The Eviction Lab](https://evictionlab.org/)
- [Data Dictionary for Eviction Lab data](https://eviction-lab-data-downloads.s3.amazonaws.com/DATA_DICTIONARY.txt): also available for download in this repository

## Assignment details

A skeleton Jupyter notebook is available in this repository that will walk you through the steps of the assignment. The completed notebook should be submitted as your assignment.

## Submission

We'll be using GitHub for assignment submission again. You can set up your own private repository on GitHub for this assignment using the link below.

The invitation link for this week is:

If you do not have a GitHub account yet, you should be prompted to make an account. After clicking on this link, GitHub will create a new private repo with permissions such that only you and the instructors can view the commits.

The assignment should be added to this GitHub repository before the deadline. You can add files to the repository through the web (github.com) interface or using the command line locally on your machine.

Below are some references if you need help:

- [Setting up git](https://help.github.com/articles/set-up-git/)
- [Managing files on GitHub](https://help.github.com/articles/managing-files-on-github/)
- [Managing files via the command line](https://help.github.com/articles/managing-files-using-the-command-line/)

**Important**: files should be committed to the newly created private repository (after following the above link) and _not_ to your forked version of the [assignment-2](https://github.com/MUSA-620-Spring-2019/assignment-2) repository.

## Installing the necessary dependencies

The Python dependencies used for this assignment are the same as through week 4. If you've updated your local environment already for week 4, you shouldn't need to install any more dependencies. If not, follow the instructions below.

First, download the `environment.yml` file in this repository to your computer.

**Important**: if you are on a Windows machine, make sure that `.txt` wasn't appended to the file name when you downloaded it. If so, you will need to rename it so the file ends in `.yml`.

Then you can run, from either the Anaconda Prompt (Windows) or Terminal app (MacOS):

```
conda env update --file environment.yml --name musa
```

where `musa` should be the name of the environment you have been using.

**Important:** If you are starting a Jupyter notebook through the command line, you must activate the environment before you start a notebook:

```
conda activate musa
jupyter notebook
```

If you are starting through Anaconda Navigator, be sure to select the right environment (change `base` to `musa`) before hitting the `Launch` button!
