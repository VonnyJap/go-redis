# go-redis
Sample app using redis with Go

### Steps
- Setup redis
```
docker pull redis
docker run --name redis-test-instance -p 6379:6379 -d redis
```
- Run the script
```
go run main.go
```
- Expect this result
```
Go Redis Tutorial
PONG <nil>
{"name":"Elliot","age":25}
```
