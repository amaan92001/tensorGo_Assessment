# Billing and Invoice Automation with Zapier Integration

Welcome to the **TensorGo Assessment Project**, a comprehensive solution for automating billing and invoice generation for SaaS customers. This repository includes both the backend (Node.js) and frontend (React) implementations, seamlessly integrated with Zapier for automated workflows.

---

## **Features**

### **Frontend**
- **Google OAuth Login**: Secure login using Google accounts.
- **Usage Details**: Display detailed metrics for SaaS usage.
- **Billing Information**: Show billing cycle details and cumulative usage.
- **Invoice Generation**: Generate and download invoices directly from the interface.

### **Backend**
- **User Authentication**: Powered by Google OAuth.
- **Usage Metrics**: Fetch and manage user-specific SaaS usage data.
- **Billing Details**: Calculate and display billing information.
- **Zapier Integration**: Automate billing processes and notifications.

### **Integration with Zapier**
- Trigger workflows based on usage thresholds.
- Automatically send notifications and generate invoices.

---

## **Tech Stack**

### Frontend
- **React.js**
- **Axios**
- **Material-UI** or **Tailwind CSS**

### Backend
- **Node.js**
- **Express.js**
- **MongoDB**
- **Passport.js**
- **Zapier API**

---

## **Getting Started**

### **Prerequisites**
- Node.js (v14 or higher)
- MongoDB (local or cloud instance)
- Zapier account

### **Installation**

1. Clone the repository:
   ```bash
   git clone https://github.com/amaan92001/tensorGo_Assessment.git
   cd tensorGo_Assessment
   ```

2. Navigate to the backend and frontend directories to install dependencies:
   ```bash
   cd backend && npm install
   cd ../frontend && npm install
   ```

3. Configure environment variables:
   - Backend (`backend/.env`):
     ```env
     GOOGLE_CLIENT_ID=<your-client-id>
     GOOGLE_CLIENT_SECRET=<your-client-secret>
     MONGO_URI=<your-mongo-uri>
     ```
   - Frontend (`frontend/.env`):
     ```env
     REACT_APP_GOOGLE_CLIENT_ID=<your-client-id>
     ```

4. Start the development servers:
   - Backend:
     ```bash
     cd backend
     npm start
     ```
   - Frontend:
     ```bash
     cd frontend
     npm start
     ```

5. Open the application in your browser at `http://localhost:3000`.

---

## **Zapier Workflows**

### Example Workflow
- **Trigger**: SaaS usage exceeds a predefined threshold.
- **Action**: Generate an invoice and send an email notification to the user.

---

## **Contributing**

Contributions are welcome! Please follow these steps:
1. Fork the repository.
2. Create a new branch: `git checkout -b feature-name`.
3. Commit your changes: `git commit -m "Add new feature"`.
4. Push to the branch: `git push origin feature-name`.
5. Submit a pull request.

---

## **License**

This project is licensed under the [MIT License](LICENSE).

---

## **Contact**

For any inquiries, please reach out:
- **Name**: Amaan Patel
- **Email**: amaanpatel500@gmail.com
- **GitHub**: [amaan92001](https://github.com/amaan92001)
