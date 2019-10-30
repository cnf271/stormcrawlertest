**Web scraping and indexing with StormCrawler and Elasticsearch**

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


