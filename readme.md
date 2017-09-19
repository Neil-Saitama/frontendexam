# myexam

frontend examination

### Setup

- make sure [node.js](http://nodejs.org) and [roots](http://roots.cx) are installed
- clone this repo down and `cd` into the folder
- run `npm install`
- run `roots watch`
- ???
- get money

### Deploying

- If you just want to compile the production build, run `roots compile -e production` and it will build to public.
- To deploy your site with a single command, run `roots deploy -to XXX` with `XXX` being whichever [ship](https://github.com/carrot/ship#usage) deployer you want to use.


#--------------------------------------------------------#

### Start a web server from a directory containing static website files :

Open a command prompt / command line window and enter the following:

- npm install -g http-server

#### Change to the directory containing your static web files (e.g. html, javascript, css etc) in the command line window, e.g:

cd \projects\myexam
Start the server with this command:

- http-server

### You should see something like the following:
 
C:\projects\angular-registration-login-example>http-server
Starting up http-server, serving ./
Available on:
  http://192.168.0.5:8080
  http://127.0.0.1:8080
Hit CTRL-C to stop the server

### Browse to your local website with a browser

Open your browser and go to the address http://localhost:8080 and you should see your local website. 