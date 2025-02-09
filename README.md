# mts_dz5_scrapy
Файл films1.csv открывался нормально в самой среде PyCharm

запустить код можно по командам:

scrapy crawl films -s FEED_EXPORT_ENCODING=utf-8

scrapy runspider films.py -o films1.csv -s FEED_EXPORT_ENCODING=utf-8
