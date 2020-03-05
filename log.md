# 100 Days Of Code - Log

### Day 0: February 21, 2020

**Today's Progress**: Reading O'Reilly Head first python book. Learning about lists and how you can append lists and use loops

**Thoughts:** Very fun to have something to do when I get home. I'm listening to the Atomic Habits audiobook about how habits are formed and I hope that it will help me keep doing this in the future.

### Day 1: February 22, 2020

**Today's Progress**: Finished the chapter on lists. Now I'm starting to get introduced to Dictionaries. 

**Thoughts:** Still a lot of fun! Got a little stuck on one of the problems I was to solve. Turns out I only misunderstood how to go about solving it.
One think that I hope helps is that I'm listening to Atomic Habits by James Clear, and getting familiar with how habits form.
So I've made some rules, and also try to change how I approach programming.
One of the rules is that when I sit down infront of the computer, I have to code (or read a course/text book about coding) for atleast 10 minutes before doing anything else.
Another rule is that when I get home from work, I will also code for atleast, hopefully more, for 10 minutes.
I also try to approach that every day I want to improve my skills in programming. I want to learn every day something about programming or getting more knowledgeable about programming.

### Day 2: February 23, 2020

**Today's Progress**: Finished chapter on dictionaries, and other type of structured data (like sets, and tuples). Started chapter on functions.

**Thoughts**: This one I look forward to learning, so I don't have to keep all my code in one single place.
A side-note: Re-arranged my desk, added a second monitor, and rotated both of them to portrait mode so I know that when I sit infront of the computer, I'm supposed to be programming. This also helped since I can use the second monitor to have the pdf of the book I'm reading open and don't have to rely on my ipad (which has a smaller screen).

### Day 3: February 24, 2020

**Today's Progress**: Finished chapter on functions and modules. Learning now how to make simple webapps.

**Thoughts**: Starting to see the point of learning a little day after day. Now I get to see some graphical stuff on my screen other than that in the IDE (although it´s very simple stuff, it's still progress). It's going to be a lot of fun to see how much I can do in a week, or better yet, month or longer :).

### Day 4: February 25 2020

**Today's Progress**: Finished chapter on webapps. Made a simple site that compares two strings and shows the common letters. Besides the book I'm reading, I decided to learn about how git works (the basics). Also trying to make a simple site that you can create a "account" with username and password and store it in a txt file, and later when you try to login see if it's correct.

**Thoughts**: Trying out this side project on my own and will see if I know enough that I can make it and figure it out. Might spend some time on it tomorrow and if it's a dead end and I have no idea on where to go, I'll continue with the python book im reading.
Also I don't think I need to use git now, for what I'm doing, but thought I would atleast learn the basics so I get into the habit of commiting stuff here so when I do need it, I know the most basic stuff atleast.

### Day 5: February 26, 2020

**Today's Progress**: Continued on webapps and how to write to files.

**Thoughts**: Have been exersising every day at work since it's "sportlov" (rough translation: sport week, or exercise week. A week in sweden when (at least schools) are closed and you're encouraged to engage in sport activities.) Have been programming the other days as soon as I get home even though we have exersiced, today I had to rest for two hours before I started coding. So I havn't done as much as usual, but atleast I have my minimum 1 hour done (that is pure coding, according to wakatime (https://wakatime.com/dashboard )) but that doesn't account for the time I spend reading the book I'm learning from.
Nevertheless, will finish this chapter and then see if I can make any progress on my personal project.

### Day 6: February 27, 2020

**Today's Progress**: Worked on the webapp, made the results readable in a HTML table

**Thoughts**: Last day of this week's "sportlov". Got the last exercise done for this chapter in Head First into python. Will spend more time on my personal project tomorrow. Don't know if I need to learn more about Jinja2 or html if I'm going to be able to make the site I want. Think it's kind of fun with html/css, but think I should focus more on python. Don't know since I'm so new to python that I should learn more about html/css before learning more basic programming skills. Have tinkered with html/css in the past but was a few years ago.
Will have to sleep on it and see if I can figure something out.

### Day 7: February 28, 2020

**Today's Progress**: Good progress on my personal project. The account creation part is done (I think), will work on the login stuff

**Thoughts**: Proud of today. Got the site to store the username/password in a textfile, and I import that to a dictionary when it starts. It also updates the textfile and dictionary when a new user is added. 
But I want the status_page function to show if both if the login is successfull and if the account creation is successfull. I could use a seperate for the login, and maybe that makes sense. Found a method in flask called referrer but that gets me the value of the entire url. I just want the last part. Could split it, but.. Just thought of something, if I do split it by '/', and look at the last listpart list[-1].. That should get me the last url bit.
*Quick edit*: Decided against the last part. It became to many if's, so I think it looks better to have seperate functions for the create and login status page.

### Day 8: February 29, 2020

**Today's Progress**: Learned about databases (mysql/mariadb) and classes.

**Thoughts**: Smooth day. Just trying to find a new project to play with. Thought it was a lot of fun with databases and classes, can see myself playing around a lot with those. Should probably get to know databases a bit better. Still searching for idea's on what to work on..
But a very good day non-the-less!

### Day 9: March 1, 2020

**Today's Progress**: Played around with databases in python. Also some css

**Thoughts**: In the past I have tried programming in small burst but was never that serious. But I do remember a little bit in how to think. But never used databases so that part is completely new to me. Always wanted to learn it because you can do cool stuff with it IMO. So trying to get a better grasp on that.
Also played around with css so I can get this new/upgraded site to look somewhat 'OK'.

### Day 10: March 2, 2020

**Today's Progress**: Worked with the database for my project (ran into some issues that's now resolved). Also did a 'roadmap' for this project (link below)

**Thoughts**: Ran into some issues with the database when I tried to check if the username was already taken. The issue was that I had already multiple users with the same name. I googled and found out that this could be resolved if you used the username as the primary key (or something along those line) instead of the id that's given in the order a user is created. Figured I could use that as a solution in future projects, but wanted to play around with the database and see how I could compare values and such. It was resolved once I deleted the other users with the same name, so my previous tries to get it to work might have worked (some of them atleast).

**Link to roadmap**: https://pbs.twimg.com/media/ESIDtfxXYAA38Al?format=jpg&name=large

### Day 11: March 3, 2020

**Today's Progress**: Finished the create user/login part (I thought). Then got introduced to sessions from the python book. So will need to implement that. Played around with the css/html.

**Thoughts**: The session part made a lot of sense. Had thought of how I would solve too see if a user is logged in, and this solves that pretty easy (I think, haven't finished the chapter yet..). Tweaked the css/html a little.


### Day 12: March 4, 2020

**Today's Progress**: Learned how to create my own decorators in python. That took some serious thinking before it clicked. (still some confusion but understand the big picture.. I think)

**Thoughts**: As I said, had to think long and hard before I understood creating my own decorators.. Writing it down on my ipad might have helped, so I didn't have to keep it all in the head.
Now I'm going to play around with flask-bootstrap and see if I can make my site even prettier!


### Day 13: March 5, 2020

**Today's Progress**: Struggled with bootstrap and how it was suppose to work and how I was supposed to manage it. Didn't get it, will continue to work with basic css/html until I give it another shot.

**Thoughts**: After a few hours I gave up in trying to use bootstrap. Played around with it yesterday evening after I wrote that post, and when I came home from work today. But for now I will rely on my basic css/html knowledge and continue learning python. But didn't get much learning done, or programming outside of trying to understand bootstrap, so will add another day to the 100 days.

### Day #: Month Date, Year

**Today's Progress**: 

**Thoughts**: 

**Link(s) to work**: 

