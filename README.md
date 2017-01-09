# go-json

Improve the way of creating JSON data structures in Go. I use it heavily when writing queries for ElasticSearch.

```
import . "github.com/pakohan/go-json"

…

	o := o{
		"nested": o{
			"key1":         "test",
			"key2":         o{"anotherKey": "value"},
			"uselessArray": A{"A", "B", "C"},
		},
	}
```
