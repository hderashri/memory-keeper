To run the code:  

1. Goto `server` -> `index.js` -> `line 19` and change the credentials according to your MongoDB connection  
2. Go to `https://console.cloud.google.com/apis` and create a new project. Create an account, if necessary and give any name to the project  
3. Go to `Credentials` of the project app and add `http://localhost:3000` under `Authorized JavaScript origins` URIs  
4. And also, add `http://localhost:3000` and `http://localhost:3000/auth` under `Authorized redirect URIs` URIs
5. Save it. Copy the `Client ID` and paste it on `client` -> `src` -> `components` -> `Auth` -> `Auth.js` -> `line 82`
6. `cd Memories-Keeper`  
7. Open two consoles:  

On console 1-  
`cd client`  
`npm install`  
`npm start`  

On console 2-  
`cd server`  
`npm install`  
`npm start`
