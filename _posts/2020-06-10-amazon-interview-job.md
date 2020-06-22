---
layout:     post
title:      Job Interview - How is Amazon interview?
date:       2020-06-10 20:45:00
author:     Mariana Campos
summary:    How is my first job interview in Amazon
categories: Programming carrer
comments: true
tags:
 - Python Amazon
---
<i>Hi :) my name is Mariana Campos, I am Junior Software Developer and I will share with you my first Amazon interview. </i>

I will say right up front that the end of this story will not be happy, but I guarantee is still a great story with  a lot of knowledge. My first interview with Amazon, more specifically with the AWS team, brought challenges, code problems, anxiety, and nervousness. But, it is OK, this is part of any software developer’s day. Let’s start!

<img src="/assets/amazon_imagem_blog.png">

It all started when a recruiter sent me a message on LinkedIn asking if I wanted to participate in the selection process. Immediately, I said yes and sent my resume. 

A dream that started at the beginning of my graduation degree, and was asleep, surfaced again when I received that message. I always dreamed to work in a big company like Google, Amazon, and Microsoft. Why did I stop to search for a job in those companies?  First, because brazilian universities don’t prepare students for these interview process, students are not incentivized to apply to tech unicorns or attend to programming competitions. Second, the interview process is usually difficult and demands a lot of study hours, so if you don’t come from a privilege home you often will not have the time to focus on the process. It is a common reality, we need to work (sometimes in early ages)  because our family depends on us.

The dream came back and I started the interview process. First: Codility test, this step was very simple. The recruiter sent me a link to a platform (like Codility, Hackerrank) and I had  to solve problems. I must confess that  I am not the fastest software engineer in the world, I like to take my time and think a lot about the problem (this is usually a bad thing in this kind of interview). Before the start of the interview I chose a quiet place in my house to make sure I wasn’t going to be interrupted. The session had 100 minutes and two questions:

<i>
1) Given a string "aaabbbcc", compress it, = "a3b3c2" . Given  that output string's length is always smaller than input string, you have to do it inplace. No extra space.
</i>
<i>
2) Given a string S and and String T, return:
<ul>
<li>"INSERT x" if string S can be obtained from String T by at most one insertion of character x.
For example, when S = "nice" and T = "niece", the method would return "INSERT e"</li>
<li>"DELETE x" if string T can be obtained from String S by at most one deletion of character x.
For example, when S = "hello" and T = "hell", the method would return "DELETE o"</li>
<li>"SWAP x z" if string T can be obtained from String S by swapping two adjacent characters.
For example, when S = "from" and T = "form", the method would return "SWAP r o"</li>
<li>"IMPOSSIBLE" if string T cannot be obtained from string S according to the rules above</li>
<li>"SAME" if string T equals string S</li>
</ul>
</i>

We established that  I am a slow person. I had already done other interviews in which I had to solve issues on code platforms, and most of the time, I couldn't finish them on time. To overcome this bad record, my strategy was to focus on these issues as much as possible and resolve them quickly  and this time it worked, I was able to finish the problems on time.. So,  one thing to always keep in mind is how  focus is important.

In next day, the recruiter sent me an email saying that I had moved on to the next stage of the interview (I will mention here that the recruiter responded very quickly, unlike the other processes that I have participated). This time, I thought: “Cool, I have a chance, but the most important thing is the experience”. Thinking like that made me lighter and less pressured, which helped me a lot to think clearly and answer questions calmly. The next step (the second step) is the phone interview, where you talk to one of the engineers about your professional experience. I learned two importants things with this step: one (more general) is the STAR method and the other was the Amazon Leadership Principles.

STAR is an interview response method that helps you to give concise answers with examples where you can show your skills and proof that you possess the experience. STAR stands for Situation, Task, Action, Result:

<ul>
<li>Situation: Describe the event or situation that you were in.</li>
<li>Task: Explain the task you had to complete.</li>
<li>Action: Describe the actions you took to complete the task.</li>
<li>Result: Close with the result of your efforts.</li>
</ul>

You can see more here:
<a href="https://www.thebalancecareers.com/what-is-the-star-interview-response-technique-2061629">https://www.thebalancecareers.com/what-is-the-star-interview-response-technique-2061629</a>

This is very helpful, I will try to use this in my life! 

Another thing that I had to learn were the Amazon Leadership Principles which are 14 leadership principles that guide the company. You can read the principles here:

<p><a href="https://www.aboutamazon.com/working-at-amazon/our-leadership-principles">https://www.aboutamazon.com/working-at-amazon/our-leadership-principles</a></p>

The questions asked would be based in these principles, that’s why it’s very important to know them. They are not difficult to learn and your recruiter will send material to prepare you. The point is: You should link these principles with your professional experience. This is an example:

