# Full-stack Challenge Guide (Onlypay)

The Full-stack Challenge encourages you to create a CRUD (Create, Read, Update, Delete) web application that showcases your skills in both backend and frontend development. We will assess your ability to use modern frameworks and tools while emphasizing clean, maintainable code and a polished, user-friendly product.

---

### **Technology Stack Overview**

This project requires using the following technologies:

---

### Backend: **Express.js, Node.js, Relational Database**

- **Express.js** is a minimal and widely used web framework for building APIs in Node.js. It provides flexibility and simplicity for structuring backend applications.

- **Node.js** is a popular server-side JavaScript runtime. It allows for fast, asynchronous processing and is great for I/O-intensive applications like web services.

- **Relational Database** (PostgreSQL, MySQL, etc.) should be used to persist data. The choice of database is up to the candidate and also the databack package as Prisma, Orm, Sequelize, etc...

- **TypeScript** TypeScript provides static typing that catches bugs during development rather than at runtime.
It acts as living documentation, making complex codebases easier for teams to navigate with perfect autocomplete and refactoring tools.

- **NextJS** A progressive Node.js framework for building efficient, reliable and scalable server-side applications. (It's completely optional, but it's a plus)


**Why use these technologies?**

- **Simplicity and Flexibility**: Express allows you to structure your application the way you want without enforcing rigid patterns.

- **Real-world Usage**: Node.js and relational databases are widely used in production systems.

- **Optional Type Safety**: TypeScript is encouraged but not mandatory.

---

### **Frontend: React.js (or React-based framework)**

- **React.js** (or a framework like Next.js) should be used to build the frontend.

- Use **React Hooks** and **Context API** for state management.

- **TypeScript** is optional, but considered a **differential**.

**Why use React?**

- **Component-based architecture**: Encourages reusable and maintainable UI.

- **Hooks**: Simplifies state and lifecycle management.

- **Ecosystem**: Large ecosystem and flexibility in implementation.

---

### **Environment**

- Use **Docker** or **docker-compose** to run the application.

- The environment should include:
  - Backend service
  - Database
  - (Optional) Frontend service

---

## **Project Requirements**

#### **Backend**

1. **Express Server Setup**

   - Set up a basic server with **Express.js** in **Node.js**.
   - Ensure that your server handles HTTP requests properly (GET, POST, PUT, DELETE).
   - Include basic **authentication** with sign-up and sign-in functionality (JWT, session-based, etc.).

---

2. **Database Interaction (Relational Database)**

   - Connect the server to a **relational database** of your choice.
   - Implement CRUD operations to create, read, update, and delete records in the database.
   - Ensure proper validation and error handling throughout the CRUD operations.
   - Remember to document your relational schema and handle migrations.

---

#### **Frontend**

1. **React Web App**

   - Set up a **React** frontend that interacts with the backend.
   - Implement authentication on the frontend, with sign-up and sign-in pages (JWT or session-based).

   - Create pages for:

     - **Creating** a new record (form-based interaction).
     - **Reading** existing records (display records in a list or table).
     - **Updating** existing records (editable form).
     - **Deleting** existing records (confirmation prompt before deletion).

---

2. **State Management**

   - Use **React Hooks** for local state management.
   - Use **Context API** for global state (e.g., authentication).
   - Ensure that the frontend is responsive and works well across different devices.

---

## **Bonus and Extras**

The following bonuses will help demonstrate your full-stack capabilities and make your submission stand out:

---

1. **Open Source**:

   - Share your code on GitHub.
   - Include a clear README file with instructions on how to run the application.

---

2. **Automated Tests**:

   - Write unit and integration tests for backend and frontend.
   - Tools are up to you (e.g., Vitest, Jest, React Testing Library).

---

3. **Design System**:

   - Implement a simple and consistent UI.
   - Focus on usability and accessibility.

---

4. **API Documentation**:

   - Use **OpenAPI (Swagger)** to document your backend.
   - Clearly describe authentication and endpoints.

---

5. **Deployment**:

   - Deploy the application (optional).
   - Include environment configuration if needed.

---

6. **CI/CD Pipeline**:

   - Optional setup using GitHub Actions or similar.

---

## **Creativity and Design**

While the technical aspects are crucial, creativity in terms of product and design will be considered.

- Keep the scope simple.
- Focus on clarity and usability.
- Avoid overengineering.

---

## **How to Get Started?**

1. Create a new repository.
2. Build your solution.
3. Document your decisions.
4. Share your project.

---

## **Useful Resources**

- Express.js docs  
- React docs  
- Docker docs  
- OpenAPI (Swagger)
