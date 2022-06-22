# Car Mechanical Services
Resolve the need to register automotive services

# Project description
We will create a project where users can register automotive services. This project allows registering the data of the cars and their owners, as well as all the services that are carried out in them. It will be possible to obtain the history of the executed service


# Stack
- Motor BD: 10.6.8-MariaDB
- Laravel Framework 9.16.0
- PHP 8.1.6 (cli) (built: Jun  1 2022 21:41:00) (NTS)
	Copyright (c) The PHP Group
	Zend Engine v4.1.6, Copyright (c) Zend Technologies
    	with Zend OPcache v8.1.6, Copyright (c), by Zend Technologies
- Angular CLI: 14.0.1
- Node: 16.14.2
- Package Manager: npm 8.12.1 
- OS: win32 x64	

# Setting up
- curl -s https://laravel.build/app | bash
- docker-compose up --build -d 
- Install Angular  - npm install -g @angular/cli
- Create frontend app  - ng new fontend
- Fake car data  - composer require pelmered/fake-car
- Install CRUD angular  - npm i angular-crud

# Settings Evironment
- .env
	DB_CONNECTION=mysql
	DB_HOST=mysql
	DB_PORT=3306
	DB_DATABASE=larevel_app_db
	DB_USERNAME=larevel_app
	DB_PASSWORD=

# Backend development
- docker exec -ti carservbackend bash
- php artisan migrate 
- php artisan db:seed
- Backend - API 
	- Create routes 
	- Test routes  
	- Security  
	- Error handler
	
# Model
- car_service_name: Service listings
- cars: Cars
- owner: Owners
- car_owner: Relationship of cars with owners
- car_service: Car Service information
- car_service_details: Services details
