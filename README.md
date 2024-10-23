**Michael Brookins**

**SDET Program** 

**Phase 3 Project**

**Project Requirements:**
Phase 3 Project – NodeJS, APIs and Databases 

**Overview** 
You have been commissioned to build a new, simple application for managing RF-SMART’s “Library” conference room’s books. Lately there’s been confusion around who’s reading what books, which ones are available in the library conference room, and when they’re expected back. Some employees also would like to leave comments about a book they’ve read and read other’s comments as well. Finally, when a book is accidentally destroyed or lost, nobody is sure who to tell or how to let others know it’s no longer available. 

**Actors:**
1. RF-SMART Employee 
2. Reader 
3. Donor 

**User Stories **
1. As an RF-SMART employee, I would like to view what books could be in the library so that I know what reading material is available. 
2. As an RF-SMART employee, I would like to view comments left on individual books that could be in the library so that I know what Readers think about each one. 
3. As an RF-SMART employee, I would like to view what books are currently in the library so that I know what books I can check out. 
4. As a Reader, I would like to check out a book from the library so that others know I have it and it’s no longer available. 
5. As a Reader, I would like to check in a book back to the library, so it becomes available to other Readers. 
6. As a Reader, I would like to leave comments on a book I have checked out so that others know what I think about it. 
7. As a Reader, I would like to be able to delete a book I have checked out because I’ve lost it, damaged it, or it’s so good that I’m keeping it for myself and don’t want anyone else to have it, ever! 
8. As a Donor, I would like to donate and add a book to the library so others may also read it and know it’s available for check out. 

**Personas: **
Susie Q. 
RF-SMART Employee, Reader 
Age: 26 
Title: Marketing Analyst II 
Department: NetSuite Marketing 
Start Date: 3 years ago, last month 
Favorite Color: Pink 
Has a pet cat named, “Freckles” 
Favorite music is Reggae, hates Nirvana 
_Susie has worked for RF-SMART now for a while and has only been in the library a couple of times for a meeting with another team. She’s recently taken up an interest in growing her leadership skills and asked one of the managers she knew on the OC side, Rebekah, what her recommendations were to grow in this area. Rebekah suggested checking out the library and noted there were lots of books about leadership and management in there. Susie decided to take a break teaching Freckles how to surf on cutting boards and instead focus on reading some good leadership material. She heads to the library and has now spent several hours trying to find a book, combing through the dozens of them in there… If only there was an easy way to see what’s available in a simple app! _

Harry H. 
RF-SMART Employee, Reader 
Age: 62 
Title: Sales Representative 
Department: On-Prem 
Start Date: Last Week 
Favorite Color: Brown 
Has a pet snake, “Jakey”, and a temporary pet mouse 
Favorite music is 60’s era rock, but will tolerate Frank Sinatra
_Harry just started at RF-SMART and is super excited to start making waves in the sales world. He’s heard all about the amazing history of RF-SMART and went into the library during the tour and noticed the super old computer on the bookshelves which brought back memories of a computer he used to have and just threw out last year from the attic which he had forgotten about, along with 80lbs of 5.25” floppy disks containing pirated copies of Oregon Trail.
Harry grabs one of the books on Office 97 to brush up on his word processing skills and amid trying to load the CD-ROM into the 5.25” floppy drive, he ends up scratching the disk beyond repair… If only there was a way to indicate to others that the CD-ROM in that Office 97 training book is no longer good and had to get tossed in the trash!  _

Marissa U. 
RF-SMART Employee, Reader, Donor 
Age: 33 
Title: Sr. Software Developer 
Department: Oracle Cloud 
Start Date: 5 years ago 
Favorite Color: It’s Parameterized and Conditional 
No pets, but can draw them well 
Favorite music is Classical 
_Marissa reads constantly and loves learning. When she’s not drawing or painting to flex her artistic abilities, she’s reading on all sorts of topics. When she finishes a book, she really likes to share it with her peers and others.  She would love to be able to donate the books she has read so anyone at RF-SMART can read them also and be able to share her thoughts and comments for others to read about them. _

