Another Python script (first: https://github.com/Swabuu/wiki_mno_scraper) for web scraping the mobile network operator data found on Wikepedia's mobile operator wiki. Includes network owners as well as technology used.
# Wikipedia Mobile Network Operator Scraper

A Python script for web scraping the mobile network operator data found on the below Wikipedia links
 
URLS = ["https://en.wikipedia.org/wiki/Mobile_Network_Codes_in_ITU_region_2xx_(Europe)",
        'https://en.wikipedia.org/wiki/Mobile_Network_Codes_in_ITU_region_3xx_(North_America)',
        'https://en.wikipedia.org/wiki/Mobile_Network_Codes_in_ITU_region_4xx_(Asia)',
        'https://en.wikipedia.org/wiki/Mobile_Network_Codes_in_ITU_region_5xx_(Oceania)',
        'https://en.wikipedia.org/wiki/Mobile_Network_Codes_in_ITU_region_6xx_(Africa)',
        'https://en.wikipedia.org/wiki/Mobile_Network_Codes_in_ITU_region_7xx_(South_America)'       
       ]

This script is using Beautifulsoup & Pandas. Pip install it and you're ready to go.

> pip install beautifulsoup4
> pip install pandas

# TO DO

- [x] Clean the data scraped
- [x] Add more outputs, currently just a .CSV file
- [ ] Create a web GUI (in Flask, a micro web framework written in Python) to easily search for operator info
