# Application Flow
# NOT COMPLETE


### User Sign up

1. User chooses sign up on the menu (available on all pages, unless the user 
is signed in already).
1. User fills out the sign up form and submits.
1. Request goes to sign up servlet.
1. Servlet creates a user object and then creates user in the database.
1. Response to user confirming addition (show a message on the jsp)

### User Sign In

1. User chooses sign in on the menu (available on all pages, unless the user 
is signed in already).
1. User enters username and password on form and submits. 
1. If user is authenticated, the server will handle allowing access to edit 
pages.  JDBCRealm used for authentication (users, users_roles, and roles table).
1. If authentication fails, show error message/page.

### View User Challenge Info

1. Page sends a request to view challenges servlet along with criteria 
(user, complete, in progress, etc).
1. Servlet uses the challenges dao to select challenges according to criteria
1. Dao performs select and creates challenge objects from results.
1. Dao returns list of challenges matching criteria to servlet.
1. Servlet sends list back to my dashboard jsp.
1. My dashboard jsp displays the challenge grid.

### View Book

1. Page sends a request to view book servlet along with criteria 
(all, title, author, etc).
2. Servlet uses the book dao to select books according to criteria
3. Dao performs select and creates book objects from results.
4. Dao returns list of books matching criteria to servlet.
5. Servlet sends list back to book  jsp.
6. My Dashboard jsp displays the books.
7. Consider paging results so page does not get super long and too much data 
is sent.

### About
1. Static page - html only? 

### Add Book
1. Option only available to logged in users with proper role

### Add Challenge 
1. Option only available to logged in users with proper role








 
