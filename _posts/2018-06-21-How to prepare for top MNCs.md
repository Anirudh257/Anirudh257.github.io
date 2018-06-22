---
layout: post
title: "How to prepare for top MNCs"
date: 2018-06-21
---
This is the twelfth article on the website.

This post was residing in my draft for quite long. I finally got some time out of my busy schedule to refine it.
The first question quickly pops up on why am I writing this post at all. There are already tens of hundreds of similar compilations on web that talks about this.

Well, following reasons compelled me to do so:

1. Being a GFG moderator, I’ve been getting many requests from readers through various social media (FB, LinkedIn, Quora, InstaGuide) and various mail clients asking for mentorship and guidance on how to prepare for top MNCs like Microsoft, Amazon, Google etc
Having gone through similar journey and witnessing many of my friends succeeding, I feel knowledge should be shared. My experience might be useful for newer generations who happen to chase the same goal as once was mine.

2. Please note that this article is purely a reflection of my learnings, what I followed through the years and my experience. This is NOT the only way to improvise on what is needed – your coding skills, strengthening DS & Algorithms and boosting problem solving skills. I repeat, this is NOT the only way. There are things I couldn’t follow because of time constraints or didn’t follow because I was just not aware. Please comment if I missed anything which is worth mentioning here.

Language

Language has been a topic of debate between aspirants since years. It’s always good to master one language, knowing ins and out of it rather than hopping from one language to other. Why?  Because sometimes it might happen to you that when you get a problem, you start wondering what language you should choose and your focus is compromised. When you should really concentrate on problem solving, Implementation comes later. Then while you are coding, you plan to change the language in between. This won’t serve you good in interviews. If you’re able to solve a problem in language ‘X’, eventually you will also solve it in language ‘Y’. Learning a new language is just a matter of time. A language might not be as widely used after 5 years as it is being used now. Your ability to solve a problem will what matter in the long run.

I usually switch between C and C++. If time is at its crunch, I prefer to use STL (standard library functions) instead of writing my own version of Linked List. If I want to develop a project, an android app for instance, I go for a managed language because it is easier. If I want to automate something to save my time, like replying and liking my birthday wishes, a python script is the saving grace. You got the point, right? Master one language and learn others as per requirements.



Data Structures and Algorithms

Data Structures and Algorithms is very important and serves as the backbone of problem solving.

For beginners, <a href = "https://www.amazon.com/Fundamentals-Data-Structures-Ellis-Horowitz/dp/0929306406?SubscriptionId=AKIAILSHYYTFIVPWUY6Q&tag=duckduckgo-d-20&linkCode=xm2&camp=2025&creative=165953&creativeASIN=0929306406">Fundamentals of Data Structures in C by Sahni Horowitz is good</a>. After reading it, you should be able to understand basic Data Structures, how they are implemented and fewer examples where they can be used. Don’t expect to learn advanced DS through this. After your basic concepts are clear and you are comfortable implementing them in a language of your choice, you can work on learning algorithms and solving problems.

Many sites (including GeeksforGeeks) present problems in a very adhoc manner with no order of difficulty level. This makes things difficult for beginners because they don’t know the difficulty level of the problem they are attempting. <a href = "https://www.amazon.com/Data-Structures-Algorithms-Made-Easy/dp/819324527X/ref=sr_1_1?s=books&ie=UTF8&qid=1529638679&sr=1-1&keywords=data+structures+and+algorithms+made+easy+by+narasimha+karumanchi">Data Structures and Algorithms made easy by Narasimha Karumanchi</a> is a good read after you are comfortable with the basics. It has pretty good collection of problems organized by difficulty level. Just make sure to try to solve problems on your own instead of rushing for the solution. Once you have a fair understanding of DS and have got some confidence in solving problems, jump to online portals and start solving problems from topic of your choice. <a href = "https://www.geeksforgeeks.org/">GeeksforGeeks</a> is good to start with.

