# Disaster-Relief-Secure-Fund-Distribution-System

A secure, region-based disaster fund distribution and management system using DID (Decentralized Identity), AES, RSA, ZKP in cryptography, email OTP for DID recovery, and a blockchain-style immutable ledger.

## System Overview 
The system contains four portals: 
 
1. Victim Portal – victim registers and gets a unique DID. 
2. Officer Portal – officer verifies victims from their own region. 
3. Admin Portal – admin approves funds and transfers them after a time- 
lock. 
4. Blockchain Viewer – shows all the fund transfer blocks and checks if the 
chain is valid. 
  Victim details are stored in a normal database, but fund transfer records are 
stored in a blockchain ledger.

## Architecture 
  <img width="604" height="377" alt="image" src="https://github.com/user-attachments/assets/6cc9936b-d30f-4693-afed-5afdf739bcaf" />


## FEATURES 
 
 Victim registration – DID generation 
 Victim Verification using ZKP 
 No tampering allowed 
Any attempt is immediately detected. 
 Chain validator checks the whole blockchain. 
 Simple and lightweight 
No mining or complex consensus. 
 100% custom 
Designed only for fund transfer safety. 
 Transparent 
Everyone can see the chain openly. 
 DID recovery via Email (SMTP)

## Security Stack

  AES → Encrypt sensitive data
  RSA → Sign transactions
  SHA-256 → Hash Govt ID
  SQLite → Encrypted local DB
  Email OTP → Password reset and DID recovery

## Requirements

  - Python 3.10+
  - Streamlit
  - SQLite3
  - cryptography
  - smtplib (email)
  - pandas

## OUTPUTS : 
## Victim Registration Form 
 
<img width="604" height="291" alt="image" src="https://github.com/user-attachments/assets/c9757875-947c-4b65-9bb6-b79aa3d74a01" />

##After Registration DID generation
 
<img width="645" height="310" alt="image" src="https://github.com/user-attachments/assets/17bdf537-28b6-4bfc-98e2-cbc63c51030a" />

## Victim Status check  (Identity Verified and Fund Status : Pending)


<img width="636" height="324" alt="image" src="https://github.com/user-attachments/assets/5082a79e-e90d-41b2-a073-438e190e9e97" />

## DID Recovery via Email
 
<img width="634" height="350" alt="image" src="https://github.com/user-attachments/assets/db9411cf-4350-46cd-a3f3-fa1cd063ecfa" />

## Verification code generation for DID Recovery
 
<img width="638" height="382" alt="image" src="https://github.com/user-attachments/assets/ed7fad90-b494-4f76-881d-78cad2ced2b2" />

## Successful Verification  And Generation Of New DID

 <img width="653" height="309" alt="image" src="https://github.com/user-attachments/assets/f813cd48-361c-418a-9acb-aa261cd13862" />

## Government Officer Portal

<img width="644" height="316" alt="image" src="https://github.com/user-attachments/assets/45acc8be-e9c4-4d0f-b978-28e870f63f69" />
 
## List Of Pending Victims In The Particular Region

<img width="649" height="311" alt="image" src="https://github.com/user-attachments/assets/aaee5e70-6f28-431d-a260-5a9d1be9e341" />
 
## Verification of victims

<img width="655" height="315" alt="image" src="https://github.com/user-attachments/assets/39c1d482-ddfe-4965-a4ea-25c56939ed70" />

## Successful Verification of victims

<img width="653" height="308" alt="image" src="https://github.com/user-attachments/assets/ed86bce2-078e-450b-8887-4d22fc019899" />
 
## Admin Portal

 <img width="644" height="356" alt="image" src="https://github.com/user-attachments/assets/a806eb6e-55b3-44cf-bdb7-f6b9373bc258" />

## Approve Funds For Verified Victims

<img width="651" height="314" alt="image" src="https://github.com/user-attachments/assets/98a8da6d-d038-4584-a941-ebcde6cfd544" />
 
## Successful Approval of Fund To The Victims

 <img width="645" height="309" alt="image" src="https://github.com/user-attachments/assets/cee1203d-c15c-4426-aa81-fb34d025fc77" />

## Mark Funds as Transferred And Added To The Blockchain
 
<img width="655" height="312" alt="image" src="https://github.com/user-attachments/assets/f9c84b02-b937-4b64-9fc9-8029f1e470e8" />

## Admin Database Viewer – Victims Table And User Table

 <img width="632" height="269" alt="image" src="https://github.com/user-attachments/assets/8939f2d0-c637-4663-b041-b0959f1b081a" />

## Admin Database Viewer – Blockchain Ledger Table 

 <img width="630" height="307" alt="image" src="https://github.com/user-attachments/assets/e3c484ae-a636-42fb-acae-f4090db76b78" />

## Public Blockchain Ledger –  (Block #1)

<img width="602" height="202" alt="image" src="https://github.com/user-attachments/assets/5ea5de21-a695-49f7-ae56-3d03650d4fed" />
 
## Public Blockchain Ledger – ( Block #2)

<img width="693" height="244" alt="image" src="https://github.com/user-attachments/assets/ad45ada8-66cd-4432-8fc6-794f0c6fd725" />
 
## Check Relief Status

 <img width="608" height="278" alt="image" src="https://github.com/user-attachments/assets/55d601e0-3eb8-434a-a342-9fef7a0d925b" />

## The Requested Fund Was Transferred To The Particular Victim (Fund Status : Transferred )

<img width="609" height="249" alt="image" src="https://github.com/user-attachments/assets/e2cd3f60-e617-411c-a807-3e49c60d92b7" />
 

## Clone :
git clone https://github.com/SailajaSelvam/Disaster-Relief-Secure-Fund-Distribution-System.git
cd disaster-relief-fund

## Email Setup
Edit email_utils.py and add:

SENDER_EMAIL = "yourgmail@gmail.com"
APP_PASSWORD = "your-app-password"

## Run the application
streamlit run app.py

 

## Author
## Sailaja S

 
 





