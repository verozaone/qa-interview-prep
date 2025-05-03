# 🧠 Basic Concepts of Software Testing

This file contains foundational QA concepts, ideal for interview preparation and beginner-level recap.

---

## 1. What is Software Testing?

Software testing is the process of evaluating a system or its components to verify that it meets specified requirements and is free of defects.  
It helps ensure **software quality**, **reliability**, and **user satisfaction** before release.

---

## 2. Difference Between Static & Dynamic Testing

| Aspect | Static Testing | Dynamic Testing |
|--------|----------------|-----------------|
| Execution | Performed **without executing** the code | Involves **executing** the code |
| Purpose | Reviews documentation or code to detect defects early | Checks runtime behavior of the software |
| Examples | Code reviews, walkthroughs, inspections | Unit testing, integration testing |

---

## 3. Validation vs Verification

- **Verification**: Are we building the product right?  
  – Performed using static techniques like reviews and walkthroughs.

- **Validation**: Are we building the right product?  
  – Performed using dynamic techniques like actual test execution.

---

## 4. Objectives of Testing

- Detect defects early
- Ensure the software meets user and business requirements
- Gain confidence in the product's quality
- Prevent future defects
- Improve the overall reliability and performance of the system

---

## 5. Testing vs Debugging

- **Testing**: Identifying defects in software (QA responsibility)
- **Debugging**: Investigating and fixing the cause of defects (Developer responsibility)

---

## 6. Test Process (STLC – Software Testing Life Cycle)

1. **Test Planning**
2. **Test Case Design**
3. **Test Environment Setup**
4. **Test Execution**
5. **Defect Reporting and Tracking**
6. **Test Closure Activities**

---

# 🧪 Test Levels & Testing Types

Understanding **Test Levels** and **Testing Types** is crucial in software testing, especially in multi-tiered or complex applications.

---

## 🔸 7. Test Levels (STLC Layers)

Test levels define **where** and **what** we test in the software development lifecycle.

| **Level**             | **Purpose**                                                                 |
|-----------------------|------------------------------------------------------------------------------|
| **Unit Testing**      | Tests **individual components or functions** in isolation (usually by developers). |
| **Integration Testing** | Tests **data flow and communication** between modules, components, or APIs. |
| **System Testing**    | Tests the **entire application** as a complete system to verify against requirements. |
| **Acceptance Testing**| Tests the application **from a user's perspective** to ensure it meets business needs. |

### ✅ Key Details

### 1. Unit Testing
- Done by **developers**
- Tests one "unit" of code (function/class)
- Frameworks: JUnit, TestNG, NUnit
- Helps catch bugs early in the SDLC

### 2. Integration Testing
- Tests **interaction between integrated components**
- Detects issues in interfaces, APIs, or microservices
- Techniques: Top-down, Bottom-up, Big Bang
- Example: Testing communication between login page & database

### 3. System Testing
- Performed by **QA team**
- Black-box testing of the **entire application**
- Validates **functional and non-functional requirements**
- Includes UI, APIs, databases, workflows, etc.

### 4. Acceptance Testing
- Final testing before deployment
- Performed by **end-users or stakeholders**
- Types: Alpha (internal) and Beta (external users)
- Goal: Ensure the product solves the business problem

---

## 🔹 8. Testing Types

Testing types define the **approach or focus** of the testing.

### ✅ Common Functional & Non-Functional Testing Types

---

### 🔍 Functional Testing
- Verifies **what** the system does
- Based on user requirements/specifications
- Example: Login button should authenticate the user with valid credentials

---

### 🚀 Non-Functional Testing
- Verifies **how** the system performs
- Includes:

| Type           | Purpose                                     |
|----------------|---------------------------------------------|
| **Performance Testing** | Check response time, throughput under load |
| **Security Testing**    | Ensure data privacy, secure access     |
| **Usability Testing**   | Check user-friendliness, UI flow       |
| **Compatibility Testing** | Test across devices, browsers, OS   |

---

### 🔁 Regression Testing
- Ensures **existing functionality is not broken** by new changes
- Must be run after every code update
- Automated wherever possible (Selenium, Postman)

---

### 🔥 Smoke Testing
- "Build Verification Test"
- Quick, high-level tests to verify basic app stability
- If smoke fails → stop testing

---

### 🕵️ Exploratory Testing
- Tester explores the app **without predefined test cases**
- Based on experience and intuition
- Useful in new features or loosely documented systems

---

### 🧠 Usability Testing
- Evaluates the application from the **end-user’s perspective**
- Focus on design, intuitiveness, accessibility
- Example: Is the checkout process on an e-commerce site smooth?

---

## 📌 Summary Tips for Interview

- Explain **test levels** as layers in QA: Unit → Integration → System → Acceptance
- Mention test types with **purpose + real example**
- Emphasize **regression** and **smoke testing** for release cycles
- Highlight **non-functional testing** when asked about performance or security


---

## 9. What’s Next?

After mastering the basics:
- Learn automation tools like **Selenium, Postman, Playwright**
- Practice writing **test cases** and **bug reports**
- Explore **test frameworks** like TestNG or JUnit
- Understand **CI/CD pipelines** for automated test execution
- Review real-world examples and join open-source QA contributions

---

📚 **Use this as a foundational reference** for interviews and practical QA work.
