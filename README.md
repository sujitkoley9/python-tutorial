# python-tutorial


# Scraping Part:
## project Location:
    cs18mds11032/TechnologyNewsScraping
## TechnologyNewsScraperBot
	This is a Scrapy project to scrape Technology related articles from famous site http://www.inshorts.com/en/read/technology

## System  requirements
  1. python 3
  2. Below external packages
	  Scrapy==1.8.0
	  selenium==3.141.0


## Extracted data

This project extracts content, meta_keyword,title,url
The extracted data looks like this sample:

   { 'content': 'data/content_file/content_1265.txt',
	 'doc_id': 1265,
	 'meta_keyword': None,
	 'title': 'RBI to issue periodic scores to assess digital payments industry',
	 'url': 'https://inc42.com/buzz/rbi-introduces-scoring-system-to-map-digital-payments/?utm_campaign=fullarticle&utm_medium=referral&utm_source=inshorts%20'
}


## Spiders

This project contains one spider.
  1. Technology

## Running the spiders

You can run a spider using the below command:

	python -m scrapy crawl Technology

it will store extracted data in excel

---------------------------------------------------------------------------------------------------------------------------

# Language Modeling part:
## project Location:
	cs18mds11032/Language modeling

## System  requirements
  1. python 3
  2. Below external packages
	  nltk==3.4.4
	  seaborn==0.9.0
	  matplotlib==3.1.2

## How to run
    It is jupiter notebook


