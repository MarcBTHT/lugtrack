# Luggage Tracking System using Blockchain
This project won the first place at the Dauphine Hackaton 2023 organized by Kryptosphere

## Problem
- Travelers often face stress during their journeys due to uncertainty about the whereabouts of their luggage.
- Searching for a lost suitcase can be a lengthy and cumbersome process.
- Currently, only the airline is held responsible for lost baggage.

## Solution
Our solution involves implementing a baggage tracking system using a reliable decentralized database on a global scale. The advantages include:
- Tracking the luggage process through a decentralized database.
- Identifying the responsible stakeholder in case of baggage loss.
- Reducing the risk of suitcase loss.

## Product
![Diagram](https://github.com/MarcBTHT/lugtrack/assets/116173196/4b448779-b79b-43b4-a777-0188fa4d9e8e)
- Creation of a Public Address for Each Suitcase during Registration:
    - Whenever a user registers their suitcase, a unique public address is created for that suitcase.
- Recording Transactions at Each Checkpoint:
    - Whenever the suitcase reaches a checkpoint, it is scanned, and the operator signs the corresponding transaction.
- Traceability Until User Retrieval:
    - The process repeats until the user retrieves their suitcase, allowing for complete traceability.

## Achieved MVP
- Creation of a Public Address for Each Passenger and a Unique ID for Each Suitcase:
    - During registration, a public address is assigned to each passenger, and a unique ID is generated for each suitcase.
- Creation of a QR Code for Each Suitcase:
    - Each suitcase is assigned a QR code containing its unique address and ID.
- Scanning the QR Code and Sending Information to a Server:
    - When a QR code is scanned, the associated information is sent to a central server.
- Retrieval by the Smart Contract of the Address and ID:
    - The Smart Contract retrieves the address and ID data, then updates the status of the suitcase based on the reached checkpoint (check-in, in-pending, etc.).

## Demo
https://github.com/Shimadakunn/lugtrack/assets/89693356/d35426c2-6265-4837-9d34-01c6573a33af
