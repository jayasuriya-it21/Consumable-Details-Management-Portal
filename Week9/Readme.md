### **Worklog for Week 9 (10.03.2025 – 15.03.2025)**
**Objective:**  
✅ Integration and Testing (Part 1)  
- End-to-end integration of frontend and backend.  
- Unit testing for individual modules.  

---

### **Team Contributions:**  

#### 👨‍💻 **Jayasuriya J (7376212IT160) – Frontend Integration & Testing**  
- Integrated frontend with backend APIs using Axios.  
- Ensured smooth state management using `useState` and `useEffect` hooks in key components.  
- Performed unit testing on:  
  - `UserDashboard.jsx` – Verified accurate stock display and order statuses.  
  - `RequestForm.jsx` – Ensured form validation and proper submission handling.  
- Fixed routing issues with `React Router` during dashboard navigation.  
- Enhanced responsiveness and UI consistency using CSS.  

---

#### 👨‍💻 **Santhosh K (7376212IT221) – Backend API Testing & Integration**  
- Verified data consistency in MongoDB during API testing.  
- Fixed issues in `requestController.js` where rejected requests were not adjusting stock properly.  
- Debugged `productController.js` to ensure CRUD operations for stock management work correctly.  
- Unit tested:  
  - `/api/requests` – Ensured correct request status updates.  
  - `/api/products` – Verified data consistency during add, update, and delete operations.  
- Improved API error handling for better debugging and feedback.  

---

#### 👨‍💻 **Rakesh M (7376212IT208) – Full-Stack Integration and Sync Testing**  
- Integrated `OrderTracking.jsx` and `RequestList.jsx` with backend APIs.  
- Ensured real-time updates using Axios and React state.  
- Synchronized frontend request lifecycle with backend status updates.  
- Performed unit testing on:  
  - `OrderTracking.jsx` – Verified order tracking timeline and updates.  
  - `RequestList.jsx` – Checked admin-side request management and real-time updates.  
- Fixed CORS errors and ensured smooth state management.  

---

#### 👨‍💻 **Praveen R (7376212IT201) – Admin Module Testing**  
- Connected `AdminDashboard.jsx`, `ManageInventory.jsx`, and `UserManagement.jsx` to backend APIs.  
- Verified secure access using JWT-based authentication.  
- Performed unit testing on:  
  - `ManageInventory.jsx` – Ensured accurate stock adjustments on approval/rejection.  
  - `UserManagement.jsx` – Verified admin role handling and user status updates.  
- Fixed API response inconsistencies in `/api/products` and `/api/users`.  
- Ensured smooth data rendering and API calls in admin panel.  

---

### ✅ **Summary of Progress:**  
✅ Successful end-to-end integration of frontend and backend.  
✅ Verified smooth state transitions and API responses.  
✅ Resolved data synchronization issues in inventory and request modules.  
✅ Completed unit testing for key modules – request handling, stock management, user authentication.  
✅ Fixed UI inconsistencies and routing issues.  

---
