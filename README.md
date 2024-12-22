# scrapy-project
A web scraper project using Scrapy and MongoDB

## Installation and Setup

1. Create a Python virtual environment

```sh
$ python -m venv ./venv
$ source venv/bin/activate
(venv) $
```

2. Install the requirements

```sh
(venv) $ pip install -r requirements.txt
```
## Run the Scraper

Navigate into the `books/` project directory.

Then you can start crawling the site:

```sh
(venv) $ scrapy crawl book
```

If set up correctly, this will populate your MongoDB collection with the book information scraped from the example site.