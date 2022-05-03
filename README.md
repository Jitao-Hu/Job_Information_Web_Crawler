I.Project Name: Job Information Crawler


This project is about building a web crawler and scraping job information, such as company name, required skills, publication date and URL to the job post.


II.Project Description:


This web crawler scrapes the job information of jobs that require python as skills from website "Timesjob"(link: https://www.timesjobs.com/candidate/job-search.html?searchType=personalizedSearch&from=submit&txtKeywords=python&txtLocation=). The program scrapes company names, skills requirements, post dates and URLs of jobs and saves the information of each job in a single text file in the folder which is named "posts". This robot includes a time function that scrapes job information every 10 minutes to make sure that the information is updated frequently. 


I chose to use beautifulsoup and python to build this robot since they are straightforward and the purpoose of the project is to learn python and web scraping.


III.How to use the project


When you download the file, make sure to also download the folder "posts" which is used to save information.


You can run the project in terminal or IDEs, at first, it will ask for a skill that you are not familiar with and you can input any programinng skills except for python since all jobs on the website require python. Then, the program will filter out jobs that require skills you do not have and save information of othe jobs in text files in the "posts" folder.


IV.Future Development


  1.This web crawler can only scrapes information from a single web page, maybe we can manage to get the information from multile pages
  
  
  2.This crawler will not delete old (outdated) text file, we can implement related function
  
  
  to be updated...


V.Credit


The robot is built based on the tutorial provided by the Youtube channel "freecodecamp" (link to the tutorial: https://www.youtube.com/watch?v=XVv6mJpFOb0). Thank them to provide such a great tutorial!




