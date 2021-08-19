# PharmacyManagementSystem
Pharmacy Dispensing Management System || Python Django

This is a simple Pharmacy's Dispensing Management System programmed using Python Django. The system has 5 types of users are the Administrator, Pharmacist, Doctor, and Receptionist(pharmacyClerk) and Patient. The Administrator User can manage all the features of the system and he/she is the only user who can create a new system user. The Pharmacist Users have access to managing the stock of the medicinal drugs and they are the ones who are in charge of dispensing the drugs. The Doctor Users can create Prescriptions for the patients. The Receptionist Users are in charge of managing the list of admissions/patients.This project has user-friendly functionalities.The Patient Can view his/her medications , can also send a feedback messege to the pharmacist incase something occur.

<div> <img src="https://github.com/tech-jamara/PharmacyManagementSystem/blob/main/screenshot/Admin%20Login.png" width="400" height="200" />
<img src="https://github.com/tech-jamara/PharmacyManagementSystem/blob/main/screenshot/Pharmacist.png" width="400" height="200" />
</div>
<div> <img src="https://github.com/tech-jamara/PharmacyManagementSystem/blob/main/screenshot/Doctor%20Login.png" width="400" height="200" />
<img src="https://github.com/tech-jamara/PharmacyManagementSystem/blob/main/screenshot/Receptionist%20Login.png" width="400" height="200" />
    <img src="https://github.com/tech-jamara/PharmacyManagementSystem/blob/main/screenshot/Patient%20login.png" width="400" height="200" />
</div>

## Run these Commads

- Step 1: `pip install -r requirements.txt`
- Step 2: `python manage.py migrate`
- Step 3: `python manage.py runserver`
-----------------------------------------------------------------------------------

### Admin User Login: 
- Username: admin
- password: 1234  
  
          Administrator Main Features
     - Manage Admissions/Patients
     - Manage System Users
     - Manage Patient's Prescription
     - Manage Medicinal Drugs Categories
     - Manage Medicinal Drugs
     - Manage Stocks
     - Dispense Medicinal Drug
     - Manage Personal Account

------------------------------------------------------------------------------------
### Patient Login:
- Username: patient1
- password: 1234

           Patient Main Featues
     -  Manage his/her medications
     - Feedback Pharmacist incase of dispensing issue
     -  manage Personal Account
      
 
-----------------------------------------------------------------------------------
### Pharmacist Login:
- Username: pharmacist1
- password: 1234

        Pharmacist  Main Features
     - Manage Medicinal Drugs
     - Manage Stocks
     - Dispense Medicinal Drug
     - Manage Patient Feedback messeges
     - Manage Personal Account
     
        

-------------------------------------------------------------------------------------
### PharmacyClerk Login:
- Username: pharmacyclerk1
- password: 1234

            Receptionist Main Features
     - Manage Admissions/Patients
     - Manage Personal Account

------------------------------------------------------------------------------------
### Doctor Login:
- Username: doctor1
- password: 1234
        
        Doctor Main Featues
     - Manage Patient's Prescription
     - Manage Personal Account
   
-----------------------------------------------------------------------------------

N/B: When adding New patient there are some validations in filling the forms 
     For easy filling of forms use fake filler extension in chrome 
     Fake Filler Extension Chrome link:https://chrome.google.com/webstore/detail/fake-filler/bnjjngeaknajbdcgpfkgnonkmififhfo

--------------------------------------------------------------------------------------










