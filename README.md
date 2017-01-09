# go-json

Improve the way of creating JSON data structures in Go. I use it heavily when writing queries for ElasticSearch.

```
import . "github.com/pakohan/go-json"

…

	o := O{
		"nested": O{
			"key1":         "test",
			"key2":         O{"anotherKey": "value"},
			"uselessArray": A{"A", "B", "C"},
		},
	}
```
