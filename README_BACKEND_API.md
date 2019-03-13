# Backend API Documentation

## Root

| Endpoint | Method | Description | isAuthenticated | isAdmin |
| -------- | ------ | ----------- | --------------- | ------- |
| `/`      | GET    | Hello       |                 |         |

## Users

| Endpoint          | Method | Description           | isAuthenticated | isAdmin | hasAPIKey |
| ----------------- | ------ | --------------------- | --------------- | ------- | --------- |
| `/users/seed`     | POST   | Seed initial users    |                 |         | YES       |
| `/users/register` | POST   | Register new user     |                 |         |           |
| `/users/login`    | POST   | Login to user         |                 |         |           |
| `/users/profile`  | GET    | Get user profile      | YES             |         |           |
| `/users/:id`      | GET    | Get one user by id    |                 |         |           |
| `/users`          | GET    | Get all users         |                 |         |           |
| `/users`          | DELETE | Delete all users      |                 | YES     |           |
| `/users/:id`      | DELETE | Delete one user by id | YES             |         |           |
| `/users/:id`      | PUT    | Update one user by id |                 |         |           |

User Model:

```json
{
  "_id": ObjectID(),
  "id": 1,
  "name": "Joen Doe",
  "email": "joendoe@example.com",
  "salt": "zyxwvutsrqp",
  "password": "zyxwvutsrqpabcdefghijklmnopqrstuvwxyz",
  "__v": 0
}
```

## Ideas

| Endpoint                  | Method | Description           | isAuthenticated | isAdmin | hasAPIKey |
| ------------------------- | ------ | --------------------- | --------------- | ------- | --------- |
| `/ideas/seed`             | POST   | Seed initial ideas    |                 |         | YES       |
| `/ideas`                  | GET    | Get all ideas         |                 |         |           |
| `/ideas/search?q=keyword` | GET    | Search for ideas      |                 |         |           |
| `/ideas`                  | POST   | Create new idea       | YES             |         |           |
| `/ideas`                  | DELETE | Delete all ideas      |                 | YES     |           |
| `/ideas/:id`              | DELETE | Delete one idea by id | YES             |         |           |
| `/ideas/:id`              | PUT    | Update one idea by id | YES             |         |           |

Idea Model:

```json
{
  "_id": ObjectID(),
  "id": 1,
  "title": "Super Strong Backpack",
  "description": "A backpack that is super strong, accompanied with an app to track your belongings inside. Marvelous!",
  "author": "Alpha User",
  "date": ISODate("2019-01-01T12:30:45.000Z"),
  "location": "Jakarta, Indonesia",
  "slug": "super-strong-backpack",
  "images": [
    "/assets/images/picture.jpg",
    "/assets/images/picture.jpg",
    "/assets/images/picture.jpg"
  ],
  "details": "<p>Details here. <b>Another thing</b>.</p>"
}
```
