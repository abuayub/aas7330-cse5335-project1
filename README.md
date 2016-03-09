# CSE 5335 Spring 2016 Project 1.

- Name: Abu Ayub Ansari Syed
- UTA ID: 1001297330
- email: abuayubansari.syed@mavs.uta.edu
- Affiliation: University of Texas at Arlington
- Website URL: http://cse5335-aas7330.herokuapp.com/

## Questions:

## a).What server framework did you choose and why?
Server framework chosen is Node.js. Reasons:

- Node is a server which can execute JavaScript.
- Sort of a server side browser.
- Node is a open source
- It runs single threaded event based loop, making it non-blocking.

## b). What client framework did you choose and why?
Client framework chosen is JQuery because of the below points:

- JQuery is an opensource framework thus involving no costs.
- JQuery supports the AJAX.
- Simple to code and use as compared to other frameworks because of the availability of the large libraries.
- Jquery also supports Document Object model manipulation through different libraries.

## c). What aspect of the implementation did you find easy, if any, and why?
 Setting up of the Heroku server has been easy. The "Getting Started" tutorial was an easy way to setup the complete server.

## d). What aspect of the implementation did you find hard, if any, and why?
 To visualize in a better manner, CSS features needed more presicion.
Credit to : @kseso at codepen.io. 
D3 understanding takes a little time. Credit to :ragingsquirrel3 at jsfiddle.net

## e). What components OTHER than your client and server framework did you install,if any, and if so, what is their purpose for your solution?
- Google API for marking of locations on a sized maps.
- d3js for the visualizing the data in pir chart.
## f). What Ubuntu commands are required to deploy and run your server?
Prepare the app:
```sh
$ git clone https://github.com/heroku/node-js-getting-started.git
$ cd node-js-getting-started
```
Deploy the app:
```sh
$  heroku create
```
Deploy the code:
```sh
$ git push heroku master
```
View logs:
```sh
$ heroku logs --tail
```
Declare app dependencies:
```sh
$ npm install

Run the app locally:
```sh
$ heroku local web
```
Add the modified files to the local git repository:
```sh
$ git add .
$ git commit -m "Demo"
$  git push heroku master
```
Add the database:
```sh
$ heroku addons:create heroku-postgresql:hobby-dev
```
Postgresql:
```sh
apt-get install postgresql
```
Use database:
```sh
$ heroku pg:psql
```

