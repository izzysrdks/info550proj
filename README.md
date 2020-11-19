# Final Project For INFO 550: Data Science Toolkit  
  
 
## Background on the project  
For this project, I am combining three datasets in order to run a regression to assess if the engagement of a student in yoga practice affects their TNF alpha levels. This work is related to my project for my capstone.  

## About
This repo contains several files that allow you to either run the program via docker (recommended) or just using the makefile. Follow the below instructions for whichever method you are looking for. Additionally, the repo contains five folders, a dockerfile and a makefile. For more information on the makefile you can type `make help` from the command line while in the project folder to see information about each section of the file. THe raw_data folder contains the raw_data for the analysis, clean_data will be the folder where the program drops the data used in the analysis, figs will contain any figures created while running the program, Rcode contains any of the statistical programs needed, and lastly Reports is where the final report will be dropped.
   
## Set Up  
First fork and clone this repository onto your local device and note the path to the project folder.  

## Execute the Code with Docker (Recommended) 
To run the program, first pull the docker image using the following code in the command line:  
`docker pull izzysrdks/info550_project:proj`  
After doing so, you can run it by typing:  
`docker run -v /path/to/project:/project izzysrdks/info550_project:proj`  
Replace "/path/to/project" with the specific path to the project folder on your computer. This will run the program and create a final report titled `report.html` in the reports folder.  

## Execute the Code without Docker  
After forking the repo, type `make` in the command line and the program will run. A report titled `report.html` will be dropped in the reports folder. Please note that this method might lead to issues with installing the R packages or running R programs on a different type of system than they were originally built on.  