<i>
Interview: “What improvements have you made at your current company?”
Candidate: “We were using an Enterprise Service Bus in our project for SOA, and one of the functions we use it for is to record the time when a web service request arrives at our platform and when the response leaves the platform. Logging this information helps us measure response-time performance analysis for each web service. The response-time data were stored in a database which has grown very big as the platform has expanded over the years. 
</i>
<i>
We needed to keep the growth of the database in check. Per project requirements, it was also necessary to keep data available for three months online and one year in an offline storage. 
</i>
<i>
I developed a tool that met and automated the requirements. Once the user configures the tool, it automatically finds the table partitions in scope, backs up those partitions, zips up the backup, and then moves the backup to tapes. As the final step, it generates SQL script files to clean up the partitions that it had backed up. 
</i>
<i>
As a result of this automation, we saved at least one to two days of effort per month. We are also using this tool to clean up the logs for provisioning history from customer records.
“
</i>

The Amazonians take these principles very serious, so it is important to memorize them to the Phone Screen Interview. My experience with this step was very nice, it was  just a conversation, I followed the STAR method and it worked well. After this step I was happy because I managed to talk in English for 45 minutes. Some hours after that, I received an email from the recruiter: I was in the final step of the process. 

The OnSite interview is the final step of the process. The recruiter sent me a email to confirm my availability from that day to a month, which means I had 4 weeks to review concepts and practice code challenges. The recruiter also made a call with me to explain the process, how many interviews would it be, what kind of the questions would be asked, and etc. After that, they sent me an email with several materials and the schedule of the interview. As the position I was interviewing was for software developer there would be only 3 technical interviews and 1 about cultural fit. 

I was a little worried about my sanity during this month, but I handled well. I worked during the day and studied at the night. I took the opportunity to learn more about Python in depth and to review concepts about data structure and OOP. To help me, I used the tool codecademy. In the two last weeks I solved problems in the Leetcode platform. It is worth mentioning that the recruiter sent several materials to study, tips from sites with codes, and material to understand more about Amazon. The leadership principles must be fresh in your mind.  I will add these links at the end of this post. 

The OnSite interview started, with a Senior Manager Solutions Architecture. All the questions were about my previous experience linked with the leadership principles. The conversation was very nice but I was nervous because of the three code interviews ahead.  Each technical interview happened in one hour: 20 minutes to answer questions about Leadership principles, 20 minutes to solve code questions and 5~10 minutes for  you to ask questions to the interviewers(the recruiter encourage you to ask questions and it’s not every day that you talk to an AWS engineer). 

I could not finish two of the three code questions, I felt horrible. After the bad feeling, I thought about my errors. I should have practiced more code challenges and be more comfortable with Python functions. For example, I forgot the name of some special functions in Python and I couldn't think of more concise solutions. Probably if I solved more different problems, I could have solved a similar problem to the interview. 

This experience was amazing, I really enjoyed this process. I will not give up, so I put in my calendar, some reminders to solve one code challenge every day and I will spend 2~3 hours in Python courses on weekends. Even though I haven't passed, I can give you some hints:

<ul>
<li>Know your projects. Make a list of projects you worked on and separate some events that you participated during the project. It is important to think about what value you delivered to your client or/and coworkers.</li>
<li>Take the Leadership principles very serious. Try to link those principles with your projects examples described in previously topic.</li>
<li>Try to solve code questions in a specific time.</li>
<li>Search about the process, you can find more content and if you are lucky, maybe a friend that works in Amazon can  help you with the process.
</li>
<li>Enjoy the interview, try to have fun. I think I did the OnSite interview with a lot of pressure and anxiety, as if my life depended on it, only it didn't. </li>
</ul>

Even though it wasn’t a happy ending, that dream didn't went to the end of the line, it is one of the priorities now. I will continue to study more English, solve programming challenges and learn about Python. It's just the beginning. 

If you have any suggestions, please let me know, contact me in my social medias. I will love to hear you!

I want to thank my friend Rebeca Sarai (<b><a href="https://github.com/rsarai">@rsarai</a></b>) for encourage me to write and review this text.

Some sites helped me a lot, if you want or you will participated in a interview, you should see those sites:
<br>
<p><a href="https://leetcode.com/">https://leetcode.com/</a></p>
<p><a href="https://practice.geeksforgeeks.org/">https://practice.geeksforgeeks.org/</a></p>
<p><a href="https://www.hackerrank.com/">https://www.hackerrank.com/</a></p>
<p><a href="https://www.codility.com/">https://www.codility.com/</a></p>

Specific to Amazon interviews:

<p><a href="https://www.amazon.jobs/pt/principles">https://www.amazon.jobs/pt/principles</a></p>
<p><a href="https://interviewgenie.com/blog-1/category/Amazon+interviews">https://interviewgenie.com/blog-1/category/Amazon+interviews</a></p>
