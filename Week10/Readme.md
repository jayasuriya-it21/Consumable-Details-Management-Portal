## **Worklog for Week 10 (17.03.2025 – 22.03.2025)**  
**Objective:**  
✅ **Integration and Testing (Part 2)**  
- Complete functional testing.  
- Fix identified bugs and improve system performance.  

---

## **Team Contributions:**  

### 👨‍💻 **Jayasuriya J (7376212IT160) – Frontend Functional Testing and Bug Fixing**  
- Conducted functional testing on the **User Dashboard** and **Request Form** modules.  
- Fixed UI inconsistencies in:  
  - `UserDashboard.jsx` – Corrected rendering issues in real-time stock updates.  
  - `RequestForm.jsx` – Fixed quantity validation error and ensured smooth request submission.  
- Enhanced performance by optimizing state management using `React.memo` and `useCallback`.  
- Improved API call efficiency by reducing redundant state updates in `RequestForm.jsx`.  
- Verified request lifecycle from submission to approval/rejection.  
- Fixed routing errors in `React Router` for dashboard navigation.  
- Enhanced mobile responsiveness using CSS media queries.  

---

### 👨‍💻 **Santhosh K (7376212IT221) – Backend Performance Tuning and Error Fixes**  
- Conducted functional testing of all backend APIs (`/api/auth`, `/api/requests`, `/api/products`).  
- Fixed issues in `requestController.js` where rejected requests were not updating stock correctly.  
- Enhanced MongoDB query performance using indexing on `userId` and `productId` fields.  
- Resolved token expiry issue in `authController.js` by adjusting JWT expiration time.  
- Fixed input validation errors in `productController.js` (missing fields).  
- Improved server response times by reducing payload size and enabling gzip compression.  
- Handled missing error responses for undefined API calls to improve debugging.  

---

### 👨‍💻 **Rakesh M (7376212IT208) – End-to-End Integration and State Sync**  
- Performed end-to-end testing of:  
  - `OrderTracking.jsx` – Verified that tracking status is consistent with backend data.  
  - `RequestList.jsx` – Ensured real-time sync between request lifecycle and stock updates.  
- Fixed CORS issues when fetching data from backend.  
- Improved state synchronization using `useEffect` and `setState` cleanup.  
- Corrected state inconsistencies when switching between pending and approved requests.  
- Improved response time of `RequestList.jsx` by reducing API call frequency.  
- Fixed broken links and incorrect routes in `Sidebar.jsx`.  
- Enhanced loading states and feedback messages for better user experience.  

---

### 👨‍💻 **Praveen R (7376212IT201) – Admin Module Testing and UI Optimization**  
- Conducted functional testing on admin modules:  
  - `ManageInventory.jsx` – Fixed UI misalignment and improved response time.  
  - `UserManagement.jsx` – Ensured role-based access works as intended.  
  - `AdminDashboard.jsx` – Verified accurate data rendering in Recharts.  
- Fixed inventory update delay by adjusting backend query execution order.  
- Resolved JWT token refresh issues causing logout during session expiry.  
- Improved UI consistency across admin screens with global CSS styles.  
- Added error messages for invalid admin actions (e.g., duplicate product names).  
- Fixed inconsistencies in status updates when tracking pending requests.  
- Enhanced data fetching by implementing `lazy loading` in admin components.  

---

## ✅ **Summary of Progress:**  
✅ Completed functional testing of all major modules.  
✅ Fixed API and UI inconsistencies.  
✅ Improved performance with reduced response times and optimized state handling.  
✅ Enhanced mobile responsiveness and UI consistency.  
✅ Resolved CORS issues and ensured real-time sync between frontend and backend.  
✅ Fixed routing errors and missing API response handling.  
✅ Verified user roles and permissions for secure data handling.  

---


**👉 Week 10 focused on enhancing system stability, fixing critical bugs, and improving performance across the frontend and backend.** ✅