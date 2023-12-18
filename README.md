![Illustration of strategic budgeting](https://media.licdn.com/dms/image/D4D12AQHjnp8H542LQg/article-cover_image-shrink_423_752/0/1693976745162?e=1704326400&v=beta&t=q68cvRcywg09W39GuhKW4yn8_roFDN_1xE6QpEIg7Fc)
# Strategic-School-Budgeting
## Description
In this challenge, I'm tasked with helping the school board and mayor make strategic decisions regarding future school budgets and priorities. I have been given access to every student's maths and reading scores, as well as various information on the schools they attend. My task is to aggregate the data to showcase obvious trends in school performance. 
## Usage
This repository contains the following files/folders:\
-PyCitySchools folder: which contains the csv file used for the analysis process and a Resource folder that contains the script for this challenge. Please navigate to the Resources folder to view the script.\
-Written report: which contains a summary and important conclusions drawn from the analysis results. Please navigate to this file to view the report.
## Installations
The following dependencies were utilised to run the code. Please copy the code as is:
1. `import pandas as pd`
2. `from pathlib import Path`

Please ensure you have the following libraries pre-installed:
1. `pip install pandas`

## School budget analysis
Our original dataset contains the following columns:
1. `Student ID`
2. `student_name`
3. `gender`
4. `year`
5. `school_name`
6. `reading_score`
7. `maths_score`
8. `School ID`
9. `type`
10. `size`
11. `budget`

### School summary
The table below summarises key metrics about each school:

![Alt text](<Screenshot 2023-12-18 at 1.11.37 pm.png>)

The top performing schools are summarised below:
![Alt text](<Screenshot 2023-12-18 at 1.12.46 pm.png>)

The bottom performing schools are summarised below:
![Alt text](<Screenshot 2023-12-18 at 1.13.37 pm.png>)

## Credits
Special thanks to these individuals for their contribution in this project:
-Jesse Wright (BCS tutor): for helping me with bugfixing the code.
-Silo, Abhat and Marissa (Ask BCS assistants): for helping me with uploading the assignment to GitHub and understanding how some Pandas functions work. 
