# Model-View-Controller Tech Blog
<br/>

## **Link** to app deployed on heroku: https://tons-tech-blog.herokuapp.com/ 

## **Link** to project repository: https://github.com/alinz07/mvc-techblog 
<br/>

## **Motivation**
Create a CMS-style blog sit to publish blog posts and comment on other developer's posts. Use the MVC paradigm, handlebars.js as the template language, sequelize as the ORM and express-session npm package for authentication.
 .

<br/>

## **Table of Contents**
[How and Why?](#what-problem-does-this-solve-and-how-was-a-solution-accomplished) <br/>
[Things I learned](#things-i-learned) <br/>
[What makes this project stand out?](#what-makes-this-project-stand-out) <br/>
[Challenge Criteria](#challenge-criteria)<br/>
[Screenshot of Web Application](#screenshot-of-web-application)<br/>
[How to Contribute](#how-to-contribute)<br/>
[Credits](#credits)<br/>
  
<br/>

## **What Problem does this solve and how was a solution accomplished?**
Developers need a way to read and write about technical concepts, recent advancements, and new technologies.
<br/>

## **Things I learned**
* How to use the maxAge property of a cookie property of an express session. The maxAge property defines how long it will take for a cookie to expire, thus forcing a user to login again before being able to add posts or comments when used in conjunction with the withAuth() function that runs before create, update and delete methods in the api routes.
* 
<br/>

## **What makes this project stand out?**


<br/>

## **Challenge Criteria**
AS A developer who writes about tech
I WANT a CMS-style blog site
SO THAT I can publish articles, blog posts, and my thoughts and opinions

GIVEN a CMS-style blog site<br/>

* WHEN I visit the site for the first time<br/>
THEN I am presented with the homepage, which includes existing blog posts if any have been posted; navigation links for the homepage and the dashboard; and the option to log in

* WHEN I click on the homepage option<br/>
THEN I am taken to the homepage

* WHEN I click on any other links in the navigation<br/>
THEN I am prompted to either sign up or sign in

* WHEN I choose to sign up<br/>
THEN I am prompted to create a username and password

* WHEN I click on the sign-up button<br/>
THEN my user credentials are saved and I am logged into the site

* WHEN I revisit the site at a later time and choose to sign in<br/>
THEN I am prompted to enter my username and password

* WHEN I am signed in to the site<br/>
THEN I see navigation links for the homepage, the dashboard, and the option to log out

* WHEN I click on the homepage option in the navigation<br/>
THEN I am taken to the homepage and presented with existing blog posts that include the post title and the date created

* WHEN I click on an existing blog post<br/>
THEN I am presented with the post title, contents, post creator’s username, and date created for that post and have the option to leave a comment

* WHEN I enter a comment and click on the submit button while signed in<br/>
THEN the comment is saved and the post is updated to display the comment, the comment creator’s username, and the date created

* WHEN I click on the dashboard option in the navigation<br/>
THEN I am taken to the dashboard and presented with any blog posts I have already created and the option to add a new blog post

* WHEN I click on the button to add a new blog post<br/>
THEN I am prompted to enter both a title and contents for my blog post

* WHEN I click on the button to create a new blog post<br/>
THEN the title and contents of my post are saved and I am taken back to an updated dashboard with my new blog post

* WHEN I click on one of my existing posts in the dashboard<br/>
WHEN I click on one of my existing posts in the dashboard

* WHEN I click on the logout option in the navigation<br/>
THEN I am signed out of the site

* WHEN I am idle on the site for more than a set time<br/>
THEN I am able to view comments but I am prompted to log in again before I can add, update, or delete comments
<br/>

## **Screenshot of Web Application**
<!-- ![gif-of-webapp](./Develop/public/assets/challenge-11.gif) -->
<br/>

## **How to Contribute**
Please feel free to review, refactor and submit a pull request for additional features on my github page: <br/>
https://github.com/alinz07 

### **Credits**
* Much of the code is reused from modules 13 & 14 from the University of Wisconsin-Milwaukee Extended Campus Full-Stack Coding Bootcamp.
