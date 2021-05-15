---
layout: essay
type: essay
title: Assignment 3 Retrospective Blog
date: 2021-05-14
labels:
  - Software Engineering
  - Learning
  - Assignment3
---
**Briefly describe your system:**

My Assignment3 is a web application/eCommerce website that sells products related to the Pokemon Trading Card Game. These products include a variety of cards, "Premium Collection" boxes, and "Elite Trainer" boxes.


**Any notable shortcomings, bugs, problems, or additional features not implemented?**

Though I was able to remove products from the cart with a button built into the cart, I could not fully figure out how to apply that same effect to clear a cart after the user logged out. I would have liked to make the process a little more automated, but at the end of the day, I decided to stick with a system for logout that was working for the most part.


**Describe what you are most proud of about your system:**

I am most proud of the UI design of my website. I spent a fair bit of time playing around with .css in order to create what I believe to be an aesthetic website. In utilizing tutorials from w3 schools, I was able to create a really nice navbar, and some of the "visual effects" that I learned about near the beginning of class also came in handy. I think that in general, my site is fairly easy to navigate and self-explanatory.


**Describe what you are least happy with your system:**

I wanted to build up my log-out system a bit more. At the moment, the /logout feature does its job fair enough (it logs you out), but I probably could have tied it to a button rather than an HTML a tag. There are also some shortcuts I probably could have taken with repeating functions, like isNonNegInt or getCookie, so I would not have to copy and paste them each time I needed it.


**How was developing this assignment different than assignment #2?**

Developing Assignment3 took a lot more time than Assignment2 to complete, and it was far more intensive for me. I spent around 30 solid hours in total on the Assignment. However, my newfound knowledge/greater experience with the many shortcuts and all-around quality of life features provided by VSCode made the actual time it took to "write" code faster. In developing this Assignment3, I also tried to take into account the feedback I received from Assignment2 and made sure to test the registration and related user_data.json permissions on the class server.


**When you ran into a problem, what did you do to address it?**

When I ran into a problem I first looked at the outputs in the console, as well as any suggestions by the debugging tools of VSCode. Most of the time I could fix the issue, (the error reference at line x (x representing a number) helped a lot), but other times, I spent a lot of time trying (and failing) to fix an issue. When I reached a point of spending too much time trying to solve a problem, I tried looking on online resources such as w3schools/resource, Mozilla developer network, and stack overflow. Sometimes, I found something that worked well for what I needed. In other cases, I asked classmates for help (inside/outside of class).


**Describe what worked well in doing this assignment?**

I think that my genuine passion for pokemon cards incentivized me to really put an effort into making Assignment3 (in my eyes) a respectable site for the sale of Pokemon cards and related Pokemon card products. In building upon the experience of the past 15 or so weeks, I was able to improve the functionality of some existing features from Assignment2 and add new features that improved user experience (e.g. telling the user if they are logged in, how many products are in the cart, removing some minor redundancies, etc.).


**Describe what did not work well in doing this assignment?**

I spent a long time testing out ways to display the final invoice to the user, and I had quite a few "error" messages scattered across my web pages that I had to "iron out." Of these errors, it was often errors where something where a function would not work or some kind of variable was undefined. It proved challenging to keep track of all of the variable names, so I tried to standardize some by modeling most functions/variables related to function in accordance with the "camelcase" format, while the app.post functions were label like URLs (e.g. /process_login). In other cases, I modeled the formatting after an example that I found from an online resource like w3schools/w3resource or the node module website (e.g. nodemailer).


**What did you learn from doing this assignment?**

From this assignment, I learned that there are a lot of great resources on the web for programmers and that VSCode offers a lot of shortcuts/quality of life features that are great to utilize. This may seem minor, but the "suggestions" that show up when type a line of code or function save an incredible amount of time on coding. I thought that you had to "click" on the suggestion at first, but then I learned that you can hit the "TAB" key to "write" previously referenced variables/functions. I found my coding to be much faster and efficient as a result of this. I also think that I've become fairly adept at using the find and replace tool. The find tool; for finding a line of code that was hiding in my server.js, and the replace tool; for standardizing variable names. I was aware of the old saying "two heads are greater than one," but I did not fully realize or appreciate what could be accomplished with the minds of classmates, or the (thousands?) of minds of online contributors.


**If you could go back in time and do things differently, what would you change?**

If I could go back in time and do things differently, I probably would have looked for help earlier. Whether this manifested in a classmate or online resource, I feel that my insistence on "figuring things out on my own" became detrimental to my workflow/motivation after a certain amount of time had elapsed (e.g. spending a whole 3 hours trying to figure out how to "carry over". It is valuable to learn from trial and error, but after a few hours of being stuck on one problem, it just becomes miserable. When I finally figured out the solution to a problem I was having (often very simple) it was as if a huge weight was lifted off my shoulders, giving me that little bit of motivation I needed to keep on coding.


**Estimate the % of time you spent (a) thinking about how to do something, (b) writing code (but do not include testing, (c) testing and debugging**

Thinking about how to do something: I spent about 25% of my time on planning and research (i.e. setting up my checkpoint plan (that I ended up changing a lot in the final product), searching the web for resources like w3schools/resource, Mozilla developer network, and stack overflow).

Writing code: I spent approximately 15% of my time on the project writing code. I spent much longer "fixing" my code than I did just writing a function or line.

Testing and debugging: I estimate that I spent about 60% of my time testing and debugging. Though I spent a lot of time on the other parts of the assignment, I just happened to spend a greater amount of time on testing and debugging my application.


**Assign an estimated percentage on the amount each team member contributed to the assignment (including yourself) and explain briefly your rationale for the percentage breakdown. Be sure to include an overview of what specifically you and your partners contributed (e.g. “I worked on the security and my partner 1 worked on personalization”)**

I worked on Assignment3 individually. Like Assignment2 however, I talked with some of my classmates, like Noah Kim or Kimberly Matutina, and was able to get ideas/insight into how to accomplish certain tasks. I also sometimes referenced online resources like the aforementioned w3schools/resource, Mozilla developer network, and stack overflow, which I found to be helpful in building my application as well.

