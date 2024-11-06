# scrape-Google
Googlesearch using Python

googlesearch is a Python library for searching Google

Crete virrtual enviroment then 
python3 -m venv venv  —— setup virtual environment
source venv/bin/activate —— activate environment 

To install, run the following command: python3 -m pip install googlesearch-python

To get results for a search term, simply use the search function in googlesearch

googlesearch supports a few additional options. 

By default, googlesearch returns 10 results. This can be changed. To get a 100 results on Google for example.
If requesting more than 100 results, googlesearch will send multiple requests to go through the pages. To increase the time between these requests, use sleep_interval:
You can also specify the region (Country Codes) for your search results
You can change the language google searches
To extract more information, such as the description or the result URL, use an advanced search: