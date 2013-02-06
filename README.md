#AutoDJ Turntable bot

A customizable Turntable.fm bot based on [Sparkle-Turntable-Bot](https://github.com/sharedferret/Sparkle-Turntable-Bot) written in node.js utilizing [ttapi](https://github.com/alaingilbert/Turntable-API).

## After Cloning
run these commands to install all dependencies

npm install ttapi
npm install request
npm install xml2js
npm install mysql 

And don't forget to set up your config.json to use your turntable creds and database


## Features

Every new song that is played the bot hits the LastFm api to find similar songs and searches for them in Turntable to add to its own queue.
Thus after one song the bot will continuously play
