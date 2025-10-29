<div align="center">

<img src="https://naanmudhalvan.tn.gov.in/_nuxt/img/logo.cda70ae.svg" alt="Naan Mudhalvan Logo" width="200">

# 💼 Streamlining Ticket Assignment for Efficient Support Operations
### *A SmartInternz – Naan Mudhalvan Project using ServiceNow Automation*

</div>

---

## 📖 Project Overview
This project focuses on automating **ticket assignment in ServiceNow** to improve support efficiency and reduce manual intervention.  
When a user submits a ticket (such as login issues, certificate problems, or system errors), it is automatically routed to the correct support group — ensuring faster resolution and improved productivity.

---

## 🧩 Objective
To build a **ServiceNow-based automated ticket routing system** that:
- Reduces delays in ticket handling  
- Ensures accurate routing to the right team  
- Enhances operational efficiency  
- Improves customer satisfaction  

---

## ⚙️ Implementation Steps

### 1. Create Users  
- Navigate to **All → Users → New**  
- Add new users (e.g., Katherine Pierce, Manne Niranjan) and submit  

### 2. Create Groups  
- Navigate to **All → Groups → New**  
- Create groups like `Platform` and `Certificates`

### 3. Create Roles  
- Navigate to **All → Roles → New**  
- Create roles `Platform_Role` and `Certificate_Role`

### 4. Create Table  
- Go to **System Definition → Tables → New**  
- Label: `Operations Related`  
- Check **Create Module** and **Create Mobile Module**  
- Add fields like *Issue, Description, Assigned Group*  

### 5. Assign Users & Roles to Groups  
- Add users and their respective roles under each group  

### 6. Set Access Controls (ACLs)  
- Go to **System Security → Access Control (ACL)**  
- Restrict access to authorized roles only  

### 7. Create Flows in Flow Designer  
- Use **Flow Designer** to automate ticket assignment:  
  - If Issue = *Regarding Certificates* → Assign to `Certificates` Group  
  - If Issue = *Login / 404 / Expired* → Assign to `Platform` Group  

---

## 🧠 Outcome
By leveraging **ServiceNow Flow Designer**, this system automatically assigns tickets to the appropriate support team, significantly reducing response time and manual workload.

---

## 📸 Screenshots
*(Add your ServiceNow screenshots here)*  
- User Creation  
- Group Creation  
- Flow Setup  
- Auto Assignment Output  

---

## 🧑‍💻 Team Members
- **Arshekh John JD**  
- **Altan**  
- **Akash**  
- **Arshana**

---

## 🏁 Conclusion
This project successfully demonstrates how ServiceNow can be used to streamline IT service management by automating ticket assignment. It ensures that tickets are routed to the correct teams instantly, improving efficiency, reducing delays, and enhancing overall user satisfaction.

---

<div align="center">

✨ *Developed under the Naan Mudhalvan – SmartInternz Program using ServiceNow* ✨  

</div>
