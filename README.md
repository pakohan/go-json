# go-json

Improve the way of creating JSON data structures in Go. I use it heavily when writing queries for ElasticSearch.

```
  o := o{
	  "nested": o{
      "path":   "scoring",
      "filter": o{"bool": singleScoreFilter},
    },
  }
```