**For Algorithms, <a href = "https://www.amazon.com/Introduction-Algorithms-3rd-MIT-Press/dp/0262033844/ref=sr_1_3?s=books&ie=UTF8&qid=1529638793&sr=1-3&keywords=cormen+introduction+to+algorithms">Introduction to Algorithms</a> by Cormen is a must read.**

Advanced Data Structures

Sometimes, basic DS don’t serve the purpose to solve problems and you need to know advanced DS. Day to day problems like implementing a prefix based search for a phone contact list to finding the dictionary word from a jumbled sequence of characters need special kind of DS. There are many of them – TST, Trie, Suffix tree, Suffix array, Fibonacci heap, Segment tree, Gap buffer, Rope, Skip list, K Dimensional tree and so on. While it is good to know the implementation of these DS, I would suggest to also know when to use one.

Problem solving

So you got a gun, understand how to use it, probably have used it before. If you are going to fight a war, you won’t like to rely upon your amateur experience. You would prefer to practice hard to save your ass. Now try to think it in perspective of problem solving. You know what DS are. But you also need to know when to use one. Welcome to the world of problem solving. You are given a problem and you are asked to solve it. That problem can be anything starting from a simple puzzle to implementing a user scenario. You must have noticed degree of connection feature in LinkedIn. How will you implement it? Does your approach take care of scalability? Will your code crumble when user base increases ten folds? This is the most important skill top MNCs usually look for. How do you approach a problem? How do  you divide it into modules? How do you solve each of them and then combine them?

Dynamic Programming

I separated out DP because it is one monster which is difficult to master upon. No matter how many problems did you solve in the past, a new DP problem can always surprise you. The more you will practice, higher the chances will be to find out patterns. Google is peculiar about DP. You should expect at least one DP problem per interview round  if you are preparing for Google. Practice DP section from:

**<a href = "https://www.geeksforgeeks.org/category/dynamic-programming/">GeeksforGeeks – Dynamic Programming</a>
<a href = "https://www.topcoder.com/community/data-science/data-science-tutorials/dynamic-programming-from-novice-to-advanced/">TopCoder – Dynamic Programming – From Novice to Advanced</a>**

Competitive Programming

Competitive Programming plays a very important role in boosting problem solving skills and ability to perform under time pressure. Do participate in various online portals like TopCoder, CodeChef, SPOJ. Here is a post on Getting started in sport of programming.

Design and testing

So you are good in DS and Algos. You are probably good in problem solving as well and you come up with different approaches with varying time and space complexity. The problem which you solve in Competitive Programming is well defined and has to work under an environment which nobody will probably use. What if you are asked to implement a user scenario. The problem statement is usually vague and you need to discuss a lot to resolve ambiguities. This is where design comes into picture. How will you design a redo-undo feature? What data structures will you use to store history in a web browser? How will you implement auto-complete feature in address bar? Let’s say Amazon wants to build a feature that would resume a video stored in cloud from any device. What data structures will you use? How will you scale up things? Does your design take care of concurrency issues? What about the performance? What if you and your girlfriend share the same cloud account and are trying to play the same video from different devices?

Now you have thought through the design well, have come up with different data structures to use with pros and cons in mind. While implementing, you must take care of corner cases. You must be aware about the integer overflow issue in Youtube video view count. While implementing, they never really thought that the view count can exceed what an integer variable can hold and BOOM, the view count cycled back to zero.

Before a feature goes live, it must be tested well. It is good to practice some test questions as well. How will you test a Insert image feature in MS Word? What about a cut-copy-paste feature? How will you test Temple Run game? Try to write all the possible test cases and how you are going to handle this in your code. Writing a robust code is very important. If you take care of these things at an earlier stage, you can avoid silly bugs (and boost your chances of getting selected in interviews).

What else?

Have a sound understanding of Operating System. The dinosaur book by Galvin is a good read. Know how networking works and have insights on DBMS.

Resume building

