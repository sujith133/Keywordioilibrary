# Keywordioilibrary

General Operation of the these Project is as the server directs to a page and form is submitted, the response is thrown to the Django framework using POST method. then the requested url is sent keywordio/url.py file and searches for the url and if url matches the given url then it calls the respective instance in the viewa.py file. that particular instance takes all the response from the html post operation and performs respective operations on it and return a response in html forms. 
________________________Login and Signup page__________________________

1. created a frontend interface using html.

2. using POST methood retrived the data from the form and analysed and verified in the views.loginsignup or views.Signup functions with respective to the button pressed.

3. for Login conditiion to be written as if the form data is thrown to the login views and login credentials are matching to any one of the database logins then the page should directs to Admin portal and if it does not match then the portal should direct you to login portal .

4. For Signup condition is writtened as when the form data is thrown to the signup views then that instance check for the email id's in the database with the form data, if the email id matches no response is given and if not the data is entered into the logins data base.

________________________Student View__________________________

1. for student view blog condition is writtened as the button is pressed django takes all the data book records and push it to the student view html page.
2. html page retrieves the data using for loop and display it on screen.

________________________Admin View__________________________

1. In Admin view CRUD operations are performed and buttons are created with respective responses and if the create button is pressed the create html link is thrown to the django and that framework sends back its response with create html file.

CREATE: for CREATE condition to be written as if the form throws response with the book details to the framework, it checks the book id and book name and are matching with the database and if not it adds the book to the database else it doesnt adds it to the database.

READ: for READ condition is writtened as the button is pressed django takes all the data book records and push it to the student view html page. Html page retrieves the data using for loop and display it on screen.

UPDATE:  for UPDATE condition to be written as if the form throws response with the book details to the framework, it checks the book id is matching with the database and if not it does not update the book details to the database, else it update the book details to the database.

DELETE: for DELETE condition to be written as if the form throws response with the book details to the framework, it checks the book id is matching with the database and if not it does not delete the book details in the database, else it deletes the book details in the database.
 
