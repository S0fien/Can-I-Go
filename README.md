# CAN I GO? 🤔

You're team is mandated by the governement to create a new app used as a COVID context utility called "Can I go?".

You're in charge of creating a webservice of this app.

This webservice is a CRUD API mainly used to know if your authorized to be in some public spaces based on your current health situation.

This webservice must use mongoDB as database.

At start, data in JSON must be added to BDD and CURL request to the API should be possible.

For a user to be able to visit a public space, that user must have a valid pass and the required age.

## Instructions :

> Your project (API + MONGODB) must be dockerize and runned by a
> docker-compose

- CRUD operations for all entities
- One endpoint to check if a given user can access a given public space
- One endpoint to check which public spaces can access a given user
- Security and token (to define)
- Implements status codes (at least 200, 201, 400, 401, 403, 404)

**BONUS:**
Add units tests with Jest and Enzyme

**TODO:**

- [ ] Create base schemas
- [ ] Create JSON with data to add in DB
- [ ] package.json ?
- [ ] Define security and token
