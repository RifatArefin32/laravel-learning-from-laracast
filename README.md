# Create and setup a laravel project

## Create laravel project
```bash	
    composer create-project --prefer-dist laravel/laravel laravel-learning-from-laracast
```
## Open the project directory and setup the project
- Go to the project directory 
- Configure database at `.env` file	
```bash
	DB_CONNECTION=mysql
	DB_HOST=127.0.0.1
	DB_PORT=3306
	DB_DATABASE=laravel_learnign_from_laracase_db
	DB_USERNAME=root
	DB_PASSWORD=password
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