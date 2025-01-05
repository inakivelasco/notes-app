# notes-app

## Some usefull commands
- **Run app →** `flask --app .\app\app.py run`
- **Test database →** `docker run -p 3306:3306 --name db-mysql -e MYSQL_ROOT_PASSWORD=root -e MYSQL_DATABASE=notes_db mysql:lts`
- **Generate requirements.txt →** `pip freeze > app/requirements.txt`
- **Build and run full app →** `docker compose up --build`