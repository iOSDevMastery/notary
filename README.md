# Mobile Notary App Project Notes
## Introduction
The motivation to create an app for the mobile notary market is appealing because it provides an opportunity to implement several frameworks incrementally.  The MVP can contribute to the mobile notary’s accuracy and productivity.

## Notary Learning Resources
One of the things that caused a bit of hesitance in moving forward with this app is our lack of experience as a mobile notary.  There is a Udemy mobile loan signing courses that will hopefully fill that gap.  The course can be found here: [How to Become a Mobile Notary/Loan Signing Agent](https://www.udemy.com/course/how-to-become-a-loan-signing-agent/)


## MVP
The objective of the MVP can contribute to the mobile notary’s accuracy and productivity.  One sticking point shared by beginners and experienced notaries alike is the danger of missing signatures.  Providing some support to help minimize  this problem might be an excellent first release.

Several epics have been identified in the Jira workflow that will hopefully be a decent starting point for the project. 


## Screens and Functionality
### INITIAL SCREEN 
- The initial view controller will display the following:
- Control to display appointments for the day, the week, or the month.
- Setting the default appointment dates will be a setup option.
- Potential income for appointments
- Income collected for the month.
- Creation of a new appointment.
- Additional fields as needed.

### SETUP SCREEN

### CREATE APPOINTMENT SCREEN

### MANAGE APPOINTMENT SCREEN

### MANAGE DOCUMENT SET SCREEN

### MANAGE CONTACTS

### CONDUCT SIGNING

### FOLLOW-UP AFTER SIGNING

### COMMUNICATION


## Workflow Suggestions
### DEVELOPMENT
- Custom objects should be prefixed with MN (i.e. MNConstants or MNError)
- When declaring types use enums first whenever possible.
- The user interface will be developed programmatically.
- The network manager will be declared as a singleton.
- Access-enabling should accommodate color blindness, changes in text size, contrast.
- Test Driven Development will be employed in the project.

### XCODE
- Use code folding to keep code files clean and easy to navigate.
- Add Mark lies to improve readability
- Some insights about Mark lines: [Xcode Mark lines](https://www.avanderlee.com/xcode/xcode-mark-line-comment/)

### TESTING
- Test Driven Developement will be used with the developement of this project.


### GITHUB REPOSITORY, BRANCHING, AND COMMITS
Branch names and commit messages should include the issue number of the task that the code relates to so that it shows up in Jira.
The issue number can be found in the lower righthand corner of the issue on the NMA board. 

### DOCUMENTATION
JIT, or Just in Time documentation will allow us to begin moving forward with the development of the app immediately while refining the requirements along the way.

## NOTES
**10/15/2021:** Everything presented here are just suggestions.  The goal is to research, exercise, and gain mastery of everything we are using while creating a viable app.  
**10/16/2021:** To make changes to the repo please login as `iosdevmastery`.  
**10/17/2021:** Added content to **Workflow Suggestions** liststing ideas for testing methodology.  

