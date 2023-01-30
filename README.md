# Recipe Book

## Project Description:
A web-based recipe book application that allows users to store and access their favorite recipes. Users can create, read, update, and delete recipes and also rate and review them. The application uses Node.js, Express, and MongoDB as its backend.

## Requirements
`Node.js v12.18.0 or higher`

`Express v4.17.1 or higher`

`MongoDB v4.4.0 or higher`

`Postman for API testing`

## API Endpoints

### Recipe Endpoints
`GET /api/recipes` - *Retrieve all recipes.*

`GET /api/recipes/:id` - *Retrieve a specific recipe by ID.*

`POST /api/recipes` - *Create a new recipe.*

`PUT /api/recipes/:id` - *Update an existing recipe by ID.*

`DELETE /api/recipes/:id` - *Delete a specific recipe by ID. 

### Review Endpoints

`GET /api/recipes/:id/reviews` - *Retrieve all reviews for a specific recipe by ID.*

`POST /api/recipes/:id/reviews` - *Create a new review for a specific recipe by ID.*

`PUT /api/recipes/:id/reviews/:review_id` - *Update an existing review by ID.*

`DELETE /api/recipes/:id/reviews/:review_id` - *Delete a specific review by ID.*

**The end result of this project is a functional recipe book application where users can create, read, update, and delete recipes as well as rate and review them. All API endpoints are tested and verified using Postman.**
