

# <center>Harmedia Software Requirements Document</center>

## 1. Introduction
### 1.1. Purpose
This document describes the software requirements for a web based video synchronization platform called Harmedia.  This specifications is intended for the designer, developer and maintainer of the Harmedia system.

### 1.2. Scope
The Harmedia video synchronization platform **(HVSP)** will be a web based platform that is used to synchronize video for multiple clients.  Users will be able to create their own channel and moderate/manage it.  Within each channel there will be a video queue where elected people can remove, insert, and modify videos in the queue.  Furthermore, in every channel there can be a channel guru and they will have access to modified the video being synchronized state.

### 1.3. Overview of Document
The remainder of this document will be organized as followed: In the following section there will be definitions that are vital for one to understand how HVSP will work.  Chapter 2 will contain the general descriptions of HVSP.  Lastly, Chapter 3  will identify the specific functional requirements, the external interfaces and the performance requirements of the HVSP.

### 1.4. Definitions
<ul>
  <li>
    <dt>Terms go here</dt>
    <dd>Definitions for terms go here!</dd>
  </li>
</ul>

<hr />

## 2. General Descriptions

### 2.1. Overview
To give a short overview of the functionality of the HVSP the following user scenarios are provided:
<!-- Sipp's Section -->
* User System <br />
&nbsp; <u>_Sign Up:_</u> <br />
&nbsp;&nbsp;&nbsp;&nbsp; 1. User is brought to the front page where they are prompted to either login or sign up<br />
&nbsp;&nbsp;&nbsp;&nbsp; 2. User clicks button to Sign up, and is taken to a page to enter their information<br />
&nbsp;&nbsp;&nbsp;&nbsp; 3. User enters basic personal information(Name, Age, Gender, Username, Password, Email)
into appropriate text field.<br />
&nbsp;&nbsp;&nbsp;&nbsp; 4. Username is checked against the database to ensure that Username is not already in use. If
it is, then User is prompted to pick a different Username. <br />
&nbsp;&nbsp;&nbsp;&nbsp; 5. Upon completion of information form, information is entered into database and user is directed
to home page. <br />
<br />
&nbsp; <u>_Log-in:_</u> <br />
&nbsp;&nbsp;&nbsp;&nbsp; 1. User is brougt to front page wher they are prompted to either login or sign up <br />
&nbsp;&nbsp;&nbsp;&nbsp; 2. User enters Username and Password into appropriate text fields and presses "enter" 
button.<br />
&nbsp;&nbsp;&nbsp;&nbsp; 3. Username and Password combination are checked against database. If there is no match in the 
database, user is prompted to attempt login again. <br />
&nbsp;&nbsp;&nbsp;&nbsp; 4. If Username and login are valid, User is taken to home page. <br />
<br />
&nbsp; <u>_Log Out:_</u> <br />
&nbsp;&nbsp;&nbsp;&nbsp; 1. User presses "Log Out" button at the top of the screen <br />
&nbsp;&nbsp;&nbsp;&nbsp; 2. User is prompted to confirm that he would like to log out <br />
&nbsp;&nbsp;&nbsp;&nbsp; 3. If user selects "no" button, he remains on his current page and dialog box closes
&nbsp;&nbsp;&nbsp;&nbsp; 4. User selects "yes" button, and is taken to the front page. <br />
<br />
&nbsp; <u>_Remove User:_</u> <br />
&nbsp;&nbsp;&nbsp;&nbsp; 1. User selects "delete profile" button on their profile page <br />
&nbsp;&nbsp;&nbsp;&nbsp; 2. User is prompted to confirm that he would like to delete his account. <br />
&nbsp;&nbsp;&nbsp;&nbsp; 3. User selects "confirm" and User is taken to front page <br />
&nbsp;&nbsp;&nbsp;&nbsp; 4. User's account information is deleted from Database. <br />
<br />
&nbsp; <u>_Set Global User Level:_</u> <br />
&nbsp;&nbsp;&nbsp;&nbsp; 1. System Administrator searches database for particular User. <br />
&nbsp;&nbsp;&nbsp;&nbsp; 2. Administrator sets user privilage to 'admin', allowing them access to all rooms. <br />
&nbsp;&nbsp;&nbsp;&nbsp; 3. Administrator saves changes, and user has new privilages upon next log in. <br />
<br />
<!-- Christian's section -->
* Channel / Room Browser <br />
&nbsp; <u>_Search For Room By Name:_</u> <br />
&nbsp;&nbsp;&nbsp;&nbsp; 1.  User types in the room he or she wishes to search for and clicks search. <br />
&nbsp;&nbsp;&nbsp;&nbsp; 2.  System then searches for rooms that contain either that tag or name includes the string that was inputted and then list them. <br />
&nbsp;&nbsp;&nbsp;&nbsp; 3.  If no results were found.  Then the system will just display a message stating "No results found!"<br />
<br />
&nbsp; <u>_List Rooms By Number of Users in Room:_</u> <br />
&nbsp;&nbsp;&nbsp;&nbsp; 1. User can select an option to list channels by viewer number (both ascending and descending)<br />
&nbsp;&nbsp;&nbsp;&nbsp; 2.  The system will then list channels by first viewer number (either ascending or descending depending on what the user chose) and then if the channels have the same number of viewers it will then sort the ones with the same number of viewers alphabetically.<br />
<br />
<!-- Should we take into account error cases? -->
&nbsp; <u>_Make a New Room (channel):_</u> <br />
&nbsp;&nbsp;&nbsp;&nbsp; 1.  User hits the option to create a room (channel). <br />
&nbsp;&nbsp;&nbsp;&nbsp; 2.  This system will then display a form with the fields Room title, a checkbox of whether or not one wants to make room private (room has a password) and if they check the private box a new field will appear that will be a password field.  Lastly, at the bottom of the form there will be a create (submit) button. <br />
&nbsp;&nbsp;&nbsp;&nbsp; 3.  If the user successfully created the room a room successfully created message will appear.<br />
<br />
<!-- Should I have an edit room option here (or should Austin have that) -->
<br />
<!-- Austin's Section -->
* Channel/Room General <br />
&nbsp; <u>_Chat:_</u> <br />
&nbsp;&nbsp;&nbsp;&nbsp; 1. Stuff <br />
<br />
&nbsp; <u>_Guru:_</u> <br />
&nbsp;&nbsp;&nbsp;&nbsp; 1. Stuff <br />
<br />
&nbsp; <u>_Owner:_</u> <br />
&nbsp;&nbsp;&nbsp;&nbsp; 1. Stuff <br />
<br />
&nbsp; <u>_Chat Mod:_</u> <br />
&nbsp;&nbsp;&nbsp;&nbsp; 1. Stuff <br />
<br />
&nbsp; <u>_Queue Video:_</u> <br />
&nbsp;&nbsp;&nbsp;&nbsp; 1. Stuff <br />
<br />
&nbsp; <u>_Skip Video:_</u> <br />
&nbsp;&nbsp;&nbsp;&nbsp; 1. Stuff <br />
<br />
&nbsp; <u>_Pause/Play Video:_</u> <br />
&nbsp;&nbsp;&nbsp;&nbsp; 1. Stuff <br />
<br />


### 2.2. Product Perspective
[This is the need(s) the product will serve, the primary stakeholders, and the developers.  Also note its characteristics]

### 2.3.  Product Function


### 2.4. User Characteristics
### 2.5. Assumptions and Dependencies

<hr />
## 3. Requirements
### 3.1. Functional Requirements
#### 3.1.1. General Requirements
#### 3.1.2. Temp requirements

### 3.2. External Interface Requirements

### 3.3.  Performance Requirements
