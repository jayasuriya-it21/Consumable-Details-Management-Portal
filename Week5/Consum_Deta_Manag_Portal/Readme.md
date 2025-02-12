### **🚀 Installation and Setup Guide**  

---

### **1️⃣ Clone the Repository**  
Open **Command Prompt (CMD) or PowerShell** and run:  
```sh
git clone <URL>
cd <Folder>
```

---

### **2️⃣ Install Dependencies**  

#### **Frontend Setup**  
```sh
cd frontend
npm install
```

#### **Backend Setup**  
```sh
cd ../backend
npm install
```

---

### **3️⃣ Configure Environment Variables**  
Go to the **backend** directory and create a `.env` file:  
```sh
cd backend
copy .env.example .env
```
Open `.env` in a text editor and update values:  
```env
MONGO_URI=mongodb://127.0.0.1:27017/mern-inventory
JWT_SECRET=your_jwt_secret_key
PORT=5000
```
**For MongoDB Atlas:** Replace `MONGO_URI` with your connection string.

---

### **4️⃣ Run the Backend Server**  
```sh
npm run server
```
✅ **Backend should now run on:** `http://localhost:5000`

---

### **5️⃣ Run the Frontend Server**  
Go back to the frontend directory:  
```sh
cd ../frontend
npm run dev
```
✅ **Frontend should now run on:** `http://localhost:5173`

---

### **6️⃣ Access the Application**  
🌍 Open your browser and go to **[http://localhost:5173](http://localhost:5173)**  

---

### **🛠 Usage Instructions**  
🔹 **Login or Signup** to access the system.  
🔹 Navigate through sections like **Orders, Suppliers, Consumables, Sales, Employees** using the sidebar.  
🔹 **Switch between Light/Dark mode** in settings.  
🔹 **Log out** when done.  

---