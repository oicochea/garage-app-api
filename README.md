# README




ails backend: Serve a JSON API with all CRUD operations available across your models. The Rails API must be deployed online via Heroku.
Must have at least one model with full CRUD
* ...



# Project 4 - Virtual Garage
working link - https://kind-brattain-53f73d.netlify.app/dashboard/

A webApp that is a virtual Garage. Allows you to add vehicles, delete a vehicle and edit a vehicle.
Each vehicle has a - Make, Model,Year, Miles, Image and Services Section. The this can be editable , the user is recommened to keep adding services and the date so maintain a log of the services the car has recieved.

The web uses a user database for the signup/create user with JWT token Authentication To create personalized garages. The backend has a one to many relationship table to allow users to have their own separate garage


## Technolgies used
Rails, JSON, One to Many Relationships, Scaffold (to create back end routes)
Full CRUD - For Car Model
sign up/log in with encrypted passwords and JWT token authorization
We have 1 models Schema and 1 user signup Schema
Heroku


## Approach Taken
 created models in write down sheet to visualise the schemas and seed data.
 Set up databse and migrated models and scaffolded the routes and pathways.
 create schema seed data
 move databse from local host to Heroku server to connect to the front end later.

## Difficulties
 I had began with a overly complicated car model, realized I could alwasy updated at a later date and add complexity.
 The one to many relationship -  I had originally wanted to have 3 models, the services would be by itslef and be part of a User to Many Cars and Cars to Many Services, this would become part of the updated version of the webApp.

 ## Future Improvements

 add another model so that each srvice can have a date , service text box, maybe location and a cost that would be a model inside of the cars models inside the header of service.

   
