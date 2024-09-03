# Little Lemon Web Application

## Introduction 
This is the final project for Meta Back-End Developer Capstone course.


## APIs
```restaurant/api/menu```
Allow all authenticated users to view the menu items
Only admin user could post new item

Fields needed to update:
>**title**: str

>**price**: decimal

>**featured**: (opt.) boolean, default = 0

```restaurant/api/menu/<int>```
Allow all authenticated users to view single menu item
Only admin user could update or delete single item

```restaurant/api/book```
Allow authenticated users to post new book, please use the same username of the user as the name of book

User could obtain all the books that has the same book name with the current username

Fields needed to update:
>**name**: str, the same as username

>**guest_number**: (opt.) int, default = 1

>**date**: date, in the form of "YYYY-MM-DD"

>**comment**: (opt.) text

```restaurant/api/book/<int>```
Only admin user could view or delete single book