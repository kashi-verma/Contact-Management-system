# ERINO: Contact Management Feature

## ⭐ SDE Internship Assignment  

This repository contains a Contact Management feature, a mini component of a Customer Relationship Management (CRM) system.  

---

## 🗒️ Overview  

The **Contact Management** feature simplifies managing customer/client contact information. With functionalities like adding, viewing, updating, and deleting contact details, it centralizes information and ensures efficient communication and record-keeping.  

### Use Cases  
1. **Adding a New Contact**:  
   Add essential details such as Name, Email, Phone Number, Company, and Job Title for new customers or clients.  
2. **Viewing Contacts**:  
   A table displays all contacts with **sorting** and **pagination** for ease of navigation.  
3. **Editing Contact Information**:  
   Update contact details to maintain current and reliable data.  
4. **Deleting a Contact**:  
   Remove outdated or irrelevant entries, keeping the contact list clean and efficient.  

---

## ❗Important Note  

This assignment will be followed by a live coding session where additional features will be implemented or modified.  
- Complete the work **independently** to demonstrate originality and effort.  
- External help or automated tools are discouraged and may negatively affect evaluation.  

---

## 🥇 Evaluation Criteria  

1. **Functionality**: Fully implemented CRUD operations.  
2. **UI Consistency**: Intuitive interface with effective use of Material UI (MUI).  
3. **Code Quality**: Modular, clean, and adherent to best practices.  
4. **Problem-Solving Approach**: Independent, well-thought solutions to challenges.  

---

## 🗒️ Specifications / Requirements  

### Frontend (ReactJS with Material UI)  

#### 1. Contact Form  
- Capture contact details using these fields:  
  - First Name  
  - Last Name  
  - Email  
  - Phone Number  
  - Company  
  - Job Title  
- Implement using **Material UI (MUI)** for forms, buttons, and layout.  

#### 2. Contacts Table  
- Display all contact details using the **MUI Table** component.  
- Features:  
  - Columns for each attribute (e.g., Name, Email, etc.)  
  - Action buttons for editing and deleting contacts.  
  - **Pagination** and **sorting** for better usability.  

---

### Backend (Node.js)  

#### API Endpoints  
- **POST /contacts**: Add new contact data.  
- **GET /contacts**: Retrieve all contacts.  
- **PUT /contacts/:id**: Update contact information.  
- **DELETE /contacts/:id**: Delete a contact.  

#### Error Handling  
- Validation for required fields.  
- Handle duplicate entries or invalid data.  
- Return appropriate error messages for API issues.  

---

### Database  

#### Setup  
- Use any database (e.g., PostgreSQL, MySQL, MongoDB).  

#### Features  
- Fully implemented CRUD operations.  

#### Documentation  
- Describe the chosen database and its suitability for the project.  

---

## 🚀 Project Submission  

### Code Repository  
- Provide a GitHub repository link with the project code.  

### ReadMe File  
1. **Setup Instructions**:  
   - Include steps to run the project locally.  
   - Provide database schema/scripts if applicable.  
2. **Project Description**:  
   - Briefly explain the project and its key functionalities.  
   - Mention major technical decisions.  
3. **Challenges & Solutions**:  
   - Highlight challenges faced during development.  
   - Describe how you resolved them.  

---

### 🛠️ How to Run  

1. Clone the repository:  
   ```bash  
   git clone https://github.com/your-username/erino-contact-management.git  
   ```  

2. Navigate to the project directory:  
   ```bash  
   cd erino-contact-management  
   ```  

3. Install dependencies:  
   ```bash  
   npm install  
   ```  

4. Set up the database:  
   - Create a database.  
   - Run the provided schema file in your chosen database.  

5. Start the backend server:  
   ```bash  
   npm run server  
   ```  

6. Start the frontend:  
   ```bash  
   npm start  
   ```  

7. Access the app:  
   Open [http://localhost:3000](http://localhost:3000) in your browser.  

---

## 💡 Challenges & Solutions  

### Challenge  
Handling form validation and error messages dynamically.  

### Solution  
Used MUI form components with custom validation hooks to provide real-time feedback and ensure error resilience.  

