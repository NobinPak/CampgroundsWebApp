# CampgroundsWebApp
This project is a web app that takes in campground reviews the user must create a account or log in to add a review. This process is check with passport and passport-local the user is authenticated to see if the campground is his/hers, we implemented this by adding in the id to the path if the id matches the user can than delete the review if they choose too. The username after registered is stored in our mysql database which is ran on rds mysql on aws. Only a user that is logged in or registered can create a new review and only the user who created that specific review can delete the review. What makes this project different than other campground review sites is we implemented a animal siting button. After the user is logged in, he can goto the campground review and if they see an animal at that location they can click the add alert button and comment what animal siting they wish to add. Whether it’s a deer to so other family members or inform other campers of dangerous animals at the campground. We added a confirm siting button to confirm the siting, the more confirms the more reliable the siting is. The confirm siting value is stored in our database and increments as the button is click.

Requiremnents:
Java version 7.0, 8.0.

Requirements:

Node.js
External node packages instructions on how to install are below
An aws account, or either visual studio  eclipse JRE
Mysql database either rds mysql instance or 
Install mysql workbench

How to install and run project:

The web app was created using aws 
Aws if you have an account goto the services tab and search for cloud now to create a new environment for your project
For Visiual studios you just upload the folder that is given and follow same commands in the terminal as aws if node.js is installed in your driver. If you do not have node.js you must install node.js onto ur pc first
https://nodejs.org/en/download/
Goto this link and install node.js into your computer into the driver you wish to use
If you do not have an aws account we can also use Eclipse or Microsoft Visual Studio
The project file will be in a zip folder called cs370Project


Name: Nobin Pak, Solman Hussain
Assignment: Track 2
Course: cs370
