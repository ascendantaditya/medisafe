# MediSafe

A decentralised solution for digitalising medical records with an added encryption layer.

## Tech Stack used

- Golang - Backend API (for interoperability)
- Solidity - Blockchain (Ethereum contracts, hosted on Sepholia Testnet)
- InterPlanetary File System (IPFS) - Database (Best way to store big data like files)

## Problem statement

Handling medical papers like blood reports and xray records can be a tedious task. Also an average Indian spends 50 mins in a queue at a hospital (Source: NHA Reports). Implementing a centralised storage exposes a huge risk of data breach and fraudulent records.

## Solution Implemented

The MediSafe leverages blockchain technology and smart contracts to establish a decentralized and tamper-proof platform for the storage and sharing of electronic health records (EHRs). In MS, each patient is assigned a unique identifier (UID) and their health records are securely stored and linked to this identifier. 

Central to the IHP framework is the implementation of an individualized IHP card, which serves as a comprehensive repository for a patient's health records, including reports, prescriptions, medical bills, and insurance receipts. The MS card is equipped with a unique QR code linked to the patient's UID. When scanned by a medical practitioner, the patient receives an OTP via two-factor authentication, providing an additional layer of consent and security. Upon successful verification, the doctor gains access to a specific subset of the patient's shared records, ensuring the patient's privacy is respected. 

The MS framework significantly streamlines the customer intake process, eliminating the need for manual data entry at healthcare facility receptions. This minimises waiting times & increases operational efficiency. Furthermore, by integrating the customer's medical history with the MS card, medical service providers gain comprehensive insights into the customer's health status, facilitating accurate diagnoses and personalized treatment plans. 

To enable efficient healthcare service discovery, the IHP framework utilizes standardized APIs to connect customer-centric applications (CCAs) with medical service provider applications (MSPs). Through these APIs, CCAs can access real-time information on available healthcare facilities, ensuring customers receive accurate and up-to-date details regarding their healthcare options.
