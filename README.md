# Basic-Express-Server res.send is when you just want to send something small like some text or a little bit of html straight from your code res.sendFile is when you want to send a real file like your index.html page or a picture from your computer

the path thing is there so the server always knows exactly where your file is if you just say public/index.html it might not work if you run the server from a different place path.join makes sure it works no matter what folder you start it in

if you want to add a menu page you just make a menu.html file in the public folder put whatever you want in it then in server.js make another route like app.get('/menu', ...) that sends that file or you can just go to menu.html in your browser if you have express.static set up
