graphql and relay were built to solve a very specific set of problems

RESTful routing

a set of conventions used in web development for manipulating data hosted on a server

common uniform rules for URL and HTTP request methods used to access a collection of data on a server

POST create new one
GET fetch all
GET fetch one
PUT update one
DELETE delete one

REST conventions break down when you get into deeply nested - heavily RELATED - data

GraphQL was created to solve inconsistencies with RESTful routing and over-serving data

RESTful issues
1. deciding on URL schema gets tough with heavily nested - related - data
2. when working with heavily nested data we may end up making too many HTTP requests
3. overfetching data

a graph is a data structure that contains nodes and relationships between nodes: edges