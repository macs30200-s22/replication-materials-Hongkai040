# replication-materials-Hongkai040	

### Current Findings:

1. Prelinary explorations suggest that there’s a change of sentiment of users between 2014 and 2015.
2. Active users tend to give lower ratings compare to other less active users in all years.
3. Active users themselves become negative overtime, which is mainly captured by the fact that they tend to give higher proprotion of high ratings but lower proportion of medium ratings and NaN ratings.

### Data:

The whole dataset is over 800MB(over 4 million commments), making it unsuitable for storing on Github. So here a sample of 5000 movie comments is uploaded)

**Link to scraping program and full size dataset**:https://github.com/csuldw/AntSpider

### Code:

**Local**:

The code run in local environment is written in python 3.8.5. and all of its dependencies can be installed by running the following in the terminal (with the `requirements_local.txt` file included in this repository):

```
pip install -r requirements_local.txt
```

Then you can download all the dataset and change all the directories specified in the code into your local machine directory, and run all the cell in sequence to reproduce all the results. 

**Colab**:

The code run on Colab is written in python 3.8.5. Training ther BERT model on Colab requires a Tesla P100 or better GPU.

**Link to Colab notebook**:https://colab.research.google.com/drive/1gPmc4gAv7iFKojHmtsbO3W4TbBUXick4?usp=sharing



