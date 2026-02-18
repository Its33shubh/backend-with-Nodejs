# Backend With Node.js

initialize project  
npm init -y  

install express  
npm i express  

install nodemon  
npm i nodemon  

setting up parser for form  
app.use(express.urlencoded({ extended:true }));  
app.use(express.json());  

setting up ejs for ejs pages  
install ejs  
npm i ejs  

setup ejs view engine  
app.set('view engine', 'ejs');  

make one more folder  
views  

create file inside views  
index.ejs  

if we want to display calculation like this  
<%= 2+2 %>  

then it will display  
4  

run project  
npx nodemon index.js  

server runs on  
http://localhost:5000  

tech used  
Node.js  
Express.js  
EJS  
Nodemon  

Author  
Shubham Kakloter
