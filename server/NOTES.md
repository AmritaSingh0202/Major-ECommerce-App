Install using npm init -y:no need to write any details;
Install all dependency:
npm i bcryptjs cloudinary cookie-parser cors dotenv express jsonwebtoken mongoose multer nodemon
add gitignore to ignore those which you dont want to push;
create server.js add replace in pkgjson file in main;
CONNECT Mongodb in it:
     on Mdb Atlas create main project -> create cluster ->whitelist ip then
     "mongodb+srv://kamritasingh5858_db_user:kamritasingh5858@e-commerce-app.cfrlbdw.mongodb.net/"
     password:kamritasingh5858
In server.js:create exp app -> Connect mongo-> add cookie parser -> cors{here add client side running port i.e 5173, origin , method what been used ,header used}
In pkgjson:to start by just :
start:server.js
dev:nodemon
="npm run dev"