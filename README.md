moodle Docker setup for ESM (Enterprise Solution Development) for Azure VM
credits to creator [seunayolu](https://github.com/seunayolu/docker-project)

Steps (on windows):
1. create a .env file containing the variables below:
```
MYSQL_ROOT_PASSWORD=YOUR_OWN_ROOT_PASSWORD_FOR_DATABASE
MYSQL_DATABASE=DATABASE_NAME_FOR_MOODLE
MYSQL_USER=MOODLE_USERNAME
MYSQL_PASSWORD=MOODLE_USER_PASSWORD
```
2. check all env variables are loaded/exists
```bash
docker compose config
```
3. build
```bash
docker compose up --build -d
```
