
![image](https://github.com/user-attachments/assets/2b114e0f-526d-44c9-a429-1c395e4a4438)

 

Manual Integration : 
=====================
The developer makes the code and its build on server at 11 pm in maven and 500 testing and there are bugs so have to send it back to the Developer to rectify the bug 




New Solution continuous integration : 
================================
In continuous integration if example 10 lines pushed in git it will automatically picked by CI Server tool which automatically will compile build continuously and there are error it will notify back to the developer that there are bugs and developers can rectify the bugs. All automated work  

 
	Problem with Traditional Integration: 
	Difficult to implement all the details that have changed 
#Some using Version 2 someone using version 3 
	Difficult to get the latest version of the code early
	Difficult to manage all the changes with changing API versions
	Difficult to manage the entire subsystem of the application that behave differently
	Difficult to rewrite the whole code

Overcome these challenges is continuous integration :
 
 


 

What is Jenkins ?

“A continuous Integration server which manages and control processes such as plan, code build, test, deploy, operate and monitor in DevOps Environment”.

1/ Maven
2/ Selenium
3/ Ansible 





 


#Use webhook to get the code      as new commit occurred
# Email notification plugin to send email if any error in code or build.
#Open source lot of community support in Jenkins community
# Master and salve setup of any number even if its windows or any other OS Can add 
# If 100 task divide 50-50 to 2 slave nodes 

                                         

Jenkins Tri
To automatically execute a Jenkins job, will use Jenkins trigger 
Based on 
Periodic time – schedule 
Whenever there is a commit a GitHub repo
A parent job can trigger execution of child job
Execute a job from remote script

Poll SCM Dashboar build trigger  Poll SCM
Can give every minute or every hour or after 10 hour or 5 pm or anytime everyday. 
Crontab search in google and use this cron schedule

![image](https://github.com/user-attachments/assets/905878ea-6bf2-4497-bb14-6c645b0187b8)

