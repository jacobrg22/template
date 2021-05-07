---
layout: essay
type: essay
title: Checkpoint Assignment 3
date: 2021-05-05
labels:
  - Software Engineering
  - Learning
---

**Develop a prototype of your entire application that addresses the following points:**

Here is my PPT prototype: https://drive.google.com/file/d/1Obf5lXl4TX5_SAM6nZ3GnqKwXUpBJ1Ld/view?usp=sharing

**Describe your design for your site’s shopping cart. That is, will it be a separate page that the user can view and edit, or will it be integrated into the product pages? If so, describe in detail how this will work on your site. Provide several examples of using the cart.**

The shopping cart will be a separate page that the user can interact with. After the user is satisfied with what they want to purchase, they can click on a button called "Go to Invoice." This button will take them to the login page, where they will need to login (or register if they have not created an account yet). After the login is validated, they will be redirected to the invoice, which they will be asked to review before confirming their purchase.

**Explain specifically how you will use sessions to manage your shopping cart. In particular, what shopping cart data will be stored in the session, what data format will be used (NOT what data type, but the format like with the data format used for your registration data). Use code examples showing what data structures (such as arrays and their objects) you will use to manage the shopping cart data and how they will be used in a session.**



**How will you avoid access to your application when the user has not logged in or registered? What are the particular security concerns you must address?**

I will build upon the if statement that I used for Assignment2. This will redirect the user if they are not logged in/associated with a user. I accomplished this by setting up an equality operator checking for username.

let params = (new URL(document.location)).searchParams;

if(params.has('username') == false) {
    alert("Oops! You are supposed to be here! Please login or register first before making a purchase!");
    window.location.replace('./index.html');
}

**Upon a successful login, how do you provide personalization in your UI? Explain how you did or will do this (paste code if necessary)**



**If you are working with partners, how will you split up the work in your team so that you are working in parallel as effectively as possible? That is, who is doing what and when?**

I will not be working with a partner for this project, but I suspect that I will be asking for help if I run into any issues.

**How are you approaching Assignment 3 differently than Assignment 2?**

For Assigment 3, 
