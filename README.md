# Christmas List Management App
This project is a Christmas themed shopping list with a built-in Christmas countdown and Christmas music player! This application helps you keep track of what you need to buy for friends and family for Christmas.

![alt tag](https://i.imgur.com/mINXdcw.jpg)
![alt tag](https://i.imgur.com/Dgut7ov.jpg)


## How It's Made:

**Tech used:** HTML, CSS, JavaScript, MongoDB, using the MVC Architecture

This is a simple ToDo App remade into a lovely Christmas shopping list. Built using the MVC Architecture with authorization so folx can sign up to track what they have to buy before Christmas! We created the Christmas theme through ejs and CSS, embed Christmas music into the page, and implemented a Christmas countdown timer. On the list page, we added a feature to sort the current list by the recipient's name in alphabetical/reverse alphabetical order. 

We also implemented a password reset feature, where the user can request an email to the address on file in the database and follow the link to reset their password. We used bcrypt and crypto to create and hash a token added to the user model, then nodemailer to send an email to the user with the link to reset their password, and finally authenticated the user based on the token to reset the password in the database. 

## Optimizations

Some features to add can include:
-  adding more features to list organization (i.e. if name is included, prompting the user to add multiple gifts to the same person), 
- shareable private lists for users without an account to see, 
- wishlists for the logged-in user to share. 

## Contributors

 - Cheri#6412 - [Priscilla De Los Santos](https://github.com/pndelossantos)
 - emlegweak#4361 - [Emily Armstrong](https://github.com/emlegweak)
 - ladynazlia#5716 - [Amanda Faulkenberry](https://github.com/LadyNazlia)
 - ZRT#1448 - [Ryan Warren](https://github.com/ZRTAssassin)
 - S_Katana#1955 - [Steven Ong](https://github.com/ong-stev)
 - adamspersonald#3432 - [Adam (Stein Beals)](https://github.com/adamspersonaldeveloping)
