# IRAPI search demo [![LinkedTV project](http://www.linkedtv.eu/wordpress/wp-content/themes/edegree/images/slidespot.jpg)](http://www.linkedtv.eu)

## Purpose
IRAPI search is a demo web appliaction based on Jersey framework, which handles searching over crawled media data in SOLR indexes. It provides only one endpoint and returns results in JSON format.

> **Note:** The project is customized for LinkedTV purposes, rather it is assumed that it will be used for inspiration.

## Example usage
QUERY: http://localhost:8080/search/media-server/?q="sonne"&media_type=image

[![example IRAPI result](todo)]

## Installation
### Prerequisites:
* JDK 1.7
* Maven 3.*

1. download/clone the project
2. prepare indexes [[example SOLR index configurations|https://github.com/KIZI/IRAPI/tree/master/solr-example-conf/cores]]
3. in class SolrIndexPool.java are hardcoded indexes, change the urls or change the class according your needs
4. do the standart web application build and deploy (mvn install, deploy .war file on server)

## Wiki
[IRAPI search wiki](https://github.com/KIZI/IRAPI/wiki/IRAPI-search) 

## License

[Apache 2.0](https://github.com/KIZI/IRAPI/wiki/IRAPI-search)
