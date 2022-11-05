# SocialNetworkBackEnd
Tyler Morse<br>
Employer Database<br>
<br>
AS A social media startup<br>
I WANT an API for my social network that uses a NoSQL database<br>
SO THAT my website can handle large amounts of unstructured data<br>
<br>
Acceptance Criteria:<br>
GIVEN a social network API<br>
WHEN I enter the command to invoke the application<br>
THEN my server is started and the Mongoose models are synced to the MongoDB database<br>
WHEN I open API GET routes in Insomnia for users and thoughts<br>
THEN the data for each of these routes is displayed in a formatted JSON<br>
WHEN I test API POST, PUT, and DELETE routes in Insomnia<br>
THEN I am able to successfully create, update, and delete users and thoughts in my database<br>
WHEN I test API POST and DELETE routes in Insomnia<br>
THEN I am able to successfully create and delete reactions to thoughts and add and remove friends to a user’s friend list<br>
Description:<br>
This application is executed through node.js, including "nodemon", "express", and "mongoose" npms.The application represents a social networking backend, allowing users to create or remove a profile, friends, thoughts, and reactions.
A link to a video demo of the application can be found <a href="https://drive.google.com/file/d/1UGQfkNyXkGIXEfb4F9bCnxwjAfCu908O/view">here<a>.