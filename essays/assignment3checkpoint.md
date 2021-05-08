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

And here is a short clip describing my plans for Assignment3: https://youtu.be/wXCSt-IUhZY


**Describe your design for your site’s shopping cart. That is, will it be a separate page that the user can view and edit, or will it be integrated into the product pages? If so, describe in detail how this will work on your site. Provide several examples of using the cart.**

The shopping cart will be a separate page that the user can interact with. After the user is satisfied with what they want to purchase, they can click on a button called "Go to Invoice." This button will take them to the login page, where they will need to login (or register if they have not created an account yet). After the login is validated, they will be redirected to the invoice, which they will be asked to review before confirming their purchase.


**Explain specifically how you will use sessions to manage your shopping cart. In particular, what shopping cart data will be stored in the session, what data format will be used (NOT what data type, but the format like with the data format used for your registration data). Use code examples showing what data structures (such as arrays and their objects) you will use to manage the shopping cart data and how they will be used in a session.**

I will be storing data related to the products and quantity as part of a session in order to manage my shopping cart.

//  var products_data;

//  loadJSON('get_products_data', function (res) {

//      products_data = JSON.parse(res);

//  });

//  loadJSON('get_cart', function (res) {

//      shopping_cart = JSON.parse(res);

//  });


**How will you avoid access to your application when the user has not logged in or registered? What are the particular security concerns you must address?**

I will build upon the if statement that I used for Assignment2. This will redirect the user if they are not logged in/associated with a user. I accomplished this by setting up an equality operator checking for username. If the user is not logged in, they should be redirected back to the homepage (index.html).

//  let params = (new URL(document.location)).searchParams;

//  if(params.has('username') == false) {

//      alert("Oops! You are supposed to be here! Please login or register first before making a purchase!");

//      window.location.replace('./index.html');

//  }


**Upon a successful login, how do you provide personalization in your UI? Explain how you did or will do this (paste code if necessary)**

Upon a successful login, I will provide a greeting (something like “hello John Smith” and note that an invoice will be sent to the email address associated with the user, which in this case would be “johnsmith@gmail.com.)” These personalized messages should follow the user up to order confirmation (fin.html).

Under invoice.html:

//    if (name !='undefined' && name !='') {

//        document.write (Hello, ${name}! Please review your invoice below.)

//    }

//    else {

//      document.write()

//    }

//    document.write(An invoice will be sent to ${params.get('email')}.);

Under fin.html:

//    document.write (<p>Hello, ${name}! Thank you for shopping at Jacob's Pokemon Card Shop! An invoice has been sent to ${params.get('email')}.)


**If you are working with partners, how will you split up the work in your team so that you are working in parallel as effectively as possible? That is, who is doing what and when?**

I will not be working with a partner for this project, but I will be asking for help if I run into any issues.


**How are you approaching Assignment 3 differently than Assignment 2?**

For Assignment 3, I decided to take a more holistic approach. By this, I mean that the first steps related to working on Assignment concerned a lot more conceptual work than Assignment2 and certainly more conceptual work than Asignment1. Beyond just the work done for the Assignment3 checkpoint, my work on Assignment3 entailed some additional planning and experimented on how the different pages would interact with each other. After talking with my classmates and seeing their work with a navbar, I got ideas and tried to think of a way that I could incorporate it in a way that works, both functionally and aesthetically for my store website. I also began work on Assignment3 immediately after I submitted Assignment2, which is in contrast to Assignment2, which I began work on a few days/a week after I finished working on Assignment1. So far, I do not know whether this decision was good/effective, as though I have been able to accomplish much more for Assignment3, I also had to incorporate several fixes I made to Assignment2 after getting feedback. This entailed rewriting some code for Assignment3 to bring it in line with the fixes made for Assignment2.
