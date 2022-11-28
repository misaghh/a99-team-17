**DUE:** 2022-12-08T15:00 (End of Exam Period)

Most general questions and an overview of getting your team set up is in this lecture: https://uncch.hosted.panopto.com/Panopto/Pages/Viewer.aspx?id=9007199e-959e-4d98-bcfa-af5500ec9123

**NOTE: You are all each individually responsible for submitting a final self- and team-assessment in addition to your team's submission of the final project. This will be emailed to you in the last week of the semester.**

## Overview

Your team will be responsible for scoping, planning, and designing a PROTOTYPE web application or system.

The app should be fully documented, including setup instructions, full API documentation, and user instructions, as well as your planning workflow (notes, GitHub Project boards, discussions archives, etc.).

Your team will create a <= 3-minute video describing your app to present to the class about your app.
This can be a very basic walkthrough, or a description/presentation of features/use cases, or something else.
Be creative.
Think of it as an opportunity to hone your ability to pitch an idea that you have in prototype (because that is what it is).

## Deliverables

A GitHub repository in the class organization containing your code and documentation and a prototype release package.
Your project should take the form of a Node package, with all of the attendant items associated with that.
The following three script commands should work in your package:

1. `npm install` - Install dependencies for your package.
2. `npm test` - Start app, check that everything can run, and then stop app.
3. `npm run` - Command to bring up all parts of the app/system's server scripts.

Your team is responsible for incorporating the following specifications and deliverables into your final project:

1. Back-end specifications
	1. API built on whatever framework you choose. You can build an API that interacts with other APIs as well in order to integrate them.
	2. API root endpoint at `http://HOST/app/`.
	4. Create (if nonexistent) and interact with a database of users (optional) and interactions (this can be logs, even). If users do not need to login to use your app, then do not worry about a user DB. These can be separate databases for different microservices or separate tables in one database. It is up to your team's decisions.
	5. Database can be of any type you choose.
2. Front-end specifications
	1. Give users the ability to register an account, update their information, see their information somewhere, and delete their account.
	2. Interactions with the front end should be logged in a database. 
3. Database specifications
	1. User database (if relevant) - registration details (username, email address, etc.)
	2. Interaction database - details of user interactions (login history, access logs, etc.)
4. Documentation
	1. License documenation - Choose a license and include it in the repository just like we have been.
	1. README.md file with basic descriptiong, installation requirements/instructions, dependency list, run instructions
	3. `/docs/` directory containing full documentation of every available API endpoint that you create for your app. This directory shoud also house an archive of your planning documentation. 
	2. Code comments (preferably referring to the documentation)
	3. User instructions in the interface
5. Demo video
	1. In order to get credit for this, add a row to the table in the README here and make a pull request
7. Self/group evaluation (Individual group members: this is part of the final exam for the course.)