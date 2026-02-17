---
name: User Story
about: Template containing the required information for writing good user stories
title: ''
labels: ''
assignees: ''

---

**As a** new user  
 **I need** create an account,  
 **So that** I can access the application's features
   
 ### Details and Assumptions
 -user has a valid email address
  -Registration service is available
   
 ### Acceptance Criteria  
   
 ```gherkin
 Given a new user visiting the application
 When the user submits valid registration information
 Then an account is created successfully and the user is logged in
 ```
