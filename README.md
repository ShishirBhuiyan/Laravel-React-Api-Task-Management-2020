# Laravel-React-Api-Task-Management-2020
<br><br><br>




### To start this project 
+ follow `package.json` file and install require packages. At first run `npm install`




+ install laravel `composer create-project laravel/laravel blog`
+ install ui package to manage third party package access `composer require laravel/ui`
+ install bootstrap in laravel `php artisan ui bootstrap`
+ install react in laravel `php artisan ui react`
+ run `npm install` for create node_modules folder. where all npm package stored.
+ run `npm run dev` 
+ for dunamic react routing install `npm i react-router-dom`
+ install Laravel difault authentication `php artisan ui:auth`





+ run `npm run dev` this command compile react full code then gives us result.if you use `npm run dev` every single changes you should again `run npm run dev`, otherwise change of react code is not effect in our project.

+ `npm run watch` only watching any of changes in our react code automatically




+ php artisan make:model Project -m
+ create controller ProjectController,TaskController



>### use tinker to insert data
+ php artisan tinker
+ $user = new User()
+ $user->name = "Shishir"
+ $user->email = "user@gmail.com"
+ $user->password = Hash::make("12345678")
+ $user->save()



