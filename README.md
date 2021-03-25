# Istruzioni

## Autori
* Gabriele Carrara: 814720;
* Alberto Filosa: 815589;
* Simone Tufano: 816984.

## Librerie Utilizzate:

### Python
Ambiente Python 3.8 per scraping con `snscrape`.

```py
import os
from datetime import datetime, timedelta
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
import string
import re
import seaborn as sns
import pickle

#-- Nltk Packages
import nltk
from nltk.tokenize import word_tokenize
from nltk.tokenize import TweetTokenizer
from nltk.corpus import stopwords
from nltk import wordpunct_tokenize

from sklearn.feature_extraction.text import CountVectorizer
from sklearn.model_selection import train_test_split
from sklearn.metrics import classification_report, confusion_matrix   #-- Model Summary
from sklearn.svm import SVC                                           #-- SVM

from collections import Counter
import itertools

nltk.download('punkt')
nltk.download('stopwords')
```

### R

```r
library("tidyverse")
library("rvest")
library("reticulate")
library("syuzhet")
library("twitteR")
library("rtweet")
library("ROAuth")
library("igraph")
```

## File
* Script: SMA_progetto.ipynb;
* Report: SMA_report.html;
* Slides: SMA_slide.pptx;
* Lexicon [Sentyx](https://valeriobasile.github.io/twita/sentix.html);
* Gephi:
    + Community_f1.gephi;
    + Betweenness_f1.gephi.
* Visualizzazioni [Tableau](https://public.tableau.com/profile/albi9702#!/vizhome/SocialMediaAnalysis_16084630027570/Ferrari).