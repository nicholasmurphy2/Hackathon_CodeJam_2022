# Save The Date

https://devpost.com/software/save-the-date-g8ayl4
https://github.com/AmimerNabil/codejam2022/blob/main/readme.md

### **WHAT IT DOES**
*Save The Date* is a website that makes the long and tedious task of organizing an agenda simple and efficient. The website contains a window where a user can drop a .pdf file that will be processed with the Amazon Textract API. The API we are using will read through the tables and extract all of the dates for submissions and exams. A python script will then use the tables extracted by the API and will parse through the table to get the name of the task (ex. Assignment, Midterm, Presentation, etc.) as well as the due dates for all of the tasks. The following step makes use of the calendar API from Google to export all the data onto an online calendar that makes organization simple and clear.

### **HOW WE BUILT IT**
The development process for our web application was done in many simultaneous steps. We split the workload into three major sections: the front-end, the dropbox for the files, and the rest of the backend. For the front-end, we used HTML 5 and CSS to create our webpage. The dropbox was made using Javascript as well as HTML 5 and CSS. The rest of the backend on the website is made up of Python scripts.
