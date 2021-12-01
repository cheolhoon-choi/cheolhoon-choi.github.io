---
layout: project
type: project
image: images/hit.png
title: HIT(Hawaii Trails) 
permalink: projects/HIT
# All dates must be YYYY-MM-DD format!
date: 2021-11-30
labels:
  - Software engineering
  - Javascript
  - Meteor
  - React Native
  - Traffic Data
  - Hacc 2021
  
summary: HACC(Hawaii Annual Code Challenge) 2021. HIT is a hiking trail application that allows users to view information about trails on their mobile phones.
---
## Links
DevPost: [Hanabata-Code](https://devpost.com/software/hanabata-code) <br />
GitHub Repository: [HIT Github Repo](https://github.com/HACC2021/Hanabata-Code) <br /> <br />

## Overview
<br />
<p align="center">
  <img class="ui image" src="/images/map.png" width="50%" height="40%"/>
</p>
HIT is a hiking trail application that allows users to view information about trails on their mobile phones. Point marks on the map indicate how congested the trail is.
Users can also select a trail on the map to see detailed data such as when the trail is less likely to be busy. Users will also have the ability to manually check in to a trail and log the hike to their profile. 
Eventually, performing a check in will award the user points. Users will receive more points when they check in on a non-congested trail course.
This will encourage users to visit trails which have not had any check-ins for the day. Users can donate using their own points.
<br /><br />

                                                     
## Development
<br />
<p align="center">
  <img class="ui image" src="/images/system.png" width="60%" height="50%"/>
</p>
HIT contains two application. The server and admin app are written using the Meteor framework for web. The user app is written using React Native for smart phone, and it will be compatible with both iOS and Android devices.
<br />
The list of hikes was retrieved from the eHawaii.trails.gov API as a JSON file. This data was then stored in our server. Next, we found data for busy times for the hikes through two sources: Google Maps and BestTime.app. 
This data is collected using anonymized cell phone data. 
<br /><br />


## My Contribution
<br />
<p align="center">
  <img class="ui image" src="/images/hit-home.png" width="30%" height="30%"/>
</p>
At the start of the project, I added a trail course to the Meteor using the image upload feature, and I worked on the landing part.<br />
It was my first time using React Native, but I learned the React hook and applied it to ui without data. I was in charge of the home screen of mobile, so that the functions of React Native appeared on the home screen.
<br />
In addition, I modified the ㅓson file on the trail that was not displayed on the map so that the contents of the trail added from Meteor could be applied to the mobile.
<br /><br />


## What I learned
<br />
This was my first project using React Native using Metor as a backend server, so I was able to gain a lot of technical experience through HACC(Hawaii Annual Code Challenge). 
<br />
Our team had their own roles and everyone worked hard on their duties. However, there were many difficulties due to new learning skills. Our team's leader tried to solve the difficulties of the team members. Thanks to his efforts, the team members were able to easily accept it without fear of learning new technical skills.
<br />
Above all, I learned that communication between team members is really important while working on the project. We had problems at the beginning of the project, but we were able to solve the difficulties through active communication. 
<br />
Through this project, I was able to learn a lot technically skills and the importance of communication.
<br /><br /><br />

