## Project: Email Spam Detection using Naive Bayes Classifier

### Install

This project requires **Python** and the following Python libraries installed:

- [NumPy](http://www.numpy.org/)
- [Pandas](http://pandas.pydata.org/)
- [scikit-learn](http://scikit-learn.org/stable/)
- [nltk](https://www.nltk.org/)

You will also need to have software installed to run and execute a [Jupyter Notebook](http://jupyter.org/install.html).

If you do not have Python installed yet, it is highly recommended that you install the [Anaconda](https://www.anaconda.com/download/) distribution of Python, which already has the above packages and more included. 

### Code

Full code is provided in the `main.ipynb` notebook file. You will also be required to use the `emails.csv` dataset file to run the notebook.

### Run

In a terminal or command window, navigate to the top-level project directory `email-spam-detection/` (that contains this README) and run one of the following commands:

```bash
ipython notebook main.ipynb
```  
or
```bash
jupyter notebook main.ipynb
```
or open with Juoyter Lab
```bash
jupyter lab
```

This will open the Jupyter Notebook software and project file in your browser.

### Data

The emails dataset consists of 5728 data points, with each datapoint having 1 feature.

**Features**
1.  `text`: text of the email

**Target Variable**
2.  `spam`: (1) is a spam, (0) is not a spam
