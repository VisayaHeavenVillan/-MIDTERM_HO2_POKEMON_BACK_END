# MIDTERM_HO2_POKEMON_BACK_END

## 📌 Project Overview
This is the backend for the **Midterm Pokémon Project**, built using **Node.js** and **Express.js**. It will serve as the Web API for the ReactJS frontend, handling data storage and retrieval for Pokémon-related features.

## ⚙️ Installation
To set up and run this project locally, follow these steps:

1. **Clone the Repository**
   ```sh
   git clone https://github.com/aagdv/MIDTERM_HO2_POKEMON_BACK_END.git
   cd MIDTERM_HO2_POKEMON_BACK_END
   ```

2. **Install Dependencies**
   ```sh
   npm install
   ```

3. **Run the Server**
   ```sh
   node index.js
   ```
   _OR_ (if you have nodemon installed)
   ```sh
   nodemon index.js
   ```

## 🚀 API Endpoints
Currently, the backend has the following endpoint:

- `GET /` - Returns a simple response to confirm the API is running.
  ```json
  {
    "message": "Pokemon Backend API is running! ⚡"
  }
  ```

More endpoints will be added as we integrate with a database.

## 📂 Project Structure
```
MIDTERM_HO2_POKEMON_BACK_END/
│── node_modules/  (excluded via .gitignore)
│── index.js       (Main server file)
│── package.json   (Project metadata and dependencies)
│── .gitignore     (Ignored files: node_modules, .env)
```

## 📅 Upcoming Features
✔️ **Database Integration (MongoDB or SQL)**
✔️ **Pokémon CRUD Operations**
✔️ **Authentication & Authorization**
✔️ **Frontend API Consumption (ReactJS)**

## 📜 License  
This project is for educational purposes only.  
Unauthorized commercial use is prohibited.  
Feel free to contribute! 🎉  



