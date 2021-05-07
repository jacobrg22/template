---
layout: essay
type: essay
title: Reflecting on Assignment 2 Technical Essay
date: 2021-05-01
labels:
  - Software Engineering
  - Learning
---
**Provide a brief introduction to the assignment along with a link to this page for further details.**

For Assignment2, I had to update the website that I worked on for Assignment1 by setting up a login and registration system, and providing a personalized experience for users (see further details: https://dport96.github.io/ITM352/morea/150.Assignment2/experience-Assignment2.html, https://dport96.github.io/ITM352/morea/150.Assignment2/experience-Assignment2_retrospective.html).

To this end, I built upon the framework I had established in Assignment1, and developed the server to make use of POST and my /process functions. I used query string to keep the information inputted between pages and set up a login and registration system for my website. See the code for my Assignment here: https://github.com/jacobrg22/ITM352_S21_repo/tree/main/Graham_Jacob_Assignment2.

**What did you learn from this assignment?**

I learned a lot, though not all of it relating to programming. I learned how to be more efficient in my coding (shortcuts, and macros), which I believe will be valuable for my Assignment3. I had an idea of how to use the query string from our in-class labs, but I did not fully realize its application until I tried it out (messing around with code and experimenting). I learned that a query string is probably not the most ideal way to keep track of information, as it is hard to keep track of all the information across the pages code-wise. Importantly, I learned that there is no shame in asking for help. Whether this helps manifests through online resources like w3 or classmates, they can sometimes give you that little push to help you over that hurdle you've been stuck on for the past few hours or so.

**Did you work with a partner? Assign an estimated percentage on the amount each team member contributed to the assignment (including yourself).**

I did not work with a partner, but I did ask my classmate, Noah Kim for help on the processing of the login and registration forms.

**How did you get help when you needed it? What did you need help with?**

I had trouble making the functions for processing login and registration. After extensive experimentation, I decided to ask my classmate, Noah Kim, for help. He provided some guidance on the functions and gave me the ideas I needed to set up the /process_login and /process_registration on my server. I also struggled with setting up the validation (character limit/character restrictions/format), and so I looked at w3 examples as a basis for the character/email limitations test on my server.js. 

UPDATE 5/6/21: After receiving feedback for Assignment2, I asked Prof. Dan Port about an file access permission issue related to Cyberduck. After an exchange of emails, the issue was able to be resolved. By default my user_data.json did not allwo others to write to the file, which was causing an abrupt termination. I also asked my classmate Kimberly Matutina for help on displaying the email on the invoice pages. With a few additions, including requesting the query, I was able to sucessfully display the name and email to the user.

**How was developing this assignment different than assignment #1?**

Developing this assignment was more "intense" than Assigment1. By this, I mean that I had to really think about how I would accomplish my tasks. Since I decided to handle a lot of validation, as well as the login/registration system on the server, I had to spend a ton of time debugging the code (as I was adding a fair bit of new functions and I had to keep track of where the data inputted in the forms were going across pages). At some point, I was getting really stressed because my web application was not showing (as in, the background loaded but none of the products or UI loaded) and there were no errors in the console (it turned out to be a UI feature messing up the loop to load products). Whereas Assignment1 entailed mostly modification from the Labs, Assignment2 entailed writing entirely new liens of code and thinking on what type of function would help me accomplish my tasks best.

**Estimate the % of time you spent (a) thinking about how to do something, (b) writing code (but do not include testing, (c) testing and debugging**

a) I estimate that I spent about 25% of my time thinking about what code I could use to accomplish my tasks (and when that code did not work, what else I could use to accomplish my tasks).

b) I spent 25% of my time on coding.

c) I spent 50% of my time testing and debugging my code.

**Describe what worked well with this project? What did not work well?**

For this project, I would say that I handled time management well. I was able to submit Assignment2 on time, without too much crunch. The assignment itself, however, was quite stressful. I probably should have taken more breaks in between coding and debugging, rather than trying to fix an issue in one session. My main concern was that if I took a break, I would forget what I was working on/what problem I was having.

**If you could go back in time and do things differently, what would you do differently?**

If I could go back in time and do things differently, I would not wait as long to ask for help. The time that I spent trying to figure out something on my own was valuable, but it also made me more stressed. When I used additional resources like w3 or a classmate, it was like a veil and lifted, and I could see clearly.
