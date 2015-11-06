## 1. Navigate to the XD [Login page](http://demo.crossdeck.us/crossdeck/login) (completed)

### 1.1. Test the Email input box
#### 1.1.1. input-email: "admin.com" --> click [log in]  
Response: "Email address in not valid"
#### 1.1.2. input-email: "admin@admin" --> click [log in] 
Response: "Email address in not valid"
#### 1.2.3. input-email: "mandy@hotmail.com" --> input-password: "1234" 
Response: pop up displaying "Email Address not found"
#### 1.2.4. input-email: "admin@admin.com" --> click [log in] 
Response: under the password box "Enter your password"

### 1.2. Test the Password input box
#### 1.2.1. input-password: "" --> click [log in]
Response: "Enter your password"
#### 1.2.2. input-password: "12" --> click [log in]
Response: "Password is not valid"
#### 1.2.3. input-password: "admin" --> input-email: "admin@admin.com" --> click [log in]
Response: succesful login to crossdeck
