---
layout: post
title: "New changes - almost time to quit beta"
description: "Changes to beta.thinkfoss.com as on 2015 September"
category: blog
tags: ['beta.thinkfoss.com']
---
{% include JB/setup %}

Yeah ! Finally its time that we say goodbye to beta.thinkfoss.com and deploy in www.thinkfoss.com. As of today, on running beta, we get approximately 65 - 80 visits per day for the site, and we have 40 registered users! The numbers are quite funny, but relevant since we are still in beta. 

Let me quote down what all changed last week : 

* Solution requests is now handled via the portal. You can see that at http://beta.thinkfoss.com/index.php#tf-task. A decent tile like view is given for people to see their request, edit and add new stuff 
* AJAX will show students who have enrolled to your courses : Along with the number of students, this was a pretty needy thing, and currently we have it ! Yay ! 
* `Bootstrap js modals` now show up the login screen : I would rate this revolutionary as the existing popover was buggy, and created issues in mobile view. The current modal is neat, and give all the necessary functionalities as ever 
* New card layout for course listing : Course details are shown up neatly using `Bootstrap thumbnails` which include 'Number of Students enrolled', 'Edit/Delete options' and more stuff. You should definitely check out http://beta.thinkfoss.com/portal/student/viewAllCourses.php
* New interface for portal home page : Due to complaints that people getting lost inside the portal, we have bootstrap thumbnails guiding users in http://beta.thinkfoss.com/portal/portal.php 


To Do: 
* Integrate payment gateway, and shift to production in the following week. 

If you find bugs, please do report at phab.thinkfoss.com

Cheers!


