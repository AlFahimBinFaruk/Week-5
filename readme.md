### How to run it
```shell
docker compose up --build
```
then query the following endpoints to see if everyting is working as expected.


### Graph Query
1. Register History
```shell
http://localhost/graph-service/query/register-history/111
```
2. Update History
```shell
http://localhost/graph-service/query/update-history/22
```
3. Delete History
```shell
http://localhost/graph-service/query/delete-history/11
```

### Auth Backend query
```shell
http://localhost/auth-backend/api
```
