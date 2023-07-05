# loldle-server

Play loldle without the limit of 1 champ/day.

### Run the server

```
npm i
node bin/www
```

### Map the API

- Use Proxyman or Charles's Map remote to map https://cache.loldle.net/cache.json to http://localhost:3000/cache.json
  <img width="846" alt="Screenshot 2023-07-05 at 5 59 20 PM" src="https://github.com/catrius/loldle-server/assets/19802230/aefdbb17-2c46-4975-b18c-aa23006fb685">

### Refresh the server to get new champ

- Simply visit: http://localhost:3000/cache.json/refresh

