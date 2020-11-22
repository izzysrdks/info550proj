# Final Project For INFO 550: Data Science Toolkit  
  
 
## Background on the project  
For this project, I am combining three datasets in order to run a regression to assess if the engagement of a student in yoga practice affects their TNF alpha levels. This work is related to my project for my capstone.  
  
## How to run the program  
Everything needed is in a docker image. To get the program to run, pull the docker image using the following code:  
`docker pull izzysrdks/info550_project:proj`  
After doing so, you can run it by entering:  
`docker run -v /path/to/project:/project izzysrdks/info550_project:proj`  
Replace "/path/to/project" with the specific path to the project folder on your computer. This will run the program and create a final report titled "report.html" in the reports folder.  

