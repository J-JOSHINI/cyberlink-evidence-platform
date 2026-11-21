
# CyberLink – Smart Cybercrime Evidence Linking Platform

A privacy-focused web application designed to organize cybercrime-related evidence and identify relationships between voluntarily submitted information.

## 1. Project Overview
CyberLink connects reported UPI transaction references, phone numbers, email addresses, suspicious messages, identity misuse references, and other digital evidence into a structured relationship map. Its main objective is to simplify evidence organization and help users understand connections between suspected cybercrime incidents.

## 2. Problem Statement
Cybercrime incidents often involve multiple pieces of information—such as suspicious phone numbers, payment references, fraudulent messages, and identity misuse. These details are frequently scattered across screenshots, messages, and documents, making it difficult for victims to organize and understand their evidence. CyberLink addresses this problem through a centralized evidence management and information-linking platform.

## 3. Proposed Solution
CyberLink provides a unified dashboard where users can submit incident details, organize digital evidence, and identify matching information across reports. The application generates visual relationship maps, identifies duplicate records, and creates structured incident summaries.

## 4. Key Features
* **Smart Information Linking:** Automatically correlates matching identifiers across reports.
* **Digital Evidence Locker:** Centralizes submitted details and references in one place.
* **Duplicate Pattern Detection:** Flags repeated numbers, IDs, or transaction references.
* **Visual Connection Mapping:** Displays interactive relationship graphs of linked evidence.
* **Incident Timeline:** Organizes events chronologically for clear review.
* **Privacy-Based Information Masking:** Protects sensitive personal identifiers.
* **Downloadable Evidence Reports:** Generates structured summaries ready for review.

## 5. Supported Information Categories
1. UPI and Bank Transaction References
2. Mobile Number and Contact Information
3. Identity Misuse Reports
4. Passport-Related Fraud Reports
5. Vehicle and FASTag-Related Fraud References
6. Suspicious Emails and Messages
7. Incident Location and Timeline

## 6. Technology Stack
* **Frontend:** HTML, CSS, JavaScript
* **Storage:** Browser Local Storage (prototype data)
* **Future Backend:** Firebase
* **Version Control:** GitHub

## 7. Advantages
* Centralized evidence organization.
* Easier identification of matching information across incidents.
* Reduced manual effort in reviewing multiple scattered reports.
* Clear visual representation of reported connections.
* Better preparation of structured cybercrime incident summaries.

## 8. Limitations and Mitigations

| Limitation | Mitigation Strategy |
| :--- | :--- |
| **Fake reports** | Mark submitted records as unverified by default. |
| **Privacy concerns** | Apply automatic masking to sensitive information. |
| **Incorrect matches** | Require manual human review before drawing conclusions. |
| **Duplicate records** | Use reference-based detection to group identical entries. |
| **Limited external access** | Rely strictly on voluntarily submitted evidence. |

## 9. Privacy and Security Disclaimer
* CyberLink uses fictional demonstration data during prototype testing.
* It does **not** access private bank databases, government identity databases, or unauthorized location records.
* Matching information is **not** treated as proof of criminal activity.
* Sensitive information is protected through masking, user consent, and appropriate access controls.

## 10. How to Run Locally
1. Clone this repository:
   ```bash
   git clone https://github.com
   ```
2. Open the project folder and double-click `index.html` to launch the prototype in your browser.

## 11. Future Enhancements
* Secure cloud backend integration (Firebase).
* Authorized cybercrime reporting portal integration.
* Advanced automated evidence classification.
* Multilingual user interface support.
* Enhanced interactive relationship visualization.

## 12. Expected Outcome
CyberLink aims to make cybercrime evidence easier to organize, understand, and review through an intelligent, connected, and privacy-conscious platform.
