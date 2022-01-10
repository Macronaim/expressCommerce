# Express Commerce


## View Locally

1. Install dependencies

```
npm install
```

2. Change the filename of `example-nodemon.json` to `nodemon.json`. Use the example as a guideline to replace keys with appropriate API keys, etc., from MongoDB, SendGrid, and Stripe. These can each be acquired using a free account.

3. Start Nodemon server at http://localhost:3000 (the `start:dev` script must be used since `nodemon.json` is used to store environment variables, and the other scripts do not use Nodemon)

```
npm run start:dev
```
