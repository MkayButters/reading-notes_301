 ## Heroku

 - Node.js is an open source, cross-platform runtime environment, which allows you to build server-side and networking applications. It's written in JavaScript and can be run within the Node.js runtime on any platform.

 - Pretty simple proccess
    1. Create a JS file
    2. Add into it this 
    `var http = require("http");

       http.createServer(function(request, response) {
        response.writeHead(200, {"Content-Type": "text/plain"});
        response.write("It's alive!");
        response.end();
       }).listen(3000):`

    3. Run command `node` and the JS files name in Ubuntu
    4.  
    
 - Using __Heroku__ allows you to make it worldwide (ie. _www._)

 - Attaching your github repository to the Heroku allows you to create your own website from your local machine using GitHub as the "middle holder of data" and passes it over to Heroku to deploy your website.
 
 
 
 
 [<===BACK](README.MD)