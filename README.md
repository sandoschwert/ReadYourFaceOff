# Sandi Schwert Individual Project

This repository is and application for Read Your Face Off, a reading program FOR ADULTS. 

### Problem Statement

Remember when you were a kid and the local library hosted their summer reading program??  Yeah??  Well this one is for adults only and is ALL YEAR ROUND.  [goodreads.com](https://www.goodreads.com/) is a great resource for keeping track of what you're reading and what your friends are reading but it lacks the ability to connect locally, with things like Happy Reading Hour, and Sunday Reader's Brunch, and Beach Reading with Cocktails.  Read Your Face Off will allow you to find reading groups in your area and connect with them online, create challenges and help each other meet those challenges, but more importantly to connect with them IRL!  It's like [meetup.com](https://www.meetup.com) and goodreads made a baby!

Screenshots from GoodReads and Meetup:

![My Books](images/MyBooksGoodreads)

![My Upcoming Events](images/meetupScreenshot)


### Project Technologies/Techniques 

* Security/Authentication
  * Admin role: create/read/update/delete (crud) of all data including readers and groups
  * User role: submit books and reviews, join goups
  * All: anyone can search for and view nearby reading groups (no login)
* Database (MySQL and Hibernate)
  * Store users, groups, and roles
  * Store reading challenge information
  * Store group announcements, surveys, upcoming events
* Web Services or APIs
  * Google Maps for group locations
  * Goodreads for book synopsis and cover art
* Bootstrap
* Logging
  * Configurable logging using Log4J. In production, only errors will normally be logged, but logging at a debug level can be turned on to facilitate trouble-shooting. 
* Site and database hosted on AWS
* Unit Testing
  * JUnit tests to achieve 80% code coverage
* Independent Research Topic
  * TBD

### Design

* [Screen Design](DesignDocuments/Screens.md)
* [Application Flow](DesignDocuments/applicationFlow.md)
* [Database Design](DesignDocuments/databaseDiagram.png)

### [Project Plan](ProjectPlan.md)

### [Time Log](TimeLog.md)