First impression is the best. Resume is the first thing that HR will use to decide whether to call you for interview or not. And they have got hundreds of them. So they will usually scan it for 20 seconds to 2 minutes. It should be clean, concise and elegant. Each word mentioned should worth the space it eats. The rule of thumb is if you have less than one year of experience, the size of resume should not exceed a page (with few exceptions).

Few points to note:

1. Maintain a header to fit info like name, email id, address and contact number

2. Mention level of expertise corresponding to each language. Example: Proficient in C and good at Java

3. If you are mentioning a project, write your key learning, impact in the team and . If this project is online (an app), don’t forget to include the link. This will show that you built something that is being used by people . Guess what, this is what companies do, building a product, stabilizing it as per user feedback, taking in new feature requests and so on.

**<a href = "https://www.quora.com/What-are-common-mistakes-that-applicants-make-when-writing-their-resumes-for-tech-companies-mainly-for-software-engineering-positions/answer/Gayle-Laakmann-McDowell?ref=fb_page">Here are few useful tips from Gayle – What are common mistakes that applicants make when writing their resumes for tech companies?</a>**

How to apply for Microsoft?
I get many messages asking me for a favour to refer them. When I ask them how much comfortable they are with DS and Algos, they say good enough. Then I rephrase my question to how do they feel when they solve interview experiences at GeeksforGeeks. Either they haven’t heard of GeeksforGeeks or they never read. This is not a surprise. GeeksforGeeks is still growing. But when I ask them a problem on DS by tweaking already existing famous ones, all they say is they haven’t solved this problem before. Please do NOT do that. Dreaming is good, but it will come true only when you work towards making it a reality.

If you are not able to clear the interviews, you will have wait again for 6-12 months depending on the company policy before you can apply again. Now coming to the point,  you can apply for a position at Microsoft either through Careers page or through referral. Referral usually bumps chances of getting an interview call because your resume gets to the system through a person Microsoft trusts to be a good engineer. How do you ask for a referral? It’s simple. Forward your resume to someone you know working there. No one will say NO unless your resume is filled with something which doesn’t fit company requirements. Rule of thumb is we believe in solving problems and if you are good at it, we would love to see you here. Remember, everyone wants to work with a smart person. And this is usually true for any company, not just for Microsoft.

Do’s and Don’ts

1. Practice, practice and practice

2. Make a habit of writing clean and readable code (avoid variables names like i, j)

3. Make sure to handle all corner cases

4. Use pen and paper to practice code. In interviews you have NO access to a compiler

5. Don’t mug up the solutions. Try to solve on your own

6. Think of different ways of solving a problem and thoughts on why one should be preferred over the other

Resources

I have answered few questions related to interview preparation on Quora. You might find some content missing here in blog and it is intentional to avoid the duplication of efforts. Please read my technical answers here.

Resources (which I haven’t talked about):

 1. <a href ="https://www.amazon.com/Cracking-Coding-Interview-Programming-Questions/dp/0984782850/ref=sr_1_3?s=books&ie=UTF8&qid=1529639078&sr=1-3&keywords=cracking+the+coding+interview">Cracking the coding interview by Gayle Laakmann</a>: A must read once before interviews. It covers aspects like what interviewers expect from you, how to deal with behavioral questions and few interesting problems. It will change your thoughts about design and test problems for good

 2. <a href = "https://www.geeksforgeeks.org/">GeeksforGeeks</a>: A bible of problems (with well explained solutions). Make sure you do NOT rush for solutions. Try to solve problems on your own no matter how much time does it take. With time and honest practice, you should get better

 3. <a href = "https://careercup.com/">CareerCup</a>: A huge collection of problems. Though you can’t rely upon solutions, it provides a rich community for discussing problems. I found it good for discussing design problems

 4. <a href = "https://projecteuler.net/">Project Euler</a>: A heaven for mathematics lovers. You solve the problems using some formulas on paper and then write code to get the final solution. Solve at least 40 problems from this site.

**Posted with permission from <a href = "https://www.geeksforgeeks.org/prepare-top-mncs/">Aashish Barnwal</a>**
