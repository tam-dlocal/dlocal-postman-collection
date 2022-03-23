# Prepare your environment 
**Download Postman Collection**

**How to download**

1. Click on Code and then click on download ZIP


![Alt text](https://github.com/tam-dLocal/Images-for-Readme/blob/main/readme1.png "Optional title")

**Import your collection**
1. Open Postman
2. Click on Import

![Alt text](https://github.com/tam-dLocal/Images-for-Readme/blob/main/readme2.png "Optional title")

3. Click ok to Upload Files and select the files previously downloaded 

![Alt text](https://github.com/tam-dLocal/Images-for-Readme/blob/main/readme3png.png "Optional title")

4. Click on Import

![Alt text](https://github.com/tam-dLocal/Images-for-Readme/blob/main/readme4.png "Optional title")

# Setup your environments 
**Payins**

Once you have imported the Postman Collection and Payins and Payouts Environment 
1. Once these files are imported click on Environments and select Sandbox Payins

![Alt text](https://github.com/tam-dLocal/Images-for-Readme/blob/main/readme5.png "Optional title")

2. In current value column insert the following values and click on Save button 

   a. Host: https://sandbox.dlocal.com 

   b. X-Login: insert x_login value from https://dashboard.dlocal.com/ 

   c. X-Trans-Key: insert x_trans_key value from https://dashboard.dlocal.com/ 

   d. Secretkey: insert Secret Key value from https://dashboard.dlocal.com/

**Payouts**

1. Once this files are imported click on Environments and select Sandbox Payouts 

![Alt text](https://github.com/tam-dLocal/Images-for-Readme/blob/main/readme6.png "Optional title")

2. In current value column insert the following values and click on Save button 

   a. Host: https://sandbox.dlocal.com 
   
   b. X-Login: insert Cash Out x_login value from https://dashboard.dlocal.com/
   
   c. X-Trans-Key: insert Cash Out x_trans_key value from https://dashboard.dlocal.com/
   
   d. Secretkey: insert Cash Out Secret Key value from https://dashboard.dlocal.com/
   
   **Prepare your requests**
   
 1. Click on Collections and click on Postman-Collections to see all the requests 2. Here you can test all available requests. 

![Alt text](https://github.com/tam-dLocal/Images-for-Readme/blob/main/readme7.png "Optional title")

Here you can test all available requests. 

**Note: Be aware to select the correct environment. If you want to test Payins select Payins environment and if you want to test Payouts select Payouts environment**

![Alt text](https://github.com/tam-dLocal/Images-for-Readme/blob/main/readme8.png "Optional title")

**Smart Fields**

 1. For Payins using Smart Fields you need to generate your Smart Fields token [here](https://dlocal.github.io/smart-fields-examples/)

![Alt text](https://github.com/tam-dLocal/Images-for-Readme/blob/main/readme9.png "Optional title")
![Alt text](https://github.com/tam-dLocal/Images-for-Readme/blob/main/readme10.png "Optional title")

 2. Copy the generated token and paste it in the token value in card object

![Alt text](https://github.com/tam-dLocal/Images-for-Readme/blob/main/readme11png.png "Optional title")

