# Elasticsearch ParisAccidentholgy
### Paris Accidenthology Analysis

We have paris accidentholgy data set in the year 2012  with CSV format ( paris_accidentology.csv ). We will convert this csv data set to json data with logstash as the repo Elasticsearch accepts only json format input. This process script available in the file "csv_to_es.conf". 

This data set has all type of vehicles involved in the accidents with repect to season and location.

This logstash file input is csv file and output is ElasticSearch means convert csv file to json format then push this data to elasticsearch with document type "paris_accident". 

We have a template "paris_template.json" for this document "paris_accident" to define datatype of columns like Converting "location" to "geo_point" data type.

#### Dashboard view 1
 ![dashboard_1](/dashboard_1.PNG)

 #### Dashboard view 2
 ![dashboard_2](/dashboard_2.PNG)

 #### Dashboard view 3
 ![dashboard_3](/dashboard_3.PNG)

 #### Dashboard view 4
 ![dashboard_4](/dashboard_4.PNG)

 #### Dashboard view 5
 ![dashboard_5](/dashboard_5.PNG)


### Useful Links

[Elasticsearch MyBook](https://github.com/nrkreddy94/elasticsearch-mybook)

[ELK MyCollection](https://github.com/nrkreddy94/elasticsearch-repo)

[RPA UIPath ElasticSearch](https://github.com/nrkreddy94/RPA_UIPath_ElasticSearch)

[ELK Apache Logs](https://github.com/nrkreddy94/elasticsearch-apache-logs)

[ELK Json Logs](https://github.com/nrkreddy94/elasticsearch-logstash-jsonlog)