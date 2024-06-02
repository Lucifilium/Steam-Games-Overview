# Steam Games Overview
 This project is to explore the recent new releases of such games to identify what affects the popularity of them.

# Requirements
!pip install selenium
!pip install word

#Import libraries and modules

import pandas as pd
import requests
from bs4 import BeautifulSoup
import numpy as np
import matplotlib.pyplot as plt
%matplotlib inline
from selenium import webdriver
from selenium.webdriver.common.by import By
from selenium.webdriver.support.select import Select
import time
import pickle
import nltk
import seaborn as sns
from nltk.tokenize import RegexpTokenizer
import re
from string import punctuation
from nltk.corpus import stopwords
from nltk import FreqDist
from wordcloud import WordCloud

nltk.download('stopwords')
nltk.download('punkt')
