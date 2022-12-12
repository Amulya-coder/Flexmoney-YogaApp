# Flexmoney Yoga App 🧘‍♀️

## Website is hosted on [Netlify](https://steady-pegasus-16cfe0.netlify.app/)

### 📌 The project is divided into two sections
1. Registration form
2. Payment

### 📌 Registration form
1. User need to add the name
2. User need to add the age b/w 18 - 65 to register on the app
3. After successfull registration it displays the message.
#### Note: Please wait for some time after registering it displays the pop up the server might take some time to respnd 

### 📌 Payment Page
1. User have to enter the registered email id
2. User need to select the batch timings as per their convenience
3. User need to click on the pay button to pay the amount of INR.500
4. After successful payment,  a confirmation message will be displayed
#### Note: Please wait for some time after payment it displays the pop up the server might take some time to respnd 

### 📌 Database 
After successful payment user data is stored in the mongodb database like Name, email, age, batch, gender etc 

### 📌 ER-Diagram
![ER_YogaApp](https://user-images.githubusercontent.com/66437295/207140066-c2b61c78-7f22-47c9-bbf4-2a6aa8d2682a.jpg)

### 📌 Screenshots
### Registration
![Reg1](https://user-images.githubusercontent.com/66437295/207146175-97c2ddfd-c088-4ab4-9915-b1e6304f630c.png)
### Payment
![Reg2](https://user-images.githubusercontent.com/66437295/207146256-99db018f-5813-482a-8436-6060f6cc8a29.png)

### Assumptions
- First you have to register there is no need of login.
- Only Registered Users can pay the fees.
- Payment information is not stored in the app.
- You cannot update the information.
- Each field in the registration form going through validation 
