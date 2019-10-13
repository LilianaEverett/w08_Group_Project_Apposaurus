# Apposaurus

## Brief:

Educational App
The BBC are looking to improve their online offering of educational content by developing some interactive browser applications that display information in a fun and interesting way. Your task is to make an a Minimum Viable Product or prototype to put forward to them - this may only be for a small set of information, and may only showcase some of the features to be included in the final app.

## MVP
A user should be able to:

- view some educational content on a particular topic
- be able to interact with the page to move through different sections of content

## Example Extensions:

- Use an API to bring in content or a database to store information.
- Use charts or maps to display your information to the page.

## How to run Appasaurus:

Download or clone this repository

In your terminal window, go inside the created respository folder, then go inside the `client` folder.

`cd client`

Run the following command to install the dependencies:

`npm install`

Run the following command to start front end server:

`npm run serve` 

Open another termianl tab:

Go inside the server folder (if the new tab opens on `client` you will need to `cd ..` to go back to the main project folder)

`cd server`

Run the following command to install the dependencies:

`npm install`

Run the following command to start your MongoDB server:

`mongod`

Open another terminal tab:

Run the following command to start your localhost server:

`npm run server:dev`  (let it run)

in the browser open `http://localhost:8080/` to access the app.
