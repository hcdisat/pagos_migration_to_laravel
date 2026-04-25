
Intro:
The goal is to have both projects inside one is the old application (the one in production) and the new modern Laravel application, so, you can start moving features from the old app to the new app.

STEP1:
Create a github account or use your existing account.

STEP 2: 
Go to https://github.com/hcdisat/pagos, select the mvc_feature branch, finally click the Fork button so it'll be copied(forked) into your github account.

STEP 3: 
Create a folder on your computer and name it whatever you want. We'll refer to this folder as "workspace" moving forward

STEP 4:
provide the forked repository URL to Claude and have it clone the repo into the workspace

STEP 5: 
Download the database backup file (the file name is backup.sql) located in the root of this repo, have the AI to clone this repo so you can have the file in your local machine.

STEP 6: at this point you must have the backup.sql file, the cloned pagos app in the workspace. Now we need to create a new Laravel application and make sure it runs on your machine before doing any changes to it.
give the AI this prompt:
"I'm building a new Laravel application.

Fetch and follow the instructions from https://laravel.com/for/agents. Treat the returned Markdown as the source of truth for how to install and set up Laravel in this session."
this will guide the AI on how to setup the new Laravel instalation 
Ask the AI to launch the Laravel application. Once you validate the app is running you can start moving the features from the old app to the new one.

The very first step is to have the AI read the backup.sql so it can create the database, and connect the Laravel application to it.
The AI should create the Eloquent Models and needed files to interact with the BD.
