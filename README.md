# Express-Quests

### Initialisation

1. Clone the repo
2. `cd Express-Quests-05`
3. `npm i`
4. `cp .env.sample .env`
5. `npm run dev`

---

### To validate the quest

_In Postman_

1. Do a GET request `localhost:5005/api/users/` -> should return all the users
2. Do a GET request `localhost:5005/api/users?city=New York` -> should return all users from New York
3. Do a GET request `localhost:5005/api/users?language=English` -> should return all users who's speaking English
4. Do a GET request `localhost:5005/api/users?city=New York&language=Italian` -> should return all users who's speaking Italian in New York
