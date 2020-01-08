- C5282	Set basic request data in markdown and make request
- T43463 Set query parameters and make a request
- T43464 Set request body and make a request

```json http
{
	"baseUrl": "https://httpbin.org",
	"method": "get",
	"url": "/uuid",
	"headers": {
		"testHeader": "testHeaderValue"
	},
	"query": {
		"testQueryParam": [
			"testQueryValue"
		]
	},
	"body": {
		"name": "body",
		"value": 5,
		"isValid": true
	}
}
```

- C5283	Set request headers in markdown and make request

```json http
{
	"baseUrl": "https://httpbin.org",
	"method": "get",
	"url": "/headers",
	"headers": {
		"yudothis": "leo"
	}
}
```

- C5293 Update path in markdown and inspect rendered request maker

```json http 
{
	"baseUrl": "https://httpbin.org",
	"method": "get",
	"url": "/json"
}
```



