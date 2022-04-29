# Archana7classes
This contains all the files and information regarding the 21-Day Python Intern Training Tasks.

PROJECT TITLE:
README file of 21-Day Python Intern Training Tasks.

PROJECT DESCRIPTION:
This project helps to create availability table and time table for students and teachers which makes it easy to keep a track of their time and schedule. 

TABLE OF CONTENTS:
In this project we have used the following excel files-
i) Batch - Consisiting of all the available batches along with batch id's.
ii) Subject - Consisiting of all the subject names along with subject id's.
iii) Student - Consisiting of all the students names along with student id's and also consisting of batch id as a FOREIGN KEY.
iv) Teacher - Consisiting of all the teachers names along with teacher id's and also consisting of subject id as a FOREIGN KEY.
v) Availability - Consisiting of all the teacher names with their availability of days and timings.

HOW TO INSTALL AND RUN THE PROJECT?
To run this particular project we need to install anaconda python and PostgreSQL shell.
We need to install anaconda distrubution which is an open-source repository and toolkit. 
The site is https://www.anaconda.com/products/distribution 
It installs a package consisting of Anaconda Navigator, Powershell, Prompt, Jupyter Notebook and syder.
Next, we need to install PostgreSQL shell.
The site is https://www.postgresql.org/download/
We can create and run our subject,batch,student,teacher,availability and time_table psql tables in here.

HOW TO USE THE PROJECT?
First we create a batch excel file containing column batch_name. 
Then we create a subject excel file containing column subject_name.
Then we create a student excel file containing columns student_name and batch name as a FOREIGN KEY.
Then we create a teacher excel file containing columns teacher_name and subject name as a FOREIGN KEY.
Then we create an availability excel file containing columns teacher_name, days and timings.

Now we enter the batches,subjects,students and teachers in their respective psql tables.
Which will look like this-
![1](https://user-images.githubusercontent.com/101273679/165882037-68bb564e-6d83-4934-b4c3-a4da08be4fb3.JPG)
![1](https://user-images.githubusercontent.com/101273679/165882246-004f5b24-0a4f-4b1b-8719-ba24f9f503e2.JPG)
![1](https://user-images.githubusercontent.com/101273679/165882472-f0b390f5-ea96-43f8-8cc5-a45b39a78aab.JPG)
![1](https://user-images.githubusercontent.com/101273679/165882653-ee17c64e-9f7d-4892-b851-461791f8dd38.JPG)
![1](https://user-images.githubusercontent.com/101273679/165882942-386a6fa3-46d6-4978-9e62-487ba6f52c5f.JPG)

Now, when we want to book a slot the process is as follows-
![2](https://user-images.githubusercontent.com/101273679/165883464-d56ccfc8-d59e-41d7-817f-728cbda75087.JPG)

Now, we have to delete the selected slot from the availability table and add to the time_table
![3](https://user-images.githubusercontent.com/101273679/165883519-4774a680-d5e4-4e71-98a1-3d57be034f56.JPG)

The result is as follows-


![4](https://user-images.githubusercontent.com/101273679/165883543-47da3351-4e08-4ed6-a836-ed1112d39715.JPG)

![5](https://user-images.githubusercontent.com/101273679/165883558-bb1f86dd-061f-4650-9fd0-e88ba1761a05.JPG)






