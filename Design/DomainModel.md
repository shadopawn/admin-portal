
![Domain Model](/Design/DomainModel.png)

React - This  front end class will have two Lists, Videos and Lessons. As well as methods to add/remove videos, move videos forward or back in the lesson list, and upload/download lessons to/from the Firebase Database

Admin - This class will be extended from the React class with an attribute for name as well as methods from React
Firebase - This is our database which will store the lessons, which contain the videos within them. It should also hold the users information, and a completion list for users.

Unity - The unity class should be able to get lessons from firebase, and upload completion information from the clients.

User - The user is extended from the unity class, inheriting the methods for uploading statistics and getting lessons. The user class also updates its list of completions. 

Lesson - The Lesson class has a list of videos, organized through react. 

Video - The video class has its length and is uploaded by admins.
