**Web scraping and indexing with StormCrawler and Elasticsearch**

![](https://github.com/cnf271/stormcrawlertest/blob/master/src/main/resources/article-1-image.png)

[Related Medium Article](https://medium.com/analytics-vidhya/web-scraping-and-indexing-with-stormcrawler-and-elasticsearch-a105cb9c02ca)

This repository contains elasticsearch configurations for StormCrawler project. 

StormCrawler is an open source SDK for building distributed web crawlers based on Apache Storm. Further clarifications on StormCrawler http://stormcrawler.net/

Run the injector using,

``` sh
storm jar target/stormcrawlertest-1.0-SNAPSHOT.jar  org.apache.storm.flux.Flux --local es-injector.flux
```

Run the crawler using,


``` sh
storm jar target/stormcrawlertest-1.0-SNAPSHOT.jar  org.apache.storm.flux.Flux --local es-crawler.flux
```


