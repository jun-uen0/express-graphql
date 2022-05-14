## Running an Express GraphQL Server
Folloing official tutorial: https://graphql.org/graphql-js/running-an-express-graphql-server/

## Useage
```shell
npm install express express-graphql graphql --save
```
```shell
node server.js
```
Then access to http://localhost:4000/graphql
Run the query
```shell
{
  hello
}
```
Expected output
```shell
{
  "data": {
    "hello": "Hello world!"
  }
}
```

## # Using Docker
```shell
docker-compose run --rm app sh -c "npm install express express-graphql graphql --save"
```
```shell
docker-compose up
```
Then access to http://localhost:4000/graphql