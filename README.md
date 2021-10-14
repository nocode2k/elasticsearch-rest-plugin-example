# elasticsearch-plugin-example
## Examples for developing ❝Elasticsearch plugin❞

## Environment

This example uses:
* macOS
* Open JDK 11
* Elasticsearch 7.15.1

## Build

* Maven Install
https://maven.apache.org/install.html

* Build example this:
```
$ mvn clean install
```

## Install
```
./bin/elasticsearch-plugin install file:///elasticsearch/elasticsearch-example-plugin-7.15.1.zip
```

## Run
```
./bin/elasticsearch
```

## Browser
```
http://localhost:9200/_nocode
{
"description": "This is a example response: Fri Oct 15 07:58:00 KST 2021"
}
```