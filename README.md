# Puddle

<p align="center">
  <img src="./client/src/image/Puddle.png"/>
</p>

Social Site that allows users to comment and post puzzles and riddles. This is the new updated version of Priddle. Completely scrapped the backend of the previous project Priddle. Rebuilt and restuctured the backend to be fully functional. Previously, it relied on seeds to be migrated in order to create the different categories. Now each category has its own table, and added comments table to allow users to comment on post

### A live version of Puddle is deployed with Render and running here:

[Live Version](https://puddle.onrender.com/)



## New Features


#### Posting
Fully up and functioning. User can post riddles, or can post a URL for a image puzzle.

### Comments
User is now able to comment on the post and guess answers.





## Get started
After cloning the repo into you system you will need to: 
- make sure your system is running a ruby version 

After cloning the repo, run the following steps in the project directory to get started:

```
bundle install
```
Install Ruby gem packages associated with the project.

 ```
 rails db:migrate db:seed
 ```
Migrates all tables and associations that are needed. Also make sure to seed the backend so you have some data to work with.

 ```
 rails s
 ```
Start your Rails server. For a closer look at just the backend, you can open http://localhost:3000

Finally for your front end run:

```
npm start --prefix client
```
Runs the app in the development mode. 
