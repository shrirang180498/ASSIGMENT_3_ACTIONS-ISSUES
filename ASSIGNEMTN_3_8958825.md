# Assignment 3: Actionable Tasks for Project  
**Course:** SENG8091-25W-Sec1-Software Engineering Principles  

---

## Project Overview  
This assignment focuses on transforming the requirements from **Assignment 2** into actionable, well-structured tasks. The goal is to create a clear implementation plan that aligns with the client’s needs and ensures the system is scalable, secure, and user-friendly.  

---

## Requirements Breakdown - (From ASSIGNEMTN 2): 
The requirements have been categorized into **Functional** and **System** requirements, ensuring a comprehensive approach to addressing the client’s challenges.  

### **Functional Requirements**  
1. **Categorized Training Questions:**  
   - Developers must be able to classify training questions by **subject, difficulty, and tags**.  
   - A **user-friendly interface (UI)** should be developed to simplify the categorization and tagging process.  
   - Questions and answers must be stored separately to support developer self-affirmation.  

2. **Balanced Training Data:**  
   - The system must include tools to detect and analyze **biases** (e.g., racial, gender, cultural) in the training data.  
   - A **dashboard** should be created to visualize data distribution across categories, helping developers identify and address imbalances.  
   - Developers should have the ability to **filter or modify** the dataset to reduce biases and ensure fairness.  

### **System Requirements**  
1. **Scalability:**  
   - The system must efficiently handle **large datasets** (millions of questions and answers) without performance degradation.  
   - **Parallel processing** capabilities should be implemented to accelerate data classification and analysis tasks.  

2. **Data Protection:**  
   - All data must be **encrypted** both in transit and at rest to ensure security and compliance with privacy standards.  
   - An **access control system** should be implemented to restrict data access to authorized developers only.  

3. **Integration with Web Scraping Tools:**  
   - The system must integrate seamlessly with the client’s existing **web scraping tools**.  
   - Support for **multiple data formats** (e.g., CSV, JSON) should be included to facilitate easy data import and export.  

---

## Actionable Tasks  
To ensure the project is executed effectively, the requirements have been broken down into specific, actionable tasks. These tasks are organized by category and priority, ensuring a logical and efficient implementation process.  

### **1. Categorized Training Questions**  
- **Task 1.1:** Design and implement a **user interface (UI)** for categorizing training questions by subject, difficulty, and tags. The UI should be intuitive and easy to use.  
- **Task 1.2:** Develop a **backend system** to store categorized questions separately from answers. Ensure the system supports efficient querying and retrieval.  
- **Task 1.3:** Implement a **search and filter feature** to allow developers to quickly locate questions based on categories, tags, or difficulty levels. 


### **2. Balanced Training Data**  
- **Task 2.1:** Develop a **bias detection algorithm** to analyze training data for potential biases (e.g., racial, gender, cultural). The algorithm should generate detailed reports for developers.  
- **Task 2.2:** Create a **dashboard** to visualize the distribution of training data across categories. The dashboard should include interactive charts and metrics.  
- **Task 2.3:** Build a **data filtering and modification tool** to allow developers to remove or adjust biased data points, ensuring a balanced dataset. 


### **3. System Scalability**  
- **Task 3.1:** Optimize the system to handle **large datasets** (millions of questions and answers) without performance issues. This includes implementing efficient database indexing and query optimization.  
- **Task 3.2:** Introduce **parallel processing** to speed up data classification, analysis, and bias detection tasks.  


### **4. Data Protection**  
- **Task 4.1:** Implement **encryption** for all data in transit and at rest. Use industry-standard encryption protocols (e.g., AES-256) to ensure data security.  
- **Task 4.2:** Develop an **access control system** to restrict data access to authorized developers. This should include role-based access control (RBAC) and multi-factor authentication (MFA).  


### **5. Integration with Web Scraping Tools**  
- **Task 5.1:** Integrate the system with the client’s existing **web scraping tools**. Ensure seamless data import and export functionality.  
- **Task 5.2:** Support **multiple data formats** (e.g., CSV, JSON) for importing and exporting training data to ensure compatibility with various tools.  

---

## Task Prioritization  
To ensure the project progresses smoothly, the tasks have been prioritized based on their importance and dependencies.  

### **High Priority Tasks (Must be completed first):**  
1. **Task 1.1:** Design and implement the **UI for categorizing training questions**.  
2. **Task 1.2:** Develop the **backend system** for storing categorized questions.  
3. **Task 3.1:** Optimize the system for **scalability**.  
4. **Task 4.1:** Implement **data encryption**.  


### **Medium Priority Tasks (Can be developed after high-priority tasks):**  
1. **Task 2.1:** Implement the **bias detection algorithm**.  
2. **Task 2.2:** Develop the **data distribution dashboard**.  
3. **Task 5.1:** Integrate the system with **web scraping tools**. 


### **Low Priority Tasks (Can be developed last):**  
1. **Task 1.3:** Implement the **search and filter feature**.  
2. **Task 2.3:** Develop the **data filtering and modification tool**.  
3. **Task 3.2:** Introduce **parallel processing**.  
4. **Task 4.2:** Implement **access control**.  
5. **Task 5.2:** Support **multiple data formats**.  
