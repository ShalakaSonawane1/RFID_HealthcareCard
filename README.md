# **Smart Health Card Using RFID for Medical Records Management**

## **Overview**
Medical errors are the third-leading cause of death, and healthcare systems face challenges such as long wait times, medication errors, inventory mismanagement, and poor patient tracking. This project proposes a **Smart Health Card** leveraging **RFID technology** to automate and streamline medical record management.

## **Problem Statement**
- Lack of real-time patient information sharing across healthcare providers.
- Manual record-keeping leading to errors and inefficiencies.
- Long hospital wait times due to manual verification.
- Medication errors due to lack of access to patient history.
- Inefficient hospital resource management.

## **Proposed Solution**
This project introduces an **RFID-based Smart Health Card** that stores and updates patient medical records automatically. The system consists of:
- **RFID Cards** assigned to patients, storing their medical history.
- **RFID Reader Module** used by doctors, pharmacists, and hospitals to retrieve and update patient information.
- **A secure backend database** to manage patient records.

## **System Architecture**
The system comprises:
1. **Patient RFID Card** – Stores unique patient ID linked to their medical records.
2. **RFID Reader Module** – Reads patient RFID data when scanned.
3. **Cloud Database** – Securely stores patient records and updates upon each scan.
4. **Web & Mobile Applications** – Provides an interface for doctors and pharmacists to access and update records.

## **Circuit Diagram**
![image](https://github.com/user-attachments/assets/1308a6b0-a78a-46cc-908f-24e37300199e)


## **Technology Stack**
1. express.js
2. node.js
3. MongoDB

## **Features**
✔️ **Automated Medical Record Updates** – No manual input required.  
✔️ **Secure Patient Data Access** – Only authorized medical professionals can access records.  
✔️ **Real-time Data Retrieval** – Doctors and pharmacists instantly retrieve updated patient history.  
✔️ **Error Reduction** – Minimizes medication errors by ensuring correct prescriptions.  
✔️ **Faster Processing in Hospitals** – Reduces patient waiting time for check-ups and prescriptions.  

## **How It Works**
1. The **patient scans their RFID card** at the hospital.
2. The **RFID Reader fetches** the patient's unique ID.
3. The system **retrieves and updates** medical records from the cloud.
4. Doctors and pharmacists can **view the latest patient history**.
5. Any new diagnosis, prescription, or treatment is **updated to the system**.

This README will make your project well-documented and ready for GitHub. Let me know if you need modifications or code snippets for specific parts! 🚀
