# 😂 DIY Jokes API

A simple **Node.js REST API** for managing jokes.  
You can fetch random jokes, search by ID or type, add your own jokes, update existing ones, and delete jokes.

---

## 🚀 Features
- **Get a random joke**  
- **Get a joke by ID**  
- **Filter jokes by type** (e.g., dad jokes, programming jokes)  
- **Add a new joke** via `POST`  
- **Update an existing joke**  
- **Delete all jokes**  
- **Delete a specific joke**

---

## 🛠️ Tech Stack
- **Node.js**
- **Express.js**

---

## 📦 Installation

1.  Clone the repository:
     ```
     git clone https://github.com/your-username/diy-jokes-api.git
     cd diy-jokes-api
    ```

2.  Install dependencies:
   ```
   npm install
   ```

3.  Start the server:
  ```
  node solution.js
  ```
---

## 📚 API Endpoints

🔹 Get a random joke:  
GET /random

🔹 Get a joke by ID:  
GET /jokes/:id

🔹 Filter jokes by type:  
GET /filter?type:

🔹 Add a new joke:  
POST /jokes

🔹 Update an existing joke:  
PUT /jokes/:id

🔹 Delete all jokes:  
DELETE /jokes

🔹 Delete a specific joke:  
DELETE /jokes/:id

---

## 🧪 Testing
Use Postman, cURL, or any REST client to test the endpoints. 

Example:
curl http://localhost:3000/random
