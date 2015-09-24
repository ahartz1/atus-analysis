# Wasting Time: Analyzing the ATUS Dataset

## Description

Use the U.S. Department of Labor's data on Americans' time use for research and analysis.

## Objectives

### Performance Objectives

After completing this assignment, you should be able to:

* Use pandas to parse and analyze data
* Use matplotlib to chart data
* Clean data

## Details

### Deliverables

* A Git repo called atus-analysis containing at least:
  * `README.md` file explaining how to run your project
  * a `requirements.txt` file
  * an IPython notebook with your analysis
  * a suite of tests for your project

### Requirements  

* Passing unit tests
* No PEP8 or Pyflakes warnings or errors

## Normal Mode

The U.S. Bureau of Labor Statistics publishes yearly data about Americans' use of their time: [American Time Use Survey](http://www.bls.gov/tus/home.htm#data).

This data is used to find out information like how many hours the average person spends per day doing household activities. You can see [the 2014 survey results](http://www.bls.gov/news.release/atus.nr0.htm) for more examples. You should use these results to double-check your logic as well.

You will download the 2014 files and use these to do analysis. The questions you are trying to answer are up to you, but they should at least:

* Compare different populations (people with children and people without, people of differing age groups, men and women, or other groupings)
* Answer macro-level questions and micro-level questions (for example, the amount of leisure for the macro-level, the types of things people do for leisure for the micro-level)

Your final analysis should be in the form of an IPython Notebook with both narrative analysis and supporting charts. Any supporting code should be in normal Python files.

## To View This Notebook
Just click on the `atus-analysis.ipynb` file above.

## To Run This Notebook
### System Requirements / Installation

* You will need to have **python&nbsp;3** installed on your machine. See [python's site](https://www.python.org/) for details.

* Clone this repo onto your machine.

* You will need to make sure that you have a virtual environment running in the folder that you intend to work from. [See this site for details if you're not familiar.](http://docs.python-guide.org/en/latest/dev/virtualenvs/) **Complete this step before attempting the below.**

* In your command-line program (such as Terminal on Mac&nbsp;OS&nbsp;X), navigate into the newly created repo. By default, this will be called `atus-analysis`. Install the requirements file by runnning **`pip install -r requirements.txt`**.

### Opening the Notebook
* Using a command-line program, navigate to the folder containing the downloaded file and run the following line: **`ipython notebook atus-analysis.ipynb`**

* **Note:** This will open in a browser window and take over the command-line program's window until you close out of IPython Notebook. If you have closed your browser window, but your command line is still running the notebook, kill the process by pressing `Ctrl+C` or quitting the program entirely.

## Additional Resources

* [How to use ATUS microdata files](http://www.bls.gov/tus/howto.htm)
* [ATUS Coding Lexicon - you will need this](http://www.bls.gov/tus/lexicons.htm)
