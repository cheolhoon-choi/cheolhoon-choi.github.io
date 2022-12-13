---
layout: project
type: project
image: images/edu.png
title: eduWrench 
permalink: projects/eduWrench
# All dates must be YYYY-MM-DD format!
date: 2022-06-15
labels:
  - Software engineering
  - Javascript
  - Gatsby
  - Express.js
  - Node.js 
  - SQLite
  
summary: EduWRENCH is a project that teaches parallel and distributed computing topics with informative and interactive activities. 
---
## Links
[eduWrench](https://eduwrench.org) <br />
GitHub Repository: [eduWrench Github Repo](https://github.com/wrench-project/eduwrench) <br /> <br />

## Overview

<p align="center">
  <img class="ui image" src="/images/e-dataFlow.png" width="50%" height="40%"/>
</p>
For this capstone project, we implemented additional features to the pedagogic web application EduWRENCH (https://eduwrench.org). 
EduWRENCH is a project that teaches parallel and distributed computing topics with informative and interactive activities. 
The website currently in production is fully functioning, but there are additional features that can be implemented to improve the overall user experience. 
We implemented a better practice questions widget where users are able to input an answer to a question. 
In addition, we created a form for users to provide feedback for each activity to gauge the satisfaction and usefulness of the activity. 
As a result, activities can be improved and changed based on the user feedback. Users did not have a way to see their progress for each module, so we created a page that tracks the user’s progress. 
Also, we created a global statistics page for the site’s administrator to see the activity feedback and practice question statistics. 
We used JavaScript to build all of the features in the project because the web application stack consists of JavaScript frameworks. 
The frontend of the website is built with Gatsby, a React-based open source framework. The backend is built with Express.js, a Node.js web application framework. 
Lastly, the web application uses SQLite3 for the database. 

<br /><br />

                                                     
## Development
The challenges that we faced implementing the practice question was the handling of the data from the database to the frontend React components and vice-versa. 
We had to figure out how to handle the POST requests in order to get the data from the database to be displayed in the frontend. 
Since EduWRENCH used Express.js, we were able to create application endpoints to respond to the client POST requests. 
In the frontend, we used Axios, a JavaScript package, to make HTTP POST requests from the browser client to the server. 
If we wanted to send data to the server, we had to include a body in the post request and the server needed to respond with a confirmation that it received the request. 
If we did not implement code to make the server respond, the client would eventually stop sending requests because HTTP requests require a response before sending any further requests. 
If we wanted to retrieve data from the server, we had to send a HTTP POST request with the parameters that we want to receive from the database, 
and the server responds with the data that we have requested. We thought about using HTTP GET requests to retrieve that data, 
but since there are a lot of parameters, such as username, email, and practice keys, for the query, it would be more complicated to retrieve the data via GET requests.

<br /><br />


## My Contribution
<p align="center">
  <img class="ui image" src="/images/e-feedback.png" width="100%" height="50%"/>
</p>
A constant objective of EduWRENCH is to improve  the quality of the educational material it provides, but the original site did not allow users to provide any feedback. 
Therefore, I implemented the function of leaving user feedback, and users can leave feedback only after logging in. 
Users can select the usefulness or quality of each module by answering multiple choice questions, and they can provide their opinions by leaving comments to improve the contents of the module. 
If users leave feedback, they can no longer leave feedback for the same module with the completion message. 
EduWrench has a function that helps users easily understand the specific concepts of each module by utilizing simulation activities. 
<br />

<p align="center">
  <img class="ui image" src="/images/e-sFeedback.png" width="60%" height="50%"/>
</p>
The simulation activity feedback was implemented in the same way as the module feedback, but a modal window appears after three simulation runs to allow users to leave feedback for the quality and usefulness of the simulation. 
<br />

<p align="center">
  <img class="ui image" src="/images/e-statistics.png" width="100%" height="50%"/>
</p>
The production EduWRENCH site only displayed usage statistics on the total number of simulation runs, so I added the global statistics to display more information. 
Global statistics included practice question data and feedback data from all users, and we decided to display the data with bar graphs. 
I implemented practice questions to record the problems that users complete or gave up and the number of attempts for each problem. 
The global statistics shows the number of questions answered, and the figures show how many times users have attempted them. 
Regarding user feedback, this page displays users’ thoughts on the usefulness and quality of the modules, and how valuable the simulation activities of each module were.

<br /><br />


## What I learned

The implemented features will improve the learning experience for students on EduWRENCH. After implementing the features and overcoming many challenges, 
we have learned a lot from working on EduWRENCH. We learned how to handle data between the frontend client and the database. 
In addition, we got to implement backend endpoints to handle the frontend POST requests. As we worked on this project, 
we learned about Formik and found out that there are many advantages to creating a form using Formik. Building forms and validation methods with React form hooks was a tedious task. 
However, the Formik library made it easier to get values in form state, submit validations, error messages, and handle form submission. 
As a result, we were able to improve our web development skills by creating new, feature-full React components. 
<br />
All developments above are implemented in a fork of the EduWRENCH repository, and a pull request will be created so that the results from this capstone project become part of the EduWRENCH main repository, 
and then automatically deployed on the live site during the summer 2022. 


<br /><br /><br />
