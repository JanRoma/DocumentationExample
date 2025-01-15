# Software Requirements Specification (SRS)

# Ditionary
- **QR Code:** A machine-readable code containing ticket information.
- **Kiosk:** A self-service terminal for purchasing tickets.

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


### **2.2 Use Cases**
- **UC-1:** Customer purchases a ticket at the counter.
- **UC-2:** Employee validates a paper ticket at the entry gate.
- **UC-3:** Customer redeems a reward after collecting a specific number of stamps on their card.

### **2.3 Processes**
#### Ticket Sales Process (AS-IS)

![ticket-selling-diagram](http://www.plantuml.com/plantuml/proxy?cache=no&src=https://raw.githubusercontent.com/JanRoma/DocumentationExample/refs/heads/main/Processes/ticket-selling/ticket-selling-as-is.puml)

#### Entry Validation Process (AS-IS)

![ticket-checking-process-as-is](http://www.plantuml.com/plantuml/proxy?cache=no&src=https://raw.githubusercontent.com/JanRoma/DocumentationExample/refs/heads/main/Processes/ticket-checking/ticket-checking-as-is.puml)

---

## **3. Future State (TO-BE)**

### **3.1 System Architecture**
The updated system will leverage automation and digital platforms:
- **Online Ticket Sales:** Tickets can be purchased via a website or kiosks.
- **QR Code Entry Validation:** Automated scanners validate tickets at entry points.
- **Digital Loyalty Program:** Customer accounts automatically track visits and rewards.

### **3.2 Use Cases**

### **3.3 Processes**
#### Ticket Sales Process (TO-BE)
- Customer selects and pays for tickets online or via a kiosk.
- System generates a QR code and sends it to the customer.
![ticket-selling-process-to-be](http://www.plantuml.com/plantuml/proxy?cache=no&src=https://raw.githubusercontent.com/JanRoma/DocumentationExample/refs/heads/main/Processes/ticket-selling/ticket-selling-to-be.puml)

#### Entry Validation Process (TO-BE)
- Customer scans the QR code at the entry gate.
- System validates the ticket and grants access.

![ticket-checking-process-to-be](http://www.plantuml.com/plantuml/proxy?cache=no&src=https://raw.githubusercontent.com/JanRoma/DocumentationExample/refs/heads/main/Processes/ticket-checking/ticket-checking-to-be.puml)

---

## **4. Requirements**

### **4.1 Functional Requirements**

### **4.2 Non-Functional Requirements**

### **4.3 UI/UX Requirements**

### **4.4 Other Requirements**

---

---

---

