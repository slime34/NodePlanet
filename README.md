# NodePlanet

## Setup

Clone the repo and then run `npm install`.

### Migrations

Make sure the database variables are correct in your .env file.

Run the following commands to run database migrations.

```js
npm i -g @adonisjs/cli
```

```js
adonis migration:run
```

### Starting up the Server

Run `node server.js` or `adonis serve`
