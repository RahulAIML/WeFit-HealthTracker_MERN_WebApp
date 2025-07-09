# 📗 WeFit Health Tracker

![License](https://img.shields.io/badge/License-MIT-green.svg)
![Node.js](https://img.shields.io/badge/Node.js-HealthTracker-brightgreen)
![Status](https://img.shields.io/badge/Status-In%20Progress-yellow)

**WeFit** is a simple web-based health tracker app that lets users record and track daily health metrics like steps, calories burned, distance covered, and weight. It uses MongoDB as the backend database.

---

## 🚀 Features

✅ Register and manage user profiles  
✅ Track daily health data: steps, calories burned, distance, and weight  
✅ View records for selected dates  
✅ Data stored securely in MongoDB  
✅ Clean, minimalistic UI for easy tracking

---

## 🗃️ Database Collections

**MongoDB Compass Structure:**

- **`health-app.users`**

  Stores user data:
  ```json
  {
    "_id": ObjectId,
    "name": "User Name",
    "email": "user@example.com",
    "password": "<hashed_password>",
    "createdAt": "<date>"
  }


⚙️ Setup & Run Locally
1️⃣ Clone the Repository
```
git clone https://github.com/your-username/wefit-health-tracker.git
cd wefit-health-tracker
```
#2️⃣ Install Dependencies
```
npm install
```
### 3️⃣ Set up .env File
 ```json
MONGODB_URI=<your-mongodb-uri>
PORT=5000
```
### 4️⃣ Run the App
```
npm start
```
5️⃣ Open in Browser
 ```
Visit http://localhost:5000 to use the app.

###📸 Screenshots

📝 Future Improvements
User authentication (JWT)

Charts and analytics for better insights

Mobile-responsive design

Reminder notifications

### 👤 Author
### Buddhadeb Bhattacharya

### 📧 bhattacharyabuddhadeb147@gmail.com

### 🗂️ License
This project is licensed under the MIT License.

###  Screenshots
![Screenshot 2025-07-10 013617](https://github.com/user-attachments/assets/4436c6e7-e309-4680-a9f1-b884cfc8589a)
![Screenshot 2025-07-10 013659](https://github.com/user-attachments/assets/703af99d-37c0-4d48-af68-db8c324816af)
![Screenshot 2025-07-10 013554](https://github.com/user-attachments/assets/09255331-3173-4500-9f1b-ff331d28526e)
![Screenshot 2025-07-10 013912](https://github.com/user-attachments/assets/e466af73-08b3-43ae-b924-1f594dbab5e4)
![Screenshot 2025-07-10 014036](https://github.com/user-attachments/assets/862cd6ef-c6a4-4b4a-b240-357062a6f5a5)
![Screenshot 2025-07-10 014052](https://github.com/user-attachments/assets/c53b07c8-9fb6-4fb2-b4f5-65a56bfd5f69)
