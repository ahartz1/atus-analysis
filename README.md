# Wasting Time: Analyzing the ATUS Dataset

## Description

The U.S. Bureau of Labor Statistics publishes yearly data about Americans' use of their time: [American Time Use Survey](http://www.bls.gov/tus/home.htm#data).

This data is used to find out information like how many hours the average person spends per day doing household activities. You can see [the 2014 survey results](http://www.bls.gov/news.release/atus.nr0.htm) for more examples.

I have analyzed the respondents' laundry activities, kitchen and food clean-up activities, and number of hours worked per day and per week. I've broken these areas down into more specific sub-groups to get at data I considered to be interesting.

## To View This Notebook
Just click on the `atus-analysis.ipynb` file above.

## To Run This Notebook
### System Requirements / Installation

* You will need to have **python&nbsp;3** installed on your machine. See [python's site](https://www.python.org/) for details.

* Clone this repo onto your machine.

* You will need to make sure that you have a virtual environment running in the folder that you intend to work from. [See this site for details if you're not familiar.](http://docs.python-guide.org/en/latest/dev/virtualenvs/) **Complete this step before attempting the below.**

* In your command-line program (such as Terminal on Mac&nbsp;OS&nbsp;X), navigate into the newly created repo. By default, this will be called `atus-analysis`. Install the requirements file by runnning **`pip install -r requirements.txt`**.

* You will need to download the data files by running the `download_data.sh` script. (Enter and run the following line at your command prompt: `./download_data.sh`)

### Opening the Notebook
* Using a command-line program, navigate to the folder containing the downloaded file and run the following line: **`ipython notebook atus-analysis.ipynb`**

* **Note:** This will open in a browser window and take over the command-line program's window until you close out of IPython Notebook. If you have closed your browser window, but your command line is still running the notebook, kill the process by pressing `Ctrl+C` or quitting the program entirely.

## Additional Resources

* [How to use ATUS microdata files](http://www.bls.gov/tus/howto.htm)
* [ATUS Coding Lexicon - you will need this](http://www.bls.gov/tus/lexicons.htm)
