# Learn to Rehydrate a Tweetset

Our tutorial *Learn to rehydrate Twitter data using Python: case #hellobrother* guides you through the process of (dehydrating and) rehydrating a tweetset. Here, the tweetset represents #hellobrother, one of the emerging themes related to the Christchurch mosque shooting in 2019.

The full analysis process is described in the following publication:

<div style="margin-left: 25pt">
Harju, A. A., & Huhtamäki, J. (2021). ‘#hellobrother needs to trend’: methodological reflections on the digital and emotional afterlife of mediated violence. *International Review of Sociology, 31(2), 1–32.* [https://doi.org/10.1080/03906701.2021.1947951](https://doi.org/10.1080/03906701.2021.1947951)
</div>

The full tutorial will be available under SAGE [Research Methods](https://methods.sagepub.com/) and its upcoming collection Doing Research Online. Specifically, this tutorial is part of Datasets, short, very practical and accessible teaching articles, where excerpts of real data are provided and used as an example to teach a particular data analysis method or technique. They are intended to give insight into how an experienced researcher could use a technique to answer a research question. 

First and foremost, you need to have a [valid Twitter developer account](developer.twitter.com). If you are a scholar, you may qualify for [Academic Research access](https://developer.twitter.com/en/products/twitter-api/academic-research).   

The following tutorials and instructions give you the necessary background information to work with the tutorial:

* [Python For Beginners](https://www.python.org/about/gettingstarted/)
* [Jupyter](https://jupyter.org/)
* [Twython](https://twython.readthedocs.io/en/latest/usage/install.html)
* [Collect Twitter Data with Twarc!](https://scholarslab.github.io/learn-twarc/)
* [Getting started with Pandas](https://pandas.pydata.org/docs/getting_started/index.html)

One way to access the necessary tools is to use [Anaconda](https://www.anaconda.com/).

In case you prefer to install the tools one by one, ideally, you will set up [a virtual environment](https://docs.python.org/3/library/venv.html) for the project.

A simple procedure for Linux and MacOS follows.

Create a virtual environment:

    python -m venv venv

Activate the environment:

    source venv/bin/activate

Install modules using [pip](https://pip.pypa.io/en/stable/):

    pip install -r requirements.txt

Start Jupyter server:

	jupyter notebook
	
Open the browser, download [the tutorial notebook](https://github.com/HYTE-research/SAGE-data-hellobrother/blob/main/Full%20Tutorial.ipynb) and start experimenting!