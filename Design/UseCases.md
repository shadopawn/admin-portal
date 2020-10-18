# Actors
- Business Admin (Admin)
- User

# Use Cases
- UC1: Admin uploads video 
-- We need this use case in order for new video to be added to the application. Without adding new videos, they can’t create new lessons. The lessons are dependent on the videos and he wants to be able to make more lessons. 
-- The actor at play is the “admin” 
-- The admin will make sure he is logged in as an admin. They will then go to the lesson making portal. This page will allow the admin to create lessons. Because videos are required to make lessons, they will be able to see the videos they have uploaded to the database. If the video they need is not there, they can click a button, select a file, then upload it to the database. The page will then display all the videos including the newly uploaded one. 
-- BR1

- UC2: Admin puts videos into a lesson -- We need this use case for the lesson creating function. The admin wants to be able to create lessons, and that involves stringing videos together to create a whole lesson. Without the ability to put the video in a certain order, there would be no way to create a coherent lesson. -- The actor at play is the “admin” --  The admin will make sure he is logged in as an admin. They will then go to the lesson making portal. This page will allow the admin to create lessons. Once here, the admin will select from a list of videos that have already been uploaded. The admin then can list the videos out in the correct order. -- BR1

- UC3: Admin saves lesson into database -- We need this use case for finishing the lesson creation process and for turning it into a use lesson for Unity -- The actor at play is the “admin” -- After the admin has create the lessons order in the lesson making portal, the admin will press “create lesson”, and it will be sent to the database. -- BR1
- UC4: User can download lessons into unity application -- We need this use case for the lesson to actually be playable in the unity application. The application needs some way of converting the lesson made and stored into the database into a lesson that’s playable in unity. -- The actor at play is the “User” -- The user will arrive at the Unity Application. They can go to a menu to buy new lessons. Once they have bought a new lesson, the download will begin. Once done downloading, they can now view and play the lesson. -- BR2

- UC5: Users view and play lessons with progress tracked -- We need this use case because the user shouldn’t have to restart lessons when they log out. They should be able to start at the video they left off at. They should also be able to see where they left off at and not just have it happen automatically. -- The actor at play is the “user” -- When the user opens up the unity application, they should see the lessons they have bought. When they click on a lesson, they should see which of the videos they have completed. They can then start the video that is after the last video they completed. -- BR2

- UC6: Users compete for achievements -- We need this use case as an incentive for the users. We want them to strive for more practice and training. If we add achievements, they’ll want to use the application more and maybe even buy more lessons. -- The actor at play is the “user” -- When the user opens the application and is signed in, it will display a score or number of achievements they have done. There is a menu to see what the achievements are and how to get the others. -- BR4
- UC7: Users data is collected -- We need this use case because we want the admins to be able to analyze the data. If we don’t collect the data, there is no way for the admins to see trends and use user data. -- The actor at play is the “user” -- The unity application will have user data tracked and will upload the data when the application is connected to the internet and database. -- BR3

- UC8: Admin can analyze user data -- We need this use case because the admins need some way of analyzing the user data. Even if the data is collected, if there is no way to see it or visualize it, then there is no point collecting the data. -- The actor at play is the “admin” -- The admin will log into the react app. The react application will have a data visualization page. From there, the admin can visualize and see the data in many different ways. -- BR3
