### **📅 Week 8 Worklog – Core Backend Development (Part 2)**  
**🗓️ Date:** 03.03.2025 – 08.03.2025  
**🎯 Objective:**  
- Implementation of additional backend APIs and business logic.  
- Enhanced database queries to handle complex use cases.  
- Ensured seamless integration of backend APIs with the frontend.  

---

## **💼 Individual Contributions:**  

### **1️⃣ Santhosh K (7376212IT221) – Backend API Development**  
- **Created Complex Database Queries:**  
   - Developed MongoDB aggregate queries to handle complex data relationships between `User`, `Product`, and `Request` collections.  
   - Added filtering, sorting, and pagination support for product and request lists.  

- **Enhanced Request Handling:**  
   - Created new endpoints in `requestController.js` to fetch filtered requests based on status (Pending, Approved, Rejected).  
   - Added logic to handle partial approvals (if stock is insufficient).  

- **Data Consistency:**  
   - Ensured data consistency using Mongoose transactions to handle simultaneous updates to inventory and request status.  

---

### **2️⃣ Jayasuriya J (7376212IT160) – Backend API Integration & Testing**  
- **Enhanced API Integration:**  
   - Worked on integrating new backend APIs with the frontend using Axios.  
   - Updated `UserDashboard.jsx` and `OrderTracking.jsx` to reflect real-time backend updates.  

- **API Error Handling:**  
   - Added `try-catch` blocks and improved status codes for better error reporting.  
   - Ensured proper error messages are shown on the frontend during request failures.  

- **Performance Tuning:**  
   - Optimized data fetching to reduce load time on the frontend by modifying Axios requests.  
   - Implemented lazy loading for dashboard components to minimize initial load time.  

---

### **3️⃣ Rakesh M (7376212IT208) – Backend-Frontend Synchronization**  
- **Full-Stack Integration:**  
   - Connected new request and product APIs with the frontend state management (Zustand).  
   - Ensured that real-time updates in order tracking and product inventory were reflected on the frontend.  

- **WebSocket Integration:**  
   - Set up WebSocket connection for live updates in the user and admin dashboards.  
   - Ensured order status changes were pushed to the frontend without the need for a refresh.  

- **Bug Fixes:**  
   - Fixed inconsistencies in the state update for request status and stock levels.  
   - Resolved mismatched product IDs during request submission.  

---

### **4️⃣ Praveen R (7376212IT201) – Security & API Authentication**  
- **API Security:**  
   - Enhanced JWT authentication for new API routes.  
   - Restricted admin-only routes using middleware (`adminMiddleware.js`).  

- **Access Control:**  
   - Improved user role validation to prevent unauthorized access to admin routes.  
   - Ensured proper handling of token expiration and refresh.  

- **Testing:**  
   - Tested all new APIs using Postman to validate request/response format and data integrity.  
   - Identified and fixed CORS issues when connecting to frontend.  

---

## **✅ Accomplishments:**  
✔️ New API routes created for complex queries and business logic.  
✔️ Enhanced API security using JWT and admin role checks.  
✔️ Improved data fetching and rendering speed on frontend using Axios and Zustand.  
✔️ Real-time updates enabled using WebSocket integration.  
✔️ Enhanced data consistency using MongoDB transactions.  

---

## **🚧 Challenges:**  
🔸 Handling simultaneous API requests without data loss.  
🔸 Resolving state conflicts during frontend-backend sync.  
🔸 Ensuring proper CORS handling for secure API access.  

---
