# Machine Learning for Natural and Life Sciences Tutorial

## How to use this

If you just want to look at the examples, open any of the notebooks or the corresponding HTML exports in this repo.

If you want to start coding yourself, follow the installation procedures below to get started.

## Installation

### Required libraries

To get the notebooks in this tutorial running, we recommend using a Python installation via [Anaconda](https://www.anaconda.com/distribution/).

We also recommend setting up a separate virtual environment. This bundles all the packages you need.

```
conda create -n ml-tutorial
conda activate ml-tutorial
```

Then, install the packages that will become your toolbox for this tutorial.

```
conda install numpy matplotlib skikit-learn jupyter
conda install pytorch torchvision -c pytorch
```

The last command is only necessary for the neural networks chapter.

### This library

```
git clone https://github.com/VLL-HD/ML-Tutorial
cd ML-Tutorial
```

To start the Jupyter notebook server, execute

```
jupyter notebook
```

A browser window will automatically open where you can view and edit the notebooks.


## Credits

Script by Ullrich Köthe, code by Felix Draxler. Both at [Visual Learning Lab, Heidelberg University](https://hci.iwr.uni-heidelberg.de/vislearn/people/).