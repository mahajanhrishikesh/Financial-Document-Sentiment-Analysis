# Financial-Document-Sentiment-Analysis
<h1>Machine Learning Techniques for Financial Sentiment Analysis </h1>
The modern stock market generates large amounts of data regarding
specific stocks. Along with this data, the opinion of various
experts/investors are available freely on the internet. Quantifying the
general sentiment regarding the stock based on such data will help in
predicting the trend (Bearish/Bullish) of the stock price. This can be achieved with the help
of several supervised machine learning techniques trained using a corpus
of positive as well as negative financial news/blogs/reviews. Some of the
major challenges are identifying the appropriate sources for stock related
data, pre-processing unstructured text and converting the same to
structured data in a scalable and efficient manner. 

<pre>
Work done until now:
  1. Scrapped Moneycontrol website and created dataset for financial data [<a href="https://github.com/mahajanhrishikesh/Financial-Document-Sentiment-Analysis/blob/master/Web%20Scrapper%20MoneyControl.ipynb">Web Scrapper MoneyControl.ipynb</a>]
    1.1. [<a href="https://github.com/mahajanhrishikesh/Financial-Document-Sentiment-Analysis/blob/master/MoneyControl-First-1-20-Pages.csv">MoneyControl-First-1-20-Pages.csv</a>] was created by the above notebook
  2. Applied text classification model Support Vector Classifier for Sentiment Analysis [<a href="https://github.com/mahajanhrishikesh/Financial-Document-Sentiment-Analysis/blob/master/Text%20Classification%20Money%20Control.ipynb">Text Classification Money Control.ipynb</a>]
  3. Applied Sequence Classification with LSTM Model [<a href="https://github.com/mahajanhrishikesh/Financial-Document-Sentiment-Analysis/blob/master/LSTM%20Sentiment%20Analysis.ipynb">LSTM Sentiment Analysis.ipynb</a>]
    3.1. Model Generated [<a href="https://github.com/mahajanhrishikesh/Financial-Document-Sentiment-Analysis/blob/master/money_control_model.h5">money_control_model.h5</a>]
  4. Vader Sentiment Analysis
</pre>
