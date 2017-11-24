# What this is
First steps into Kaggle following along on the python tutorial for the Titanic optimization.

As far as I know so far, this is the base level for getting things to work within a virtual environement.
I had to do a `brew install gcc` to ensure that the scikit learn library behaved correctly.

There were also various things to make sure that iPython worked correctly within the virtualenv.

# How to run
This uses the Titanic Data from Kaggle, which is within the `data` directory.
Although, the way it's written right now the data could easily be rewritten for
different files.

To use, it's recommended you use a python virtualenv.
To create: `virtualenv -p python3 envname`

Then, within that directory clone this project. This project also requires that
you use ipython to run, so to run: `ipython notebook.py `
