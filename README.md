# Whatsapp-Clone-App

How to run this project:

- Clone this repository or fork it.
  - To clone this repository type `git clone https://github.com/B-HemanthKumar/Whatsapp-Clone-App.git` on your command line
  - To fork this repository, click fork button of this repository then type `git clone https://github.com/<your username>/whatsapp-clone-app.git`

 - In `Backend` folder, create a new file named `.env` which stores informations about server side variables such as `ATLAS_URI`, `SECURITY_KEY` and `CLIENT_URL` informations
  - `ATLAS_URI` variable stores your database(MONGODB) URI  
  - `SECURITY_KEY` variable stores your security key 
  - `CLIENT_URL` variable stores your client url  

 - example:
  ```
  ATLAS_URI =mongodb+srv://admin:<password>@cluster0.8aezk.gcp.mongodb.net/whatsappClone?retryWrites=true&w=majority
  SECURITY_KEY = D73373D9B4ED6FEC5B8B2DAF6WA929B1C7D14CDC88B196EBDCCEA77AFF7BB9
  CLIENT_URL = http://localhost:3000/
  ```
- Inside `Frontend` folder, create a new file called `.env` which stores your information about client side such as `REACT_APP_SECURITY_KEY` and `REACT_APP_BACKEND_URL` informations

  - `REACT_APP_SECURITY_KEY` variable stores your security key , note that this value must same as `SECURITY_KEY` in `server/.env` file
  - `REACT_APP_BACKEND_URL` variable stores your server url  

 - example:
  ```
  REACT_APP_SECURITY_KEY = D73373D9B4ED6FEC5B8B2DAF6WA929B1C7D14CDC88B196EBDCCEA77AFF7BB9
  REACT_APP_BACKEND_URL = http://localhost:5000
  ```
- ports in local server:

  - Fronted side (Client) : http://localhost:3000
  - Backend side (Server) :http://localhost:5000

- Install all dependencies

  - Fronted side (Client) : on the `Fronted` directory type `npm install`
  - Backend side (Server) : on the `server` directory type `npm install`

- Run it on node js:

  - Fronted side (Client): on the `Fronted` directory type `npm start`
  - Backend side (Server): on the `server` directory type `npm start` 

#### Warning: This project has some basics security functions such as hashed user password, encrypt messages and so on, But it is NOT secure enough in production mode.
