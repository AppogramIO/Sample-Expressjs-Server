# Appogram Sample With Express js

this repository contain a very simple server that written in JavaScript and [Express JS](https://expressjs.com) 


# Installation
be sure that you have `Node` and `NPM` on you machine.
then download the repository and then run these commands on directory that you downloaded.

    npm install
    npm start
  by default server run on `localhost:80` and ready to use.then you can use the address of server in [Appogram Studio](https://studio.appogram.io)

# Use in Appogram Studio 
After you run the server you need to add the url of server in  [Appogram Studio](https://studio.appogram.io) but first of all be sure that you download the last version of [Appo Template](https://github.com/AppogramIO/Sample-Appogram-Appo) and then import it to versions. after that go to `Designer` and on top of page select `Variables`.Click on `Variables` button after a modal opend edit the `server` variable and replace it with this server url.

**Important Note 1**
the server run on `localhost` and port `80` but as you know if you use this url in you app it cause a problem in android emulator or other devices. so instead of using `localhost`  use your **ip address** for example if your app address is `192.168.1.10` instead of using `localhost:80` use `192.168.1.10:80` for `server` variable in Appogram Studio.

**Important Note 2**
this is very important that after you import the version in Appogram Studio then save it. for this go to `Designer` and then click on `Save and Update` button.

# Configs

for changing ip and port or change secret key of jwt you should change `config.js` and then restart the server.
