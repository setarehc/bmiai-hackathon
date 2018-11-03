# BMIAI Hackathon
## Getting started
### 1- Anaconda
Anaconda is a package and environment manager for Python. There is other package managers as well, but Anaconda is self-contained and maintains packages neatly. You can download it from [here](https://www.anaconda.com/download/).

After you downloaded Anaconda, make sure Python3 uses the one in Anaconda.

```
$ which python
/home/<your-username>/anaconda3/bin/python
```

If it did not work, updating your PATH might help:

```
$ export PATH="/home/<your-username>/anaconda3/bin:$PATH"
```

If you are not using Anaconda, make sure Python3 is installed on your machine.

### 2- Jupyter notebook
Jupyter notebook is a nice environment for running your codes and writing reports in the same page. It also provides an interactive environment for programming, i.e. no need to run your code from scratch every time.

In this tutorial, we will use Jupyter notebook for walkthroughs. You can even use them to do the main challenge.

If you have Anaconda, Jupyter notebook is already installed and you can launch it using

```
$ jupyter notebook
```

A browser window should be popped out containing a Jupyter notebook Home showing the terminal's current directory contents.

In case you don't have Anaconda, check [this](http://jupyter.org/install) out.

### 3- Packages
You would need the following packages for this tutorial:

- [pandas](https://pandas.pydata.org/)
- [numpy](http://www.numpy.org/)
- [torch](https://pytorch.org/)
- [scikit-learn](http://scikit-learn.org)
- [seaborn](https://seaborn.pydata.org/)

Other than torch, the rest should come with Anaconda.

You should be all set now. Let's get started with `Intro.ipynb`