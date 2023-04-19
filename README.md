# Home Tutoring Management System
#### A back-end management system that facilitates matchmaking between individuals seeking home tutoring services. The system records detailed information such as subject classifications, hourly rates, and teacher profiles in a transparent manner for easy access.

# Function Introduction
#### 1. CRUD operations are supported for creating, reading, updating, and deleting data.
#### 2. Extension methods are utilized through ISPan.Utility.
#### 3. ErrorProvider is integrated to display warning messages if personal information is not filled in properly, such as missing password or account.
#### 4. Teachers can upload personal pictures, supporting 5 types of image formats (Jpg, Jpegs, Png, GIF, Bitmaps), when providing personal consultations.

# Description of Product Maintenance Record Function
#### In the add and edit functions, the form information is first built into a ViewModel, and then field verification is performed.
#### At the beginning of EditForm, a record is loaded and converted into a ViewModel, and then bound to various controls.

## The following pages all have the functions of creating, adding, deleting, and modifying.

![image](https://github.com/cindy5hsu/WinForms-CRUD/blob/master/Project_Store/Resources/1-2.png?raw=true)

#### On the login page, when the account and password are not entered, an ErrorProvider warning icon will appear. Similarly, when the account or password is incorrect, a window will appear displaying the error message.
#### Clicking "Clear Fields" will clear the information entered in the fields above.  
#### Clicking "Exit" will close the program.

![image](https://github.com/cindy5hsu/WinForms-CRUD/blob/master/Project_Store/Resources/0-1.jpg?raw=true)

#### After successful login, this main page will be displayed where you can select the content to be edited.

![image](https://github.com/cindy5hsu/WinForms-CRUD/blob/master/Project_Store/Resources/2-5.jpg?raw=true)

#### This is the user account creation page. As it is a backend management system, registration cannot be done at the login page. Users need to log in to the backend system first before they can register.

![image](https://github.com/cindy5hsu/WinForms-CRUD/blob/master/Project_Store/Resources/3-2.jpg?raw=true)

#### Subject classification sorting page helps to better categorize the subject classification menu.

![image](https://github.com/cindy5hsu/WinForms-CRUD/blob/master/Project_Store/Resources/2-2.png?raw=true)

#### You can select the subject category from the dropdown menu on the subject category page, which allows you to quickly find the course category.

![image](https://github.com/cindy5hsu/WinForms-CRUD/blob/master/Project_Store/Resources/3-1.jpg?raw=true)

#### The teacher's personal information filling page contains a date drop-down menu and a subject classification drop-down menu. Personal pictures can be uploaded, and the file name of the photo is displayed below the picture.

![image](https://github.com/cindy5hsu/WinForms-CRUD/blob/master/Project_Store/Resources/3-3.jpg?raw=true)

#### when you click on the "Logout" button, a confirmation window will pop up to confirm the logout action

# Challenges Faced
#### It took me some time to figure out how to add images to the database. Eventually, I decided to record the image name in SQL Server.
#### Also, I encountered some difficulties with using extension methods, and had to debug for some time.
#### When I couldn't solve a problem on my own, I would search online and discuss with classmates to find a solution.






