# Zeblok - Compuatational

Home Screen - https://computational-beta.zeblok.com/ \
{{URL}} - Production URL || localhost:3000

### Register User => 

Method : POST\
Path : {{URL}}/api/v1/auth/register\
Protection : Public\
Description : User submits the details like Fullname, EmailId, Password which comes as a part of the request. The Database is checked if the user details already exists or not, 

### Login User => 

Decription :

exports.login = asyncHandler(async (req, res, next) => { } )


Current LoggedIn User =>
 
Method : GET\
Path : {{URL}}/api/v1/auth/me\
Response : { "success" : "true", "user" : "user"}\
Protection : Private
 
### Forgot Password =>

Method : POST\
Path : {{URL}}/api/v1/auth/forgotpassword\
Data : { "email" : "user_email_id" }\
Response : { "success" : "true", "reset_token" : "reset_token"}\
Protection : Public

### Change Password =>

Method : PUT\
Path : {{URL}}/api/v1/auth/resetpassword/:resetToken\
Data : { "Password" : "user_new_password" }\
Response : { "success" : "true", "message": "password updated successfully."}\
Protection : Private

### Check Invite =>

Method : POST\
Path : {{URL}}/api/v1/auth/checkinvite\
Response : {
    success: true,
    data: {
      organisationId: org._id,
      organisationName: org.name,
      email: data[1]
    }
  }\
Protection : Private

### Activate User Account =>

Method : GET\
Path : {{URL}}/api/v1/auth/active/:emailActivationToken\
Response : Redirect from mail link to "{{URL}}/welcome/{{user}}"\
Protection : Public

### Resend Email Token =>

Method : POST\
Path : {{URL}}/api/v1/auth/resendEmailToken\
Data : { "email" : "user_email" }\
Response : "Welcome to the Zeblok Computational AI Platform. Please check your email for an account activation link to complete your registration" alongwith Activation Link in User Email\
Protection : Public

### Check If Redirect After payment or not =>

Method : POST\
Path : {{URL}}/api/v1/spawnedImages/redirectCheck\
Data : { "email" : "user_email_id" }\
Response : { "success" : "true", "reset_token" : "reset_token"}\
Protection : Private

### Forgot Password =>

Method : POST\
Path : {{URL}}/api/v1/auth/forgotpassword\
Data : { "userId": "req.user.id", "dockerImageId": "req.body.dockerImageId", "planId": "req.body.planId" }\
Response : { success: spawnedImages.length >= plan.allowedNotebooks }\
Protection : Public

### Forgot Password =>

Method : POST\
Path : {{URL}}/api/v1/auth/forgotpassword\
Data : { "email" : "user_email_id" }\
Response : { "success" : "true", "reset_token" : "reset_token"}\
Protection : Public

### Forgot Password =>

Method : POST\
Path : {{URL}}/api/v1/auth/forgotpassword\
Data : { "email" : "user_email_id" }\
Response : { "success" : "true", "reset_token" : "reset_token"}\
Protection : Public

### Forgot Password =>

Method : POST\
Path : {{URL}}/api/v1/auth/forgotpassword\
Data : { "email" : "user_email_id" }\
Response : { "success" : "true", "reset_token" : "reset_token"}\
Protection : Public

### Forgot Password =>

Method : POST\
Path : {{URL}}/api/v1/auth/forgotpassword\
Data : { "email" : "user_email_id" }\
Response : { "success" : "true", "reset_token" : "reset_token"}\
Protection : Public

### Forgot Password =>

Method : POST\
Path : {{URL}}/api/v1/auth/forgotpassword\
Data : { "email" : "user_email_id" }\
Response : { "success" : "true", "reset_token" : "reset_token"}\
Protection : Public

### Forgot Password =>

Method : POST\
Path : {{URL}}/api/v1/auth/forgotpassword\
Data : { "email" : "user_email_id" }\
Response : { "success" : "true", "reset_token" : "reset_token"}\
Protection : Public

### Forgot Password =>

Method : POST\
Path : {{URL}}/api/v1/auth/forgotpassword\
Data : { "email" : "user_email_id" }\
Response : { "success" : "true", "reset_token" : "reset_token"}\
Protection : Public

### Forgot Password =>

Method : POST\
Path : {{URL}}/api/v1/auth/forgotpassword\
Data : { "email" : "user_email_id" }\
Response : { "success" : "true", "reset_token" : "reset_token"}\
Protection : Public

### Forgot Password =>

Method : POST\
Path : {{URL}}/api/v1/auth/forgotpassword\
Data : { "email" : "user_email_id" }\
Response : { "success" : "true", "reset_token" : "reset_token"}\
Protection : Public

### Forgot Password =>

Method : POST\
Path : {{URL}}/api/v1/auth/forgotpassword\
Data : { "email" : "user_email_id" }\
Response : { "success" : "true", "reset_token" : "reset_token"}\
Protection : Public

### Forgot Password =>

Method : POST\
Path : {{URL}}/api/v1/auth/forgotpassword\
Data : { "email" : "user_email_id" }\
Response : { "success" : "true", "reset_token" : "reset_token"}\
Protection : Public

### Forgot Password =>

Method : POST\
Path : {{URL}}/api/v1/auth/forgotpassword\
Data : { "email" : "user_email_id" }\
Response : { "success" : "true", "reset_token" : "reset_token"}\
Protection : Public
