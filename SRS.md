# Software Requirements Specification (SRS)

## **1. Project Overview**

### **1.1 Project Description**
The "Pure Fun" amusement park aims to modernize its operations by transitioning from a manual ticketing and loyalty system to a fully automated digital system. The proposed changes will streamline ticket sales, entry validation, and loyalty program management, enhancing the overall customer experience and operational efficiency.

### **1.2 Project Objectives**
- Automate ticket sales through an online platform and on-site kiosks.
- Implement QR code-based entry validation to replace manual checks.
- Develop a digital loyalty program that tracks customer visits and rewards them automatically.

### **1.3 Target Users**
- **Customers:** Visitors to the park who purchase tickets and participate in the loyalty program.
- **Employees:** Staff managing park entry, customer support, and system oversight.

---

## **2. Current State (AS-IS)**

### **2.1 System Architecture**
The current system involves manual operations:
- **Ticket Sales:** Conducted at physical counters where employees issue paper tickets.
- **Entry Validation:** Employees manually check tickets at entry gates.
![alternative text](http://www.plantuml.com/plantuml/proxy?cache=no&src=https://raw.githubusercontent.com/JanRoma/DocumentationExample/main/Processes/ticket-checking/ticket-checking-as-is.puml)


### **2.2 Use Cases**
- **UC-1:** Customer purchases a ticket at the counter.
- **UC-2:** Employee validates a paper ticket at the entry gate.
- **UC-3:** Customer redeems a reward after collecting a specific number of stamps on their card.

### **2.3 Processes**
#### Ticket Sales Process (AS-IS)
- Customer requests a ticket.
- Employee confirms availability and issues a paper ticket.
- Customer pays and receives the ticket.

#### Entry Validation Process (AS-IS)
- Customer hands the paper ticket to an employee at the gate.
- Employee verifies and allows entry.

#### Loyalty Program Process (AS-IS)
- Employee stamps the customer’s card for each visit.
- Customer redeems rewards when the card is full.

*(Insert AS-IS architecture diagram here)*

---

## **3. Future State (TO-BE)**

### **3.1 System Architecture**
The updated system will leverage automation and digital platforms:
- **Online Ticket Sales:** Tickets can be purchased via a website or kiosks.
- **QR Code Entry Validation:** Automated scanners validate tickets at entry points.
- **Digital Loyalty Program:** Customer accounts automatically track visits and rewards.

### **3.2 Use Cases**
- **UC-1:** Customer purchases a ticket online or via a kiosk.
- **UC-2:** QR code is scanned at the entry gate, and the system validates it.
- **UC-3:** Customer receives rewards automatically after a threshold is reached.

### **3.3 Processes**
#### Ticket Sales Process (TO-BE)
- Customer selects and pays for tickets online or via a kiosk.
- System generates a QR code and sends it to the customer.

#### Entry Validation Process (TO-BE)
- Customer scans the QR code at the entry gate.
- System validates the ticket and grants access.

#### Loyalty Program Process (TO-BE)
- System automatically updates visit counts when the ticket is scanned.
- Rewards are issued digitally when thresholds are met.

*(Insert TO-BE architecture diagram here)*

---

## **4. Requirements**

### **4.1 Functional Requirements**
- The system must allow customers to purchase tickets online and at kiosks.
- QR codes must be generated for every ticket purchase.
- Scanners at entry gates must validate QR codes in real time.
- The loyalty program must automatically track visits and issue rewards.

### **4.2 Non-Functional Requirements**
- The system must process ticket validations within 2 seconds.
- All customer data must be securely stored and comply with GDPR.
- The system should support at least 10,000 transactions per day.

### **4.3 UI/UX Requirements**
- The website and kiosk interfaces must be intuitive and accessible.
- The app must provide clear feedback after a ticket purchase or QR code scan.
- Loyalty program rewards and status must be visible on the customer’s account dashboard.

### **4.4 Other Requirements**
- The system must integrate with existing park management software.
- The solution must be scalable for future park expansions.

---

## **5. Diagrams**

### **5.1 System Architecture**
*(Insert diagram showing connections between actors, ticketing system, QR code scanners, and loyalty program)*

### **5.2 Use Case Diagrams**
*(Insert diagrams depicting AS-IS and TO-BE use cases for ticket sales, entry validation, and loyalty program)*

### **5.3 Activity Diagrams**
*(Insert activity diagrams for AS-IS and TO-BE processes)*

---

## **6. Glossary**
- **QR Code:** A machine-readable code containing ticket information.
- **Loyalty Program:** A system that tracks customer visits and rewards them.
- **Kiosk:** A self-service terminal for purchasing tickets.

---

## **7. Appendix**
- List of existing systems.
- Details on compliance requirements.
