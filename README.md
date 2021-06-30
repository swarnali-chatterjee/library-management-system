# Library Management System

A Python Flask based Library Management System. This Flask app has all the features of a Library Management System like adding, removing, and creating copies of books. This app has a separate admin tab for admin users. Now also has admin support for users.


# Start

- Clone the repository.

```sh
$ cd Library-Management-System
```

- Create Virtual Environment.
```sh
$ virtualenv venv
$ source venv/bin/activate
```

- Install dependencies.
```sh
$ pip install -r requirements.txt
```

- Run the application.
```bash
$ python main.py
```

- Navigate to http://127.0.0.1:9000/


- The application is hosted on
http://swarnalilibrary.pythonanywhere.com/



-----------------------------------------
##  Instructions to use  ##
-----------------------------------------

## 1. Library Home ##

This is the very first page that open when you link on the library link or host the website

`No books are in library!` will be shown if the website is rebooted or hosted for the first time 

Now you have to log in as a Admin to add book then the same will be shown over this page


## 2. Register : Admin ##

Migrate to `Register` page then add email, name and password
Make sure to select radio button `Admin`

Once register is successful, the system automatically login the user to main dashboard 

Logout from there, and log in as a Admin on `Admin` Section. Now you can see a Admin name on the top left corner

Once you log out, book will will seen on the Home page of library.


## 3. Add Book / Delete Book ##

An Admin is our Librarian, who can add or delete book in library

Choose the appropiate option from top menu, then fill in details of book in case of Add Book and select a book from drop down menu in case of Delete Book

We kept the Issue Book and Return Book as a functionality of Student not Librarian as that doesn't make sense as `who will the librarian issue book to it can really say any student to take book, that is just non sense`


## 4. Show Student ##

This feature in Admin show the list of students that are registered over the website or library 
ie. Anyone who have not selected that `Admin` radio button while login.


## 5. Register : Student ##

Same as Admin, once register is succesfull, the website automatically migrate you to the Student Dashboard page where you can see the Issue Book and Return Book Functionality

Your name will be shown on the top left corner

Keep two points in mind
- Two students can't have the same email
- Password must be atleast 8 letters


## 6. Issue Book / Return Book  ##

Choose the appropiate funtionality from the top menu

Select a book from the drop down menu to Issue a Book

Select a book from the drop down menu that includes the book you have issued earlier to Return a Book

Once a book is issue it will show on the `Student Dashboard`

-Don't issue the same book twice