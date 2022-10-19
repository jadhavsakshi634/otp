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







flipkart-Web-Scraping-using-python
Basically it contains code and procedures of how we can scrap any web and get tons of information. It is easy to understand. You should include two python linraries while working with it

BEAUTIFUL SOUP
Beautiful Soup is a Python library for pulling data out of HTML and XML files. It works with your favorite parser to provide idiomatic ways of navigating, searching, and modifying the parse tree. It commonly saves programmers hours or days of work.

from bs4 import BeautifulSoup

REQUEST Requests is a Python HTTP library, released under the Apache2 License. The goal of the project is to make HTTP requests simpler and more human-friendly


How to scrap data form flipkart 
we need to follow certain steps for data extraction 
1.Importing necessary libraries like Beautiful Soup, requests,Pandas,ect.
2.Find product link we want to extract.
3.Inspect the page ,we need to specify the content variable from html which we want to extract.
4.writing code for scraping.
5.store the result in desired format.
