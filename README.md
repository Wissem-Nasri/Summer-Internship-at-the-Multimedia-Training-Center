# Summer Internship at the Multimedia Training Center
Implemented Active Directory to enhance infrastructure security, integrating Splunk for monitoring and conducting attack simulations.
## Completed Architecture

![Untitled Diagram](https://github.com/user-attachments/assets/7a9fdfd5-d2ad-42a6-aaee-438bca0bb0e5)

## install virtual machines 
#### windows10,windows server 2019, kali linux et ubuntu server(splunk)
![image](https://github.com/user-attachments/assets/3edecff7-204b-4008-8010-86ecc28acc8b)
## install and configure sysmon and splunk 

![image](https://github.com/user-attachments/assets/0f09677e-35af-436f-bf92-9c92a624732c)


![image](https://github.com/user-attachments/assets/5c47008e-c7ee-4113-8ed8-0c95bfa932e2)

![image](https://github.com/user-attachments/assets/cdd2c8f4-9a02-4324-9192-d37cd3b6f37c)
RootRoot123

![image](https://github.com/user-attachments/assets/2019923f-1e5b-4b9a-b8a4-66a470efa519)

![image](https://github.com/user-attachments/assets/a1c7984f-f2bf-485f-9bdb-339e1dd171ea)

![image](https://github.com/user-attachments/assets/0c136a29-aff9-4a1d-8cf9-94a6fb81e816)
## install splunk iniversal folder and sysmon in win10 

![image](https://github.com/user-attachments/assets/3172b846-7d54-45f9-bc18-cea5dfe5fd17)


![image](https://github.com/user-attachments/assets/c44130d5-f1a2-47d6-a2d1-289f5962244d)

![image](https://github.com/user-attachments/assets/089ae274-b6e7-4e39-9a10-5bfd19330e2f)

![image](https://github.com/user-attachments/assets/0d30c88d-5115-4887-b66a-1d309f32dd94)

![image](https://github.com/user-attachments/assets/d6138ea4-f5ef-42b7-88c8-a9764ae14a0f)

#### construct our splunk folder in what we want send to splunk server 

![image](https://github.com/user-attachments/assets/1430a330-6ad2-4792-8a29-4f0f35f6f14c)

C:\Program Files\SplunkUniversalForwarder\etc\system\default

![image](https://github.com/user-attachments/assets/9ab0beca-65c9-4d1a-aa09-852d03a13e7b)

but we will create a new file(local file)  and the exisitant one stay as it is 

this is our splunk folder to push this to the servr (application,security ,system,sysmon)
![image](https://github.com/user-attachments/assets/4f2fd0e6-a356-4c28-994d-227c3abfb18a)
save as inputs.conf 
![image](https://github.com/user-attachments/assets/48b3d61c-07e1-4d28-a319-2804b8f1a8ae)

![image](https://github.com/user-attachments/assets/e471c903-dd69-451b-b891-6e219912a9d5)

![image](https://github.com/user-attachments/assets/a4d4529a-4eb6-48a9-a714-0ae43b3f86a2)

![image](https://github.com/user-attachments/assets/8e9e3fc2-d4b1-40e2-bdfa-83095b46bbe0)

sysmon
![image](https://github.com/user-attachments/assets/26e0c7f3-8055-41bd-a567-feb2e0334031)

![image](https://github.com/user-attachments/assets/b7f100ad-0bd8-4683-8bef-d920643b62e3)

## cinfig splunk endpoint 
![image](https://github.com/user-attachments/assets/aa22b92e-8051-445c-8cdc-2e52c36e765d)

![image](https://github.com/user-attachments/assets/c1cb98a5-9ab3-45df-a57a-816284ec3d6a)

![image](https://github.com/user-attachments/assets/99316d91-3006-4d10-8321-e0a7e0205ba9)

## enable splunk server to receive data 
![image](https://github.com/user-attachments/assets/48e7c83c-cf87-4d84-826f-030f7bffe741)

![image](https://github.com/user-attachments/assets/dd8451e6-f463-41d8-ad18-3af1039e6871)

![image](https://github.com/user-attachments/assets/e842315e-956d-4bc0-8daa-4bb088181f91)


![image](https://github.com/user-attachments/assets/c2da0be7-7f5c-41ca-a4bf-d91a622f53e8)

![image](https://github.com/user-attachments/assets/237fb31d-e575-4abb-b847-7e95c63df5ce)


![image](https://github.com/user-attachments/assets/3388e1ec-044d-4c63-b795-d2eb806b6d84)

## we will add also AD stay tunned ! 
##### same step to installation 
username splunk in AD : AD

![image](https://github.com/user-attachments/assets/d1e942cc-429b-4436-8a4a-f7497e3fd363)
## 2 hosts added 

![image](https://github.com/user-attachments/assets/f28424a3-b50c-401e-b764-dbcda53a81fd)

## add 
![image](https://github.com/user-attachments/assets/df84386e-daa2-4f24-b3d8-ad1cb1d35ad1)

![image](https://github.com/user-attachments/assets/1854d2b2-6b2f-4b6d-b589-bd9606129137)
## add new forest (new domain ) 
![image](https://github.com/user-attachments/assets/8ca98d02-7170-46f8-adda-643ab1a5aafa)

![image](https://github.com/user-attachments/assets/ebb72567-baa2-430d-bbf8-3bcfc507bdd7)

## add organization of BTS AND BTP AND add user
![image](https://github.com/user-attachments/assets/786d142c-f91c-4921-b91b-5e2f202e73b5)
## add win10 
#### pointed at our domain controller 

![image](https://github.com/user-attachments/assets/ba3af466-a13d-4724-95f8-8d317ed352dc)

![image](https://github.com/user-attachments/assets/c874b808-060d-4f2c-bdc9-0d1fd71ed306)
#### added user to the daomain 
![image](https://github.com/user-attachments/assets/8a941d78-0655-4a82-8c6c-bc77a88585f4)
## attack similation  brute force 
![image](https://github.com/user-attachments/assets/90b016d2-d3b3-401a-a7ab-b1948cf65990)
#### enable remote desktop for two user
![image](https://github.com/user-attachments/assets/59721b7e-dd6f-452a-94f1-7bb4a60a8d9d)
#### rdp = remote desktop protocol 
![image](https://github.com/user-attachments/assets/d76141bd-4125-4124-8801-f4ec1cb786dc)

![image](https://github.com/user-attachments/assets/93f4b571-0a05-452c-a57b-bb8681be7277)

![image](https://github.com/user-attachments/assets/c3071158-93cf-42a4-ac15-79edcdf91734)

![image](https://github.com/user-attachments/assets/7ae1d986-6ce3-46db-b41c-5f4289f83969)

![image](https://github.com/user-attachments/assets/8c3348f1-81a5-4488-8aa0-26f751db7263)

![image](https://github.com/user-attachments/assets/c6aaece1-6251-4c51-803e-8b8f243d9991)

![image](https://github.com/user-attachments/assets/90b82ff1-b137-4dde-bfcd-66c43c19cbff)

#### info attacker
![image](https://github.com/user-attachments/assets/e9c402d7-1423-4c5b-9bdc-f104b3794239)

![image](https://github.com/user-attachments/assets/03bd89bf-70f1-45dd-812e-88cdd3ae7b55)

## install ATM (atomic red team ) 
![image](https://github.com/user-attachments/assets/3761192f-7d56-483d-856b-a800b4c303b9)

![image](https://github.com/user-attachments/assets/523876d0-4e41-4825-b909-955614bccd09)

![image](https://github.com/user-attachments/assets/420e32e3-bcc3-4857-84f9-2650ac375537)

![image](https://github.com/user-attachments/assets/9bf1a604-9f6e-40a6-88a8-10894e37296d)
## atomic test 
#### technique id (MITRE|ATT&CK)

![image](https://github.com/user-attachments/assets/c595536c-adb5-405b-9702-3793712d206d)

 #### generate telemtry based on local account 
 
![image](https://github.com/user-attachments/assets/f54194e7-1ea8-4ec7-8831-15154b5117ef)

#### search fo newlocaluser

![image](https://github.com/user-attachments/assets/674fae81-9aef-4285-aa2f-491ac559e7a5)

#### detection localy 

![image](https://github.com/user-attachments/assets/970cc4ac-14e5-4d0f-a8a4-3291f7eb5d5f)

![image](https://github.com/user-attachments/assets/9daf1680-26ca-463b-841a-a21ab9b39aa1)

![image](https://github.com/user-attachments/assets/2a981cab-a74a-4196-bd8e-bee7e70479bf)
