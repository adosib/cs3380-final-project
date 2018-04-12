# cs3380-final-project

## Team Members:
  * **Sohaila Bakr**
  * **Ado Sibalo**
  * **Derek Rogers** 
  
## **Application Description**
  Description of application goes here  

## **Database Schema**
  #### events
  |Field      |Type       |Null?   |Default |Key        |
  |-----------|-----------|--------|--------|-----------|
  |id         |INT        |NOT NULL|None    |Primary Key|
  |title      |VARCHAR(40)|NOT NULL|NewEvent|None       |
  |description|MEDIUMTEXT |NULL    |None    |None       |
  |weight     |DOUBLE     |NOT NULL|1       |None       |
  |eventDate  |DATETIME   |NOT NULL|None    |None       |
  |dateCreated|DATETIME   |NOT NULL|NOW()   |None       |
  
  #### going
  |Field   |Type       |Null?   |Default |Key        |
  |--------|-----------|--------|--------|-----------|
  |id      |INT        |NOT NULL|None    |Primary Key|
  |userID  |INT        |NOT NULL|None    |None       |
  |eventID |INT        |NOT NULL|None    |None       |
  |message |MEDIUMTEXT |NULL    |None    |None       |
  
  #### groups
  |Field      |Type       |Null?   |Default |Key        |
  |-----------|-----------|--------|--------|-----------|
  |id         |INT        |NOT NULL|None    |Primary Key|
  |name       |VARCHAR(30)|NOT NULL|NewGroup|None       |
  |description|MEDIUMTEXT |NULL    |None    |None       |
  
   #### membership
  |Field      |Type       |Null?   |Default |Key        |
  |-----------|-----------|--------|--------|-----------|
  |id         |INT        |NOT NULL|None    |Primary Key|
  |groupID    |INT        |NOT NULL|None    |None       |
  |userId     |INT        |NOT NULL|None    |None       |
  |role       |VARCHAR(20)|NOT NULL|member  |None       |
  |dateJoined |DATETIME   |NOT NULL|NOW()   |None       |
  |dateLeft   |DATETIME   |NULL    |None    |None       |
  
   #### users
  |Field      |Type        |Null?   |Default |Key        |
  |-----------|------------|--------|--------|-----------|
  |id         |INT         |NOT NULL|None    |Primary Key|
  |username   |VARCHAR(20) |NOT NULL|None    |None       |
  |password   |VARCHAR(128)|NOT NULL|None    |None       |
  |first_name |VARCHAR(30) |NOT NULL|None    |None       |
  |last_name  |VARCHAR(30) |NOT NULL|None    |None       |

## **Entity Relationship Diagram (ERD)**
  ERD goes here  

## **Where CRUD happens:**
* Create:
* Read:
* Update:
* Delete:

## **Video Demonstration**
  Video demonstration goes here  
  
