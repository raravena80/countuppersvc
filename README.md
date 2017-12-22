# countuppersvc
Sample count and uppercase service using go-kit

## Run

```
go run main.go
```

## Use

```
$ curl -XPOST http://localhost:8080/count -d '{"s": "my happy string"}'
{"v":15}
curl -XPOST http://localhost:8080/uppercase -d '{"s": "my happy string"}'
{"v":"MY HAPPY STRING"}
```
