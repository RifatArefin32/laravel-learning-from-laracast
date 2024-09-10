# Create and setup a laravel project

## Create laravel project
```bash	
composer create-project --prefer-dist laravel/laravel project-name
```
## Open the project directory and setup the project
- Go to the project directory 
- Configure database at `.env` file	
```bash
DB_CONNECTION=mysql
DB_HOST=127.0.0.1 # your host ip
DB_PORT=3306 # mysql port
DB_DATABASE=database-name
DB_USERNAME=datanase-username # e.g. root
DB_PASSWORD=database-password 
```
- Run laravel migration 
```bash
php artisan migrate
```

## Add the project at github repository:
- Create a github repository (without `README.md` because during installation laravel has a default `README.md`)
- Add the project to the github repo:
```bash
git init
git branch -M main
git remote add origin <repo-link>
git add .
git commit -m 'initial commit'
git push origin main  
```