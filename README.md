# fiit-pdt-project
Project for subject PDT on FIIT, STU - Geo queries with Bratislava

## Detailed description

This project serves for example manipulation upon geo datasets of Bratislava city and consists of client and server side communication. Client dispose with .html file to control UI through browser where client can see his map, options and client input. Server side communicate with client and PSQL database server.

## Used technologies

In this project I used following technologies:
* Node.js
* JavaScript
* HTML
* CSS
* PSQL
* Socket.io
* Mapbox

## Client side

My client side consists of files for browser common with client-server communication. Most of work here involve processing user input and response from my server to show it on map.

Example of UI looks liek follows:

![My UI picture](https://github.com/Marek-Bernad/fiit-pdt-project/blob/master/images/ui.png)

## Server side

My server side is based on Node.js server with socket.io communication between user and this server. In this project server run client UI on localhost: http://localhost:8080/. 

![My server-side picture](https://github.com/Marek-Bernad/fiit-pdt-project/blob/master/images/server.png)

## Scenarios / what can it do?

Project allows user to use following scenarios:
* Show street A (map layer1)(Input: text field)
* Show street B (map layer2)(Input: text field)
* Show PgRouting betwwen A & B (map layer 3) (Input: 2x text field)
* Show PgRouting from A to C but needs to go through B (map layer 4)(input: 3x text field)
* Show polygon/polygons with edge points of specific objects like 'Billa', 'Kaufland' ... (map layer 5,6)(input: 1 text field)
* Show heatmap of traffic in Bratislava with touches to sth (map layer 7)(input: 1 text field)

## Datasets details

* openStreetMap of Bratislava (cut area)
* traffic in Bratislava

## How to run this project

1. Run your psql local server
2. Import databases
3. Update DB access in nodeServer.js file
4. Navigate to fodler with file "nodeServer.js"
5. Run in cmd/terminal "node nodeServer.js" (if you miss modules, install it in order of error code you obtain)
6. Navigate to http://localhost:8080/
 

## Versions / settings

description


