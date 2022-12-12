## Library Management in py


A library management system keeps track of the books present in the library.
 It is an important piece of software which is a must at schools and colleges. 


The library management system in python which we are going to build will look something like this :

(img)


## Project Requirements

Open your python compiler terminal :

- tkinter – Please run below command to install tkinter

`pip install tkinter`
- pillow – Please run below command to install pillow

`pip install pillow`
- pymysql – Please run below command to install pymysql

`pip install pymysql`

**Note:** You are required to have MySQL server installed on your system in order to make pymysql work. If you do not have it ready, please download from <a href="https://www.mysql.com/downloads/" target="_blank">MySQL Official website</a>



## Description of Project files

Below are the project files you will get once you fork and clone the Library project:

- `main.py` – which does function call to all other python files
- `AddBook.py` – To add the book
- `ViewBooks.py` – To View the list of books in the library
- `DeleteBook.py` – To Delete a book from library
- `IssueBook.py` – To Issue a book from library
- `ReturnBook.py` – To Return a book to the library

**NOTE:** Use your own Database name and password.


## Description of Tables (Database)

**Create Tables:**
```
 create database db;

create table books(bid varchar(20) primary key, title varchar(30), author varchar(30), status varchar(30));

create table books_issued(bid varchar(20) primary key, issuedto varchar(30));
```
- **books**

![image (1)](https://user-images.githubusercontent.com/79866006/207016754-a8c38ce7-c732-4618-b688-b8c65e62bc23.png)


- **books_issued**

![image (2)](https://user-images.githubusercontent.com/79866006/207016822-f44ea6c6-d670-4a0c-8d29-6b1e77ca15d0.png)



## Description of Project Codes

Let’s start the detailed discussion of each and every file of our library management system python project:

1. **main.py**



### Info

- Make a `pull request` to countribute to this project
- Make an `issue` if you're facing an issue
- `Fork` this Project to receive more python projects 
- Give a `star` if you like this Project 



- **Note**

Apart from this,

you can now take a step forward to extend the project by making a history tab which keeps track of the previous books issued.

Moreover, you can integrate a login system to authenticate a user before making changes to the database.




