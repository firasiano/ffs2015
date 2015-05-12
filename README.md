#CODENAME [FED]ERATION
A tool for developers to log and track their own competencies and those of other team members.

##Dependencies Install 

`npm install -g bower`

`npm install`

`bower install`

##Database
MongoDB is required.

Download Mongodb, and add it to the path:

using Terminal:

`cd ~`
`touch .bash_profile`
`vim .bash_profile`	

Add these 2 lines:

export MONGO_PATH=/usr/local/mongodb                        ///usr/local/mongodb is your path to mongodb

export PATH=$PATH:$MONGO_PATH/bin

Save: Shift + ZZ

restart terminal

##Running Server
Dependency: `npm install -g nodemon`

Run with: `npm run dev`

## Client builds
To do a client build to the .build folder run`gulp`
Dist builds should only be done for production ready versions of the client source. To generate a dist build run `gulp dist`

## Environment Variables

For now check ./server/config.js
