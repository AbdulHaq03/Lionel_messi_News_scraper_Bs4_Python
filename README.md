# **Libraries you need**:
+ import csv
+ import requests
+ from urllib.request import Request, urlopen
+ from bs4 import BeautifulSoup as bs
+ from time import sleep
+ from bs4 import SoupStrainer
+ import requests
+ import lxml
+ import random
+ from datetime import datetime
+ from itertools import cycle
+ import time

# **For running lxml you need to install it**
pip install lxml

# **Install beautifulSoup as well as requests**
+ pip install requests
+ pip install beautifulsoup4

# *For getting the date from Ap news I got only the format for the date so I extracted that as well all the steps are given in my ipynb*

# **I have provided the Ips I got from a website named webshare.io**
import requests
requests.get(
    "https://ipv4.webshare.io/",
    proxies={
        "http": "http://tctsdtrb-rotate:ncht9e985h7x@p.webshare.io:80/",
        "https": "http://tctsdtrb-rotate:ncht9e985h7x@p.webshare.io:80/"
    }
).text

# username is tctsdtrb and password is ncht9e985h7x for getting webshare ips

# Columns scraped:
## +*URL (Link of news)*
## +*Headline Of news*
## +*Proxy Ip (proxy which I used)*
## +*Publication Date*
## +*Content (description of news)*
## +*Image URL*

# This code will give you the ips that I have I used these to get the list ready
# I have already provided the ip list so no need to run this 
# Run Every cell one by one 
# Thank you :)
