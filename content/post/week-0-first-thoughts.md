+++
title = "Week 0 | First Thoughts"
description = "Some initial thoughts about the summer ahead ..."
date = 2019-05-29T00:00:00Z

tags = [
    "python",
    "weekly updates",
    "journal",

]

categories = [
    "python",
    "updates",
]
+++

## REVIEW OF COMPUTATIONAL WORKSHOP 0

We had a wonderful inaugural session last Friday!  You can find [the slides here](/soars19ctds/assets/SOARS_WS0_05252019.pdf) if you'd like to go over the content again.  

### THE COMPUTATIONALLY F-A-I-R FUTURE

I want to encourage you again, to read the [Gil, et. al paper](http://doi.org/gc4h73) as it sets the stage for many of the things coming over the summer and over the course of your academic careers to come.  Reiterating the conversation about FAIR notebooks, I would also recommend you:
 
 * check out the poster I did last year at a scientific software workshop at UT/Austin on [FAIR computational notebooks](https://doi.org/10.6084/m9.figshare.6198554.v1); and

* read this recent PLOS One blog post on [Supporting FAIR data in Earth, Space and Enviromental Sciences](https://blogs.plos.org/everyone/2018/11/05/supporting-fair-data-in-the-earth-space-and-environmental-sciences/) which gives you some real insight as to how important this topic is becoming in publishing.

### PYTHONISTAS UNITE!
It is encouraging to see that Python is making its way into your coursework, as I see informally that nearly all of you are getting at least some exposure to it.  Please know that in terms of the geosciences, Python is important for a number of reasons, but one of the most important is that there is really strong support for it in the multitude of libraries and code repositories using it to solve geoscience problems.

I wanted to point out there are so many great repositories on Github for [using Python in the Geosciences](https://github.com/search?q=geoscience+python), but here are three you are strongly encouraged to bookmark:

* [`python_for_geosciences`](https://github.com/koldunovn/python_for_geosciences) repository contains a number of really good notebooks from introductory Python, to maps, time series, and much more.  You might [view it more comfortably with NBViewer](https://nbviewer.jupyter.org/github/koldunovn/python_for_geosciences/blob/master/00%20-%20Why%20Python.ipynb);
* [`Awesome Open Geoscience`](https://github.com/softwareunderground/awesome-open-geoscience) is a really strong resource that neatly organizes the things you need to know.  The list is openly curated, and there are a number of really nice resources including the "Basic Geoscience Cheatsheet" one-pager that you may (or may not) find useful. 
* [`Research Computing in Earth Science`](https://rabernat.github.io/research_computing_2018/) graduate course website at Columbia University.  This course hits the mark with where things are going with Python and computing in general.  You will want to take some of the content _very_ seriously in applying what you learn to your future skills and goals as 21st century graduate students and scientists.

### WHY GITHUB, AGAIN?

We will be using [JupyterHub](https://jupyter.org/hub) in the workshops like last year, and in order to use the environment, you will need to get your a Github account set up .  As I mentioned in the introduction, Github is (arguably) _the place_ for open source software on the Internet, and it is increasingly the place where computational digital scholarship is happening.  Many scholars are using Github to share their research in the open, since it is a platform that is conducive to sharing software assets of all kinds, from code, to text files, papers, preliminary results, datasets, visualizations, etc.

## LOOKING AHEAD TO (WEEK 1) WORKSHOP 1

### FOR NEW PROT&Eacute;G&Eacute;S  

There is one thing that you can be certain of as your career in atmospheric and geo- science progresses: you will need to be familiar with formulating computational solutions to problems.  So what is this _computational thinking_ anyway?  Quite simply, it is _algorithmic_ thinking, or ways to develop solutions to problems that (mainly computers, but sometimes humans) can carry out.  It is thinking about how to break a problem down so that you can identify the key abstractions of the problem, and to apply the computational tools necessary to approach those abstractions effectively and efficiently.  It isn't really about "programming", per s&eacute;, since a good "computational solution", can be programmed on any machine and in any language. 

It is also developing a way of thinking at capitalizes on _scaling_ your solution to work on larger problems efficiently.  Computational thinking is not restricted to computer science, indeed, nearly all modern scientific domains rely on computers to solve a myriad of complex problems &mdash; arguably we are at an epoch in civilization where, perhaps, that reliance is permanent &mdash; and now even [the humanities has turned a computational leaf](https://digitalhumanities.mit.edu/).

* **For workshop 1 (AM) this week**, we're going to start to explore some core concepts in computational thinking and problem solving, especially around problem abstraction and decomposition.


### FOR RETURNING PROT&Eacute;G&Eacute;S 

Our friends at [Unidata](https://www.unidata.ucar.edu/) have graciously provided a JupyterHub-based computational platform for us to conduct our workshops.  This playground requires that you use your Github account (created last year) to gain access to the JupyterHub where you are free to not only [explore the many tutorials already provided by Unidata](https://www.unidata.ucar.edu/support/index.html#training), but also to work on code of your own.  Access to the Hub will (at least for now), only be available through the summer.

Unidata is a UCAR Community Program (UCP) operating with support from the NSF "[that] has been providing data, software tools, and support to enhance Earth System education and research"[^about-unidata].  Among other things, they manage and maintain cloud infrastructure for geoscience-related data and software, as well as develop a number of software modules in a variety of languages, specifically related to manipulating geospatial, atmospheric and meteorological data.  From your university courses, you might have used [NetCDF](https://www.unidata.ucar.edu/software/netcdf/) (Network Common Data Format) &mdash;which is a data format that UCAR and Unidata developed in 1989.  NetCDF is still currently maintained and developed here at UCAR within Unidata.  If you are not familiar with NetCDF, you may want to check out [this demo](https://unidata.github.io/MetPy/latest/examples/Four_Panel_Map.html?highlight=netcdf) of loading NetCDF data and plotting a four panel map.

* **For workshop 1 (PM) this week** we'll explore the JupyterHub enviroment and a few of the included tutorials, so make sure you have your Github account (and check out the email about logging in).


[^about-unidata]: About Unidata, [https://www.unidata.ucar.edu/about/](https://www.unidata.ucar.edu/about/)