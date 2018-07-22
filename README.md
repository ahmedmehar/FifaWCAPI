# FifaWCAPI
This is APi made in Laravel 5.6 with Laravel passport authentication.
#created by Ahmed Raza

There are different Module in this Api:

First Number: 

Admin Module
Team Add
Player Add
Matches Add
Group Matches (Add by Seeder) 
Score Add
 
 -------------------------------------------------------------------------------
 
 Step1:
 1.You have to to create the Database according to the name .env file
 2. After you have to migrate the database: php artisan migrate
 3.Then you have to install the Command: php artisan passport:install
 4. In the last, you have to run this command: php artisan serve and Hit http://localhost:8000/ in the browser
 
 Test-driven Development:
 Step1: You can Run all the Test in the cmd by using this command: vendor/bin/phpunit
       -> I wrote different Test Cases: Team, Player, Group Matches, Scoring Test.

 Step3:
 1. You have to register the user either using postman or using frontend page.
 2. You can login the Api Via postman and get the user token.
 3. Also you can check the User detail to put the Token.
 
 Step4: 
 1. You can add the Team after Login Via postman and will view in the frontend of Api.
 2. Without Login you can not Add the Teams.
 
 Step5:
 1.You can add the Player after adding the team Via postman.
 
 Step6.
 1. You have to add the Group Matches Via Seeder: php artisan db:seed

 Step7. you have to see the teams who are qualify the Round 2...with 16 Teams
 Step8. You can update the Score of particular Teams to decide who's winning.
 
 
 
 Extra Features by Myself: 
 1. Add a notification once someone had registered
 2. Add the password strength feature