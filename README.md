# NewYork-Presbyterian-Hospital-Division-Database-Project

## Client: New York-Presbyterian Hospital
Objective: Implement a new information system for data storage and usage to support hospital expansion in Long Island City, a high population growth area post-COVID-19.

## My Role:

System Development: Designed and developed a patient database to ensure accurate and precise transfer of patient records to the new location.

Database Management: Created a clear, transfer-friendly database structure, enabling comprehensive patient profiles to prevent treatment conflicts.

Location Analysis: Addressed the needs of patients from both Manhattan and Queens, leveraging the strategic location of the new facility.

## Key Features:

Patient Information Integration: Developed a system to incorporate patient data, including personal information, for precise identification and efficient medical resource allocation.

Physician Assignment Module: Implemented a feature for assigning physicians based on patient disease and disorder profiles, optimizing department allocations like surgery and tumor treatment.

## Outcome:

Successfully integrated OBGYN, Cardiology, and other departments into the new sub-hospital, enhancing market share and healthcare delivery in New York City.


ER MODEL USING UML NOTATION
# <img width="460" alt="image" src="https://github.com/chenliu521/NewYork-Presbyterian-Hospital-Division-Database-Project-/assets/71107771/19c3f599-dda8-4393-9088-346598042bec">

## Entity:
1.	Patient: Patient_id
2.	Department: Department_id
3.	Staff: can be superclass, having doctor, nurse, office people, etc. subclasses
4.	Appointment:
5.	TreatmentType: Surgery, etc
6.	Treatment: each patient each visit, treatment history
7.	Prescription: Drug_Name
8.	Billing: Billing_Num
9.	Patient
10.	Payment

## RELATIONSHIP SENTENCES

![image](https://github.com/chenliu521/NewYork-Presbyterian-Hospital-Division-Database-Project-/assets/71107771/278da508-9050-445a-9002-dca6b71f36d7)

![image](https://github.com/chenliu521/NewYork-Presbyterian-Hospital-Division-Database-Project-/assets/71107771/89e49a27-c3f5-4838-90f9-ce1a68a22b11)

![image](https://github.com/chenliu521/NewYork-Presbyterian-Hospital-Division-Database-Project-/assets/71107771/00bbd4c4-5b50-4fbc-88fd-d18286e1f2a2)

![image](https://github.com/chenliu521/NewYork-Presbyterian-Hospital-Division-Database-Project-/assets/71107771/3837f136-2352-4f55-92ae-085c0418aa07)

![image](https://github.com/chenliu521/NewYork-Presbyterian-Hospital-Division-Database-Project-/assets/71107771/f5c0dd0f-e733-496c-b112-0b17402a319e)

![image](https://github.com/chenliu521/NewYork-Presbyterian-Hospital-Division-Database-Project-/assets/71107771/0d779ace-69b7-4885-8795-1776e2e2c6b8)

![image](https://github.com/chenliu521/NewYork-Presbyterian-Hospital-Division-Database-Project-/assets/71107771/020baade-937c-40e2-bc4a-ee6d3ca663c8)

![image](https://github.com/chenliu521/NewYork-Presbyterian-Hospital-Division-Database-Project-/assets/71107771/688030f7-4961-4549-8dbc-550a8c6ddb57)

![image](https://github.com/chenliu521/NewYork-Presbyterian-Hospital-Division-Database-Project-/assets/71107771/29d42fa0-ec78-4540-a997-9b0a3eeddc03)

![image](https://github.com/chenliu521/NewYork-Presbyterian-Hospital-Division-Database-Project-/assets/71107771/b5ea8564-9a23-4183-a16c-6c45de305e55)

![image](https://github.com/chenliu521/NewYork-Presbyterian-Hospital-Division-Database-Project-/assets/71107771/718e7b75-e536-43c2-84a0-b2500ef4ed39)

![image](https://github.com/chenliu521/NewYork-Presbyterian-Hospital-Division-Database-Project-/assets/71107771/15b5c87c-4ecb-47b6-86a5-88e7e6df41c7)

![image](https://github.com/chenliu521/NewYork-Presbyterian-Hospital-Division-Database-Project-/assets/71107771/19504113-701b-41bd-b320-782a768ff2b2)

![image](https://github.com/chenliu521/NewYork-Presbyterian-Hospital-Division-Database-Project-/assets/71107771/c2af5fdd-44d9-4caf-9cb1-ef3e76339f8e)

![image](https://github.com/chenliu521/NewYork-Presbyterian-Hospital-Division-Database-Project-/assets/71107771/cd83f4a0-071c-415a-b0ce-c35c741b6f88)

![image](https://github.com/chenliu521/NewYork-Presbyterian-Hospital-Division-Database-Project-/assets/71107771/d0a0c5df-1a9a-4e6c-ac4e-6027b1ada3da)

# CONVERTING THE ERD TO A RELATIONAL MODEL: ERD->RDM
![image](https://github.com/chenliu521/NewYork-Presbyterian-Hospital-Division-Database-Project-/assets/71107771/224ec329-495d-437e-ab95-78e1cc1521e1)

![image](https://github.com/chenliu521/NewYork-Presbyterian-Hospital-Division-Database-Project-/assets/71107771/a7a68d59-ff93-4e7f-86d0-2f1f9fa396d2)

![image](https://github.com/chenliu521/NewYork-Presbyterian-Hospital-Division-Database-Project-/assets/71107771/520742e9-3272-4b2a-bdb0-16ee95fa6d06)

![image](https://github.com/chenliu521/NewYork-Presbyterian-Hospital-Division-Database-Project-/assets/71107771/a474857a-c030-4c1f-b7b2-8eb680697157)

![image](https://github.com/chenliu521/NewYork-Presbyterian-Hospital-Division-Database-Project-/assets/71107771/bde846e3-09b7-4937-828a-0bda051650de)

![image](https://github.com/chenliu521/NewYork-Presbyterian-Hospital-Division-Database-Project-/assets/71107771/60e4f81a-bd72-4c72-8ec3-495b71276ad2)

![image](https://github.com/chenliu521/NewYork-Presbyterian-Hospital-Division-Database-Project-/assets/71107771/d70dcfad-cbd8-401a-b695-325337147175)

![image](https://github.com/chenliu521/NewYork-Presbyterian-Hospital-Division-Database-Project-/assets/71107771/2efd26d7-d134-4f3e-aa7d-f6f8e4c26f49)

![image](https://github.com/chenliu521/NewYork-Presbyterian-Hospital-Division-Database-Project-/assets/71107771/6550cd5e-e4da-4342-8eac-dc1b5bdac6c2)

![image](https://github.com/chenliu521/NewYork-Presbyterian-Hospital-Division-Database-Project-/assets/71107771/859d9c4e-7eaf-40d2-ba18-1e62ce302a68)

![image](https://github.com/chenliu521/NewYork-Presbyterian-Hospital-Division-Database-Project-/assets/71107771/7126cd53-40ca-4837-93d7-77cebd86073f)

![image](https://github.com/chenliu521/NewYork-Presbyterian-Hospital-Division-Database-Project-/assets/71107771/d58d6284-9dd0-4bc6-947a-506a35e2b80d)

![image](https://github.com/chenliu521/NewYork-Presbyterian-Hospital-Division-Database-Project-/assets/71107771/1a8e6bdf-8e3f-4f92-b61f-09949801328a)

# ![image](https://github.com/chenliu521/NewYork-Presbyterian-Hospital-Division-Database-Project-/assets/71107771/467e1a3b-e28c-40ab-bea0-529e0f956d83)


![image](https://github.com/chenliu521/NewYork-Presbyterian-Hospital-Division-Database-Project-/assets/71107771/e4d9f9d7-97c8-4343-a65f-ba0c6d5b5c19)


![image](https://github.com/chenliu521/NewYork-Presbyterian-Hospital-Division-Database-Project-/assets/71107771/15eba853-73cc-4e80-b683-4d67744cf9d2)


![image](https://github.com/chenliu521/NewYork-Presbyterian-Hospital-Division-Database-Project-/assets/71107771/373f9aa7-cd96-4bfb-9e06-40677e2720a9)


![image](https://github.com/chenliu521/NewYork-Presbyterian-Hospital-Division-Database-Project-/assets/71107771/5c7a6d9b-dc29-4cd0-aaf4-93df9c0b72e9)


![image](https://github.com/chenliu521/NewYork-Presbyterian-Hospital-Division-Database-Project-/assets/71107771/5414233e-edcb-4ced-89e7-5d8de0aa94b1)


![image](https://github.com/chenliu521/NewYork-Presbyterian-Hospital-Division-Database-Project-/assets/71107771/74cd62ab-6f1b-4873-ae47-add2c251e8bd)


![image](https://github.com/chenliu521/NewYork-Presbyterian-Hospital-Division-Database-Project-/assets/71107771/dee6970e-8d5c-4b9e-94a2-6cdde05b7a84)


![image](https://github.com/chenliu521/NewYork-Presbyterian-Hospital-Division-Database-Project-/assets/71107771/f726e4d9-f8d5-4a0f-aaba-24ba32a083b0)


![image](https://github.com/chenliu521/NewYork-Presbyterian-Hospital-Division-Database-Project-/assets/71107771/e3f50c87-1200-49f5-97de-2bcf656cbbb1)



# ![image](https://github.com/chenliu521/NewYork-Presbyterian-Hospital-Division-Database-Project-/assets/71107771/8e906ece-e910-4e23-b487-d696bbcf25f5)
 

![image](https://github.com/chenliu521/NewYork-Presbyterian-Hospital-Division-Database-Project-/assets/71107771/8b150d97-00a6-496e-90e7-3c5bd5881bb3)


![image](https://github.com/chenliu521/NewYork-Presbyterian-Hospital-Division-Database-Project-/assets/71107771/f0e69aa7-e4d4-4046-89d8-b6611585246b)
 

![image](https://github.com/chenliu521/NewYork-Presbyterian-Hospital-Division-Database-Project-/assets/71107771/12a3677e-b3d4-4a3b-8132-a073f4cb3c85)


![image](https://github.com/chenliu521/NewYork-Presbyterian-Hospital-Division-Database-Project-/assets/71107771/3d3695eb-4819-43ce-bf5a-14669e934639)
 

![image](https://github.com/chenliu521/NewYork-Presbyterian-Hospital-Division-Database-Project-/assets/71107771/a8af28d5-b162-41a6-8c4f-34cc30d38983)

 

![image](https://github.com/chenliu521/NewYork-Presbyterian-Hospital-Division-Database-Project-/assets/71107771/de17f01a-c4e6-4c5c-bd7b-ce544f519ed5)

 
![image](https://github.com/chenliu521/NewYork-Presbyterian-Hospital-Division-Database-Project-/assets/71107771/9ccf6737-7f57-490b-b6d3-5b369744f415)


![image](https://github.com/chenliu521/NewYork-Presbyterian-Hospital-Division-Database-Project-/assets/71107771/5fb1f3a3-6408-4a51-b590-98b978a89771)


![image](https://github.com/chenliu521/NewYork-Presbyterian-Hospital-Division-Database-Project-/assets/71107771/26c38e43-6996-4930-9146-6fe8282cbcd5)

 
![image](https://github.com/chenliu521/NewYork-Presbyterian-Hospital-Division-Database-Project-/assets/71107771/ffb175e2-d4a3-4fe1-8c1e-b1c5221a1289)


![image](https://github.com/chenliu521/NewYork-Presbyterian-Hospital-Division-Database-Project-/assets/71107771/b37ec2f4-0e89-48bf-bf98-2c303a3b927c)

![image](https://github.com/chenliu521/NewYork-Presbyterian-Hospital-Division-Database-Project-/assets/71107771/8a2123c6-358d-4b4e-97c8-154cb2066c9e)
 
 
![image](https://github.com/chenliu521/NewYork-Presbyterian-Hospital-Division-Database-Project-/assets/71107771/bee27121-45df-42a7-ade8-2458d96617c2)
 
![image](https://github.com/chenliu521/NewYork-Presbyterian-Hospital-Division-Database-Project-/assets/71107771/ee4b191d-64b4-490c-9752-7b15569382b7)

![image](https://github.com/chenliu521/NewYork-Presbyterian-Hospital-Division-Database-Project-/assets/71107771/8aa82889-fd1f-41e9-a0d4-96fc06cb52bb)
 
![image](https://github.com/chenliu521/NewYork-Presbyterian-Hospital-Division-Database-Project-/assets/71107771/7901ef2f-589f-474b-b27e-2b1bd63d893c)
 
![image](https://github.com/chenliu521/NewYork-Presbyterian-Hospital-Division-Database-Project-/assets/71107771/e2cdcd77-c2b1-430e-8c15-5fcd3e5b20db)
