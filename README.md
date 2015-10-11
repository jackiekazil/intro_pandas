Introduction to Pandas
======================
Clara Bennett & Tyler Jorgensen, [Picwell](http://nerds.picwell.com/)

*Class materials for PyLadies DC -- October 11, 2015*

---

## Viewing the materials
The class materials combine code and notes in IPython notebooks. You can view the [tutorial notebook](pandas_tutorial.ipynb) and the [case study notebook](pandas_case_study.ipynb) right in GitHub. (They render IPython notebooks now! How cool is that??)

However, we chose to use IPython notebooks so that you can easily play with the code yourself and build your understanding of the Pandas library by seeing what happens when you change things. Therefore, we _highly_ recommend that download this git repository and run the notebooks yourself locally.

## Running the materials locally

### Download the git repository
If you are familiar with git, go ahead and clone this repository. If not, you can click the "Download Zip" button to get a zipped folder with all of the files downloaded to your local machine. Unzip the folder and put it somewhere that you can easily access via the command line.

### Installs
The required libraries to run the `pandas_tutorial.ipynb` notebook are found in `requirements.txt`. The additional libraries required to run `pandas_case_study.ipynb` are found in `optionals.txt`. To install the requirements with [pip](http://pip.readthedocs.org/en/stable/installing/), simply change to the `intro_pandas` directory and run

```
pip install -r requirements.txt
```

You may need to use `sudo` if you're going to install the requirements to your system, rather than in a [virtualenv](https://virtualenv.pypa.io/en/latest/).

Alternatively, you can install all of the requirements and basically anything else that you would need to work with data in Python by installing the [Anaconda](https://www.continuum.io/downloads) distribution. It comes bundled with all the pydata things.

### Run the IPython Notebook server
Once you have everything installed, navigate to the `intro_pandas` directory from the command line and run

```
ipython notebook
```

This will start the IPython Notebook server and open a new tab in your browser that shows the contents of the `intro_pandas` directory. Do not close the command line window that is running the server.

### Run the course notebooks
In your IPython Notebook browser tab, click on `pandas_tutorial.ipynb`. This will open yet another tab with the tutorial notebook in it.

Note that while every cell already has an input number and an output number, none of the cells have actually been run yet in this session. We recommend going to `cell > run all` as a first step, so that the whole notebook is loaded into memory and you can re-run whichever cells you like.

To run a cell and advance to the next one, press `shift + enter`. The results of the last line in the cell will be output below it. As you go through the notebook, feel free to modify the data and the code to see how the output changes. You can add new cells via the `insert` menu at the top.

Happy learning!