**Technical Direction:**
To assist with the design of this application, here are some general guidelines for technical direction and overall design for how to approach this project: 
You will need some **tools**: 
Visual Studio Code (and any plug-ins you may want) 
NodeJS/NPM 
Podman (if using Docker containers) 
You will need a database; this can be created using mySQL or PostgreSQL 
You can use a Docker container for doing this, or 
You can install a database directly on your local machine 
You get to design the schema, tables, etc. that you’ll use based on what you learn 
You will need a JavaScript NodeJS/Express Web App + API Project 
You’re going to be creating both a static web app and REST services 
You’ll need classes to represent your data models, requests, responses, etc. 
You’ll need controllers with actions to represent your REST endpoints 
You’ll need some validation 
You’ll need NPM packages for communicating with your database 
You’ll need settings for the connection string and potentially other things 
You’ll need to store, update, and read data from your database in your code 
You will need a Web App 
The assets for your web app, routes, etc. Should be embedded in the NodeJS/Express Web App from above 
Use your JavaScript skills to create a basic web application 
You’ll be calling your REST API from your web application to perform the various actions 
It doesn’t have to be pretty, but it should be functional 
You will need a TypeScript End-to-End Automation test project 
This will use Playwright with TypeScript 
You’ll use the Page Object Model (POM) pattern 
You’ll need tests that cover the UI 
You’ll need tests that cover the API directly 

See: Test Cases* 
You should be able to run everything “locally” on your machine 
Bonus points for orchestrating them in containers (docker, docker-compose, etc.) 

**Test Cases **
Test Case Constraints / Requirements 
You should use the Page Object Model design pattern in constructing your test bed 
There should be 2 test cases for each use-case presented: 1 for UI, 1 against the API. 
There should also be at least 4 negative test cases, you can distribute the 4 across different use-cases or all on the same use-case. 
Collect data and create artifact after manipulating it in some way (reverse the order, select last 5, etc.)  
Create a broken or non-existent endpoint in the API and test that a happy path test returns a failing test result. 

**Timeline** 
3 months (~12 weeks) 
**Submission** 
1. Commit your code to GitHub for review  
2. Demo individually with your technical partner, and your code will be reviewed - You will be assigned an individual developer or SDET as your technical partner throughout the project. 

**Database** – mySQL or PostgreSQL 
You can use Docker container to do this 
Install Database onto my local machine 
Design schema, tables, etc for library app 
NodeJS/Express API Project 

Create REST services 
Classes to represent my data models, requests, responses, etc 
Controllers with actions to represent my REST endpoints 
Validations / Error Handling 
NPM packages for communicating with your Database 
Settings for the Connection String and other things potentially 
Store/Update/Read Data from my Database to my Code 

Web Application 
Using JavaScript -> Create a Basic Web Application 
Embed this in your same ExpressJS app (it can serve the static assets using middleware) 
Call your REST API from your Web Application to Perform various Actions 
Does not need to be pretty -> MUST BE FUNCTIONAL 

**TypeScript End-to-End Automation Test Project **
Framework: Playwright with TypeScript 
Use Page Object Model (POM) 
Minimum Test Cases = 8 –  
1 - UI Test 
1 - API Test 
4 - Negative Test Cases 
Can be on 1 use-case or multiple use-cases 
1 - Collect Data & Create Artifact after manipulating it in some way (ex. Reverse order, select last 5, etc) 
1 - Create a broken or non-existent endpoint in the API -> test that a happy path test returns a failing test result 

Run Locally on Machine 
You will need to be able to run everything “locally” on my machine 

BONUS POINTS for Orchestrating in Containers (docker, docker-compose, podman, etc) 

FINAL Submission 
Commit Code to GitHub for Review 
Demo Individually to SDETs 
Review Each Other’s Code 
