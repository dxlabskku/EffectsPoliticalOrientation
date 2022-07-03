# The sentimental scores
We collected news titles are 550 and comments are 44,446 for candidates of Seoul Mayor from Youtube.
1. Crawled all data by python using Youtube API.
   (https://developers.google.com/youtube/v3/getting-started)
2. News titles and comment for news outlets' Youtube channels in South Korea.
3. Filtering data by rules that we made.
   * The number of news titles are 79 and comments are 7,141 for progressive candidate, 108 and 15,538 for conservative candidate respectively.
   * data_result.csv : The result of sentiment score of titles that provided by progressive and conservative news outlets.
   * data_collection.ipynb : This ipynb read the csv file and represent the sentimental scores of titles.
