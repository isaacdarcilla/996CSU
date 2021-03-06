# Technical Support System
Technical Support System developed under MIS

[![Build Status](https://travis-ci.org/electron/electron-api-demos.svg?branch=master)](https://tsrf.epageant.x10.bz)
[![JavaScript Standard Style](https://img.shields.io/badge/code%20style-standard-brightgreen.svg?style=flat)](http://standardjs.com)

### Introduction

We’ve created this admin panel for everyone who wants to create request for technical support. Our mission is to deliver a user-friendly, clear and easy-to-use system, that can be used by both, MIS Officers and employees of Catanduanes State University. The only requirement is a basic computer knowledge—as a reward, you’ll be able to manage and visualize different types of data in the easiest possible way!

### Acknowledgement

This project was documented, designed and developed by <a href="https://facebook.com/isaacdarcilla">Isaac</a> as part of his internship at Management Information Services in year 2019.

![SS](https://github.com/isaacdarcilla/SYSCSU/blob/master/Capture.PNG)

### Contributors
Here are the developers and testers who have contributed to this project.

Officer in Charge

* [Joey V.  Casim](https://www.facebook.com)—Officer in Charge at Management Information Services

Developer

* [Isaac](https://www.facebook.com/isaacdarcilla)—College of Engineering, Department of Computer Engineering

Penetration Testers & Quality Assurance
                        <ul>
                          <li><a href="https://www.facebook.com/jovicabengona?refid=18&__tn__=R">Jovic Laurena Abengona</a>—suggest edit in the datatable for mobile optimization.</li>
                          <li><a href="https://www.facebook.com/tagapandan?refid=18&__tn__=R">Erwin Dulog</a>—reported a bug in the login form username non-case sensitive input fields. </li>
                          <li><a href="https://www.facebook.com/dinom.myer?refid=18&__tn__=R">Dino Myer</a>—help publish a report in the Blind SQL and XSS vulnerality of the system</a>.</li>
                          <li><a href="https://www.facebook.com/variacyberorg/?__tn__=R">Varia Cyber Security</a>—a group of White Hats, Cyber Security Professional and Cisco Global Ops Scholar who helped test the security of the system.</li>
                          <li><a href="https://www.facebook.com/frnklnsrrno?__tn__=R">Franklin</a>—reported a vulnerability in the <code>print.php</code> page in the admin side which escalated access to the database. Also reported an XSS insecurity to the admin and employee text field.</li>
                          <li><a href="https://www.facebook.com/pajares.rickyboy?refid=18&__tn__=R">Ricky Martija Pajares</a>—reported a SQL Injection insecurity in the text/output fields.</li>
                          <li><a href="https://www.facebook.com/lazydeveloper.ph?refid=18&__tn__=R">先輩 悲しい</a>—reported XSS vulnerability and suggest a solution using <code>htmlentities()</code>.</li>
                          <li><a href="https://www.facebook.com/kenneth.regalado?refid=18&__tn__=R">Kenneth Regalado</a>—help suggest changes in the Password Reset page to minimize upto 8 characters.</li>
                        </ul>                 
                        
### Bugs & Feature Request

**Bug #01** (Reported April 23, 2019) Bug in the datatable not compatible with the Javascript. <br>
**Bug #02** (Reported May 26, 2019) Firefox Browser version 33+ not currently supported. <br> 
**Feature #01** (Reported May 14, 2019) Recommends realtime notification module for the Administrator.<br> 
**Feature #02** (Reported May 20, 2019) Recommends activity logging in the system for auditing. 

### Software Changes & Updates

Version 0.1.0
* Initial released on April 12, 2019
* Update the Database diagram
* Create Data flow diagram of the system
* Dashboard page Respond to Request bug/issue that creates multiple data insertion fixed
* Added 3 status: Pending, Responded and Fixed
* Changes in status: No Fixed status until MIS remarks is filled up

Version 0.1.1
* Released on April 17, 2019
* Change to Datatable instead of Static table in the Administrator side
* Debug and fixed error in the SQL database

Version 0.1.8
* Released on April 23, 2019
* Removed and fixed the bug in the datatable not compatible with the Javascript require.js
* Added a new Profile page in the employee side, employees can now view/create requests, update their profile, and print request form
* Employee can now give feedback to the response if they accidentally close the form

Version 0.2.0
* Released on April 25, 2019
* Fixed bugs in the Feedback form where data submitted failed to insert in the database
* Added a feature: Reports can now be sorted by Months

Version 0.2.2
* Released on April 27, 2019
* Update the database and added a column named date_str
* Fixed bugs in the data insertion less than 255 characters

Version 0.2.6
* Released on May 7, 2019
* Added a feature: Employee can now change their password in Password Reset page
* Added a feature: Reports from the previous years can now be generated
* Started creating Notification System
* Test the system online

Version 0.3.0 
* Released on May 12, 2019
* Added Documentation page
* Added a feature: Holiday notification and reminder added

Version 0.3.2
* Released on May 20, 2019
* Fix the button when submitting
* Added a feature: Added Annual Requests Graph in reports for visualization
* Added a feature: You can now change the graph type to line, bar, step or spline
* Administrator can now view annual total requests
* Added a feature: Employee who logged in for the first time can now setup their own account
* Redesigned the Profile page of the employee

Version 0.3.3
* Released on May 22, 2019
* Employees can now view the documentation
* Administrator can now filter data by year and ensure the website loads fast
* Administrator can now filter their response by months
* Updated the links
* Fix bugs in linking
* Fix bugs in View Mode
* Optimized select option in Employee page

Version 0.3.4 
* Released on May 23, 2019
* Added timer in the Admin page
* Fixed the bugs in Datatable in which ordering is not working

Version 0.3.6
* Released on May 27, 2019
* Added a feature: Employee can now log in using their usernames
* Added a feature: Employee can see setup guides in the Account Setup
* Added a feature: Employee can now update their user profile settings
* Fix bugs in the setup page and optimized user data input
* Change the session encryption to PASSWORD_BCRYPT hash

Version 0.3.8 (latest) 
* Released on May 31, 2019
* Added a feature: **Night Mode**
* Added a feature: Employee can only update their account in every 60 days
* Added a feature: Super admin privelege can now add new administrators
* Added a feature: Super admin privelege can now add new employees
* Added a feature: Administrator can now update their accounts
* Redesigned the My Profile modal and added an Edit Profile button
* Fix bugs in the graph and grid view link

### Bug Hunting

Contribute? [Be a beta tester](http://tsrf.epageant.x10.bz)
