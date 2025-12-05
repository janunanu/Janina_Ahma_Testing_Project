Learning Reflection for GitLab Testing Project

Summary of the assignment

This project was about learning how to test a website, specifically GitLab. I had to make a detailed test cases for creating accounts, starting a new project, and making an issue (task/bug) and write a report about it. My experience testing the actual web application was very useful because it's completely different from the quizzes. The required file structure was effective for ensuring I thought about every angle of the test.

Key takeaways

I learned that testing needs to be organized and that even the most clear things that one would assume everybody knows need to be written out so there is no confusion on how to run the test.

I used the specific format with the three boxes (Settings, Variables, Test Case), which makes the test steps easy to follow. This process of using a formal structure for Preconditions, Inputs (Variables), and Expected Results really helped me make sure I didn't forget any important steps. Also, the structure in the test suites has the syntax required for test automation using Robot Framework and I didn't know before what it includes and how it looks so this was useful to learn.

I figured out that all the test pages are connected. The biggest thing I learned was that one test needs to succeed before the next one can even begin. For example, I had to pass the registration test (03_RegisterPage) to even be able to start the project test (04_ProjectPage).

At first, I didn't think about security checks like the "I am not a robot" feature (reCAPTCHA) on the registration page. Then I realized that a robust test suite must verify that anti-bot defenses are working, even if I can't always see the checkbox. Checking this negative case stops spam accounts messing with the site.

I learned in the bug report that I have to clearly write down the steps to reproduce as well as fixing suggestions and also provide screenshots/code if possible so the programmer can fix the bug fast.

GitHub is the only part of this assignment I was already familiar with so publishing my repository there was simple.

I used Visual Studio Code to edit the files, as I am familiar with it and it was easy.

The manual steps I wrote are very clear, so I think they could be put into a simple spreadsheet (like Excel) or maybe a dedicated tool like TestRail so other testers could see them easily.

In-Demand Skills: By looking at job postings for "Tester" and "Automation Tester" on Glassdoor and LinkedIn, it seems the most important skills right now are Test Automation (using tools like Selenium/Cypress/Python) and knowledge of SQL (for checking database data).

I actually discussed with a representative of a big company about their testing processes and turns out they also use Robot Framework and any knowledge in that are would be useful in applying for example for a trainee position.
