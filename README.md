
A library management system using ruby on rails.

Landing page launches to a page with links to student section and the book section.

________________________________________________________________________________________________________________


Book section

----button to add new book

    --- form which asks for bookid, title, author and a description
    
----button to edit existing books

    --- form showing the existing details and capability to edit it
    
----delete an existing entry

----button to show more details

    ----function to show all details of the book
    

_________________________________________________________________________________________________________________


Student section

----button to add new student

     ---form which asks for studentname, address and  section 
     
----button to assign a book to a student

    ----form showing the function to assign a book to student and edit existing details of the student as well   
    
----remove an existing student

----button to show more details

    ----function to show all details of the student
    
_________________________________________________________________________________________________________________

Navigation buttons named student, book and home to traverse through the site

_________________________________________________________________________________________________________________
    
NOTE** By default Assigned Book(ID),Issue date and  Days remaining attributes in student sectio will be null when a
new student is created .
As soon as a book is issued to a student the corresponding book id , date of issue ,and days remaining ( i.e. 10 ) will be shown in the respective columns of the student.
The number of days remaining reduces by 1 after each day.





