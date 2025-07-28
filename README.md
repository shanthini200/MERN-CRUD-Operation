### MERN-CRUD-Operation

This MERN CRUD app allows users to add, view, update, and remove records through a user-friendly React interface backed by a RESTful API. With clean separation between client and server, it serves as a solid foundation for full‑stack development.

## 🧰 Features

- Create, read, update, and delete records via a RESTful API.
- Frontend built with React.js, using Axios for HTTP requests.
- Backend powered by Express.js and connected to MongoDB via Mongoose.
- Clean architecture: separate `client` and `server` folders.

## ⚙️ Technologies Used
- **MongoDB**, **Express.js**, **React.js**, **Node.js**  
- **Mongoose** for schema modeling  
- **Axios** (client–server HTTP requests)

## 🚀 Getting Started
## 1. Clone the Repository
   
```bash
git clone https://github.com/shanthini200/MERN-CRUD-Operation.git
cd MERN-CRUD-Operation
```
## 2. Install Dependencies
   
Backend Setup:
```bash
cd server
npm install
```
Create a ".env" file with your MongoDB connection string.
```bash
mongoose.connect("mongodb://connections string/yourdbname");
```

Frontend Setup:
```bash
cd client
npm install
```
## Run the app:
```bash
cd server
npm start
```
## Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

The page will reload when you make changes.\
You may also see any lint errors in the console.


### 🧩 Project Structure
```
/client       # React application
  /src
    components/
      AddForm.jsx
      EditForm.jsx
      List.jsx
    services/
      api.js
    App.js
/server       # Backend API
  models/
    Model.js
  routes/
    routes.js
  server.js
.env
```
### If the following are implemented correctly, it's likely functional:

- Check that server logs (Backend APIs (create/read/update/delete)) show listening and connected to MongoDB via Mongoose.
- Ensure the React UI loads and CRUD interactions reflect correctly.
- Frontend components making Axios API calls to those endpoints.
- Verify API responses using tools like Postman (GET, POST, etc.).
- Proper routing using React Router and live state updates after actions.

### 🧪 Troubleshooting
MongoDB not connected? Check the connection URL in .env.

 - 🔍 CORS issues? Make sure Express has cors() middleware enabled.
 - 🔍 Port conflicts? Ensure backend and frontend are on separate ports (e.g. 5000 and 3000).
 - 🔍 UI blank/React errors? Check browser console for missing dependencies or import issues.

## 📄 License
This project is licensed under the Apache 2.0 License.

## 👤 Author
- Shandhini Parthiban
- GitHub: @shanthini200
- Feel free to connect and explore more projects!



