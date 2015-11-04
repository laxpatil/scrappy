# scrappy_tests

This repository contains simple scraping using 'scrapy'.

The repository sturucture is as follows:

tutorial/
    scrapy.cfg            # deploy configuration file

    tutorial/             # project's Python module, you'll import your code from here
        __init__.py

        items.py          # project items file

        pipelines.py      # project pipelines file

        settings.py       # project settings file

        spiders/          # a directory where you'll later put your spiders
            __init__.py
            ...






To run the spider:

       scrapy crawl dmoz
