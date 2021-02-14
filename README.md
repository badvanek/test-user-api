
## Run project
1. Clone repository
2. Run `docker-compose up -d --build` in project folder
3. Apply migration `docker-compose run php bin/console doctrine:migrations:migrate --no-interaction`
4. Open http://localhost:8081/api in browser
