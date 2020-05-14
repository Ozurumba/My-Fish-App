# My-Fish-App

Stacks
* React
* Redux
* CORS
* PostgreSQL

For this application i built an API that performs full CRUD (create, read, update, delete) on a single resource - fishes. Each row in our fishes table will have a name and type. Our API will consist of the following four routes:
GET /fishes - returns an array of fish objects
POST /fishes - creates a new fish object and returns the object
PATCH /fishes/:id - updates an existing fish object
DELETE /fishes/:id - removes an existing fish object
