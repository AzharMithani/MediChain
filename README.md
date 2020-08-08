# Blockchain-healthcare
A Healthcare Information Exchange System implemented using Blockchain Technology, I'm calling this system MediChain for short.

<br />

## Features 

What can MediChain do for you in today's world?

<dl>

  <dt>Integrated Payment Methods</dt>
  <dd>Pay your doctor at your own convenience through multiple payment methods.</dd>

  <dt>Add your preferred hospital</dt>
  <dd>Add your hospital for easier access.</dd>

  <dt>Manage your patients all in one platform</dt>
  <dd>Access/create/update your patients medical records all in this one stop platform for you doctors.</dd>

  <dt>Manage your doctors all in one platform</dt>
  <dd>Add and remove doctors in your hospital in an instant</dd>

</dl>


## Project Images

### HOME

<img src="/home.png" alt="Azzy's MediChain banner" align="center" />

### SIGNUP

<img src="/login.png" alt="Azzy's MediChain banner" align="center" />

### LOG IN
<img src="/signup.png" alt="Azzy's MediChain banner" align="center" />



### HOW IT WORKS

<br />

<img src="/How_it_works-pt1.JPG" alt="Azzy's MediChain banner" align="center" />


<img src="/How_it_works-pt2.JPG" alt="Azzy's MediChain banner" align="center" />

### Doctor

<img src="/Doctor-Dashboard.JPG" alt="Azzy's MediChain banner" align="center" />


<img src="/Doctor-create presccription.JPG" alt="Azzy's MediChain banner" align="center" />


<img src="/Doctor-Edit_Prescription.JPG" alt="Azzy's MediChain banner" align="center" />


<img src="/Doctor-medical records.JPG" alt="Azzy's MediChain banner" align="center" />


<img src="/Doctor-medical_records_of_selected_patient.JPG" alt="Azzy's MediChain banner" align="center" />


<img src="/Doctor-PatientList.JPG" alt="Azzy's MediChain banner" align="center" />


<img src="/Doctor-prescription of selected record.JPG" alt="Azzy's MediChain banner" align="center" />


### PATIENTS

<img src="/Patient-Dashboard.JPG" alt="Azzy's MediChain banner" align="center" />

<img src="/Patient-HospitalList.JPG" alt="Azzy's MediChain banner" align="center" />

<img src="/Patient-MedicalRecord.JPG" alt="Azzy's MediChain banner" align="center" />

<img src="/Patient-Update Personal Info.JPG" alt="Azzy's MediChain banner" align="center" />

<img src="/wallet.JPG" alt="Azzy's MediChain banner" align="center" />


<br />

<div align="center">
  <sub>By (you guessed it right!) Azhar Mithani </a></sub>
</div>

## Quick start
Follow the instructions below.
## Hyperledger Composer
<br> 0. Set up the lab environment 
<br> 1. Download the fileblockchain_network/healthcare-blockchain(Clean).bna file 

<br> 2.Run the following commands:
<br> - cd easy-hyperledger-composer
<br> - npm run build_image
<br> - npm run test_bna
<br> - npm run setup_crypto
<br> - npm run start_fabric
<br> - npm run start_playground
<br> - go to localhost:8080/ and import our healthcare-blockchain(Clean).bna file in and deploy
<br> - Under Credentials for System Adminstrator, select 'ID and Secret'
<br> - Input Enrollment ID: admin and Enrollment Secret: adminpw

<br> 3. Set up the following participants:
<br> - Hospital identified as h1
<br> - Doctor identified as d1 assigned to h1 hospital
<br> - Patient identified as p1 assigned to h1 hospital

<br>4. Issue new identities to participants on the composer.
<br> - Doctor d1 as d1
<br> - Patient p1 as p1

<br>5. To start the rest server:
<br> - npm run start_rest-server p1@blockchain-healthcare 3001
<br> - npm run start_rest-server d1@blockchain-healthcare 3002

**Great! Now you have the blockchain network up and running!

## Front-End 

1. Clone this repo 
2. Move to the appropriate directory
3. Run `yarn` or `npm install` to install dependencies.
4. Run `npm start` to see the example app at `http://localhost:3000`.

**Now you're ready to build on our Blockchain Application!**

## Logging in
<br> **Logging in as a patient**
<br> userid : bcd
<br> password: password

<br> **Logging in as a doctor**
<br> userid : abc
<br> password: password

## Troubleshooting 

**Common problems when launching front-end such as:**
1. internal/modules/cjs/loader.js:596 throw err;
    <br>Error: Cannot find module './types.json</br>
    <br>FIX: Remove node_modules folder and re-run npm install on terminal</br>
2. Cannot find module 'express-http-proxy'
    <br>FIX: npm install express-http-proxy</br>



## Info

Project made as a part of individual study on "Strategic implementation of blockchain in healthcare industry" at Schulich School of Business, York University.


