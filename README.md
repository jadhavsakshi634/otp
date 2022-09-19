# OTP ( one time password)

INTRODUCTION
most web applications need an otp ( one time password)or secure code to validate their users this package allows you to send/resend and validate otp for users authenication with users friendly method


USAGE 
You need addtional tool to create otp and send sms the module only takes care of the verfication part you can take a look at,the opt generator module to create  otp for users 


VERIFICATION PROCESS
OTP verficaton is done in the following steps
a hash is created with the phone number/emails adresses and then sent to te users
the users also recevies OTPvia sms  or emails or any other method 
the users send back the hash,OTP and the phone/emails used in the first request 
the server verify ther information if they true thren its match


