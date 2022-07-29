# Analyze Tweets Sentiment Using NLP

[![Generic badge](https://img.shields.io/badge/Datascience-Beginners-Red.svg?style=for-the-badge)](https://github.com/turkeruzun/twitter-data-analysis-nlp) [![Generic badge](https://img.shields.io/badge/LinkedIn-Connect-blue.svg?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/turkeruzun)

[![GitHub repo size](https://img.shields.io/github/repo-size/iamsivab/Twitter-Data-Analysis.svg?logo=github&style=social)](https://github.com/turkeruzun) [![GitHub code size in bytes](https://img.shields.io/github/languages/code-size/iamsivab/Twitter-Data-Analysis.svg?logo=git&style=social)](https://github.com/turkeruzun)![GitHub top language](https://img.shields.io/github/languages/top/iamsivab/Twitter-Data-Analysis.svg?logo=python&style=social)

[![Made with Python](https://forthebadge.com/images/badges/made-with-python.svg)](http://turkeruzun.com.tr/kategori/veri-analizi/)

# SUMMARY

This study, analyze on Twitter data related to eating habits in April 2020. The data aims to reveal the effect of new information affected by Covid-19 on diet-related patterns among Twitter users during the pandemic. Sentiment analysis through frequently used words and on ngrams and explores the causal link between information-led society and attitude shifts during the pandemic in cyberspace.

## Installation Packages

Use the package manager [pip](https://pip.pypa.io/en/stable/) to install foobar.

``` bash
pip install nltk
pip install wordcloud
pip install sklearn
pip install pandas
pip install chardet
pip install textblob
pip install gensim
pip install scipy
pip install PIL
pip install pattern
...
```

## Load Packages

``` python
import pandas as pd
import numpy as np
import chardet
import re
import openpyxl
import string
import nltk
from nltk.corpus import stopwords
from nltk.stem import PorterStemmer,WordNetLemmatizer
from pattern.text.en import spelling
from pattern.text.en import suggest
from nltk.sentiment.vader import SentimentIntensityAnalyzer 
from textblob import TextBlob
import gensim
import pyLDAvis.gensim_models
import statistics as st
from scipy.stats import stats,mode
from wordcloud import WordCloud, STOPWORDS, ImageColorGenerator
from PIL import Image
import matplotlib.pyplot as plt
```

## Check Data

![](images/paste-880DC0AF.png)

# STEMMING WORDS + NGRAMS

### ![](images/paste-12510328.png)

![](images/paste-152ECC32.png)

# WORDCLOUD

![](images/paste-78993C9F.png)

# SENTIMENT ANALYZE

![](images/paste-E5299A34.png)

# LDA MODEL - FIND TOPICS

![](images/paste-A6A49787.png)

# HASHTAG SENTIMENT ANALYZE

![](images/paste-F56C8917.png)

# EMOJIES SENTIMENT ANALYZE

![](images/emoji%20sent%20analyze1.png)
![](images/emoji%20sent%20analyze2.png)

# Contributing

[![GitHub issues](https://img.shields.io/github/issues/turkeruzun/twitter-data-analysis-nlp?logo=github)](https://github.com/turkeruzun/twitter-data-analysis-nlp/issues) ![GitHub pull requests](https://img.shields.io/github/issues-pr/turkeruzun/twitter-data-analysis-nlp?color=blue&logo=github)

-   Clone [this](https://github.com/turkeruzun/twitter-data-analysis-nlp) repository:

``` bash
git clone https://github.com/turkeruzun/twitter-data-analysis-nlp.git
```

-   Check out any issue from [here](https://github.com/turkeruzun/twitter-data-analysis-nlp/issues).

-   Make changes and send [Pull Request](https://github.com/turkeruzun/twitter-data-analysis-nlp/pulls).

### Need help?

[![LinkedIn](https://img.shields.io/static/v1.svg?label=connect&message=@turkeruzun&color=success&logo=linkedin&style=flat&logoColor=white&colorA=blue)](https://www.linkedin.com/in/turkeruzun/) [![WP](https://img.shields.io/static/v1.svg?label=Visit&message=turkeruzun.com.tr&color=9cf&logo=wordpress&style=flat&logoColor=white&colorA=informational)](https://turkeruzun.com.tr)

### License

© [turkeruzun](https://github.com/turkeruzun/twitter-data-analysis-nlp)

[![GitHub forks](https://img.shields.io/github/forks/turkeruzun/twitter-data-analysis-nlp.svg?style=social)](https://github.com/turkeruzun/twitter-data-analysis-nlp/network/members) [![GitHub stars](https://img.shields.io/github/stars/turkeruzun/twitter-data-analysis-nlp.svg?style=social)](https://github.com/turkeruzun/twitter-data-analysis-nlp/stargazers) [![GitHub followers](https://img.shields.io/github/followers/turkeruzun.svg?label=Follow&style=social)](https://github.com/turkeruzun/)
