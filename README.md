# Regression Test
## Directions
####Go through the steps in order, if bug occurs report the step number to the #xd-bugs channel on slack. 
### Happy Hunting!



## 1. Navigate to the XD [Login page](http://demo.crossdeck.us/crossdeck/login) (completed)

### 1.1. Test the Email input box
#### 1.1.1. input-email: "admin.com" --> click [log in]  
Response: "Email address in not valid"
#### 1.1.2. input-email: "admin@admin" --> click [log in] 
Response: "Email address in not valid"
#### 1.2.3. input-email: "mandy@hotmail.com" --> input-password: "1234" 
Response: pop up displaying "Email Address not found"
#### 1.2.4. input-email: "admin@admin.com" --> click [log in] 
Response: under the password box "Enter your password"

### 1.2. Test the Password input box
#### 1.2.1. input-password: "" --> click [log in]
Response: "Enter your password"
#### 1.2.2. input-password: "12" --> click [log in]
Response: "Password is not valid"
#### 1.2.3. input-password: "admin" --> input-email: "admin@admin.com" --> click [log in]
Response: succesful login to crossdeck



## 2. CLASSROOM

### SKIP -- Application not yet completed



## 3. WATCHBILL 

### SKIPP -- Application not yet completed 



## 4. PLAN OF THE DAY

### 4.1. Test the Side Navigation Button (Hamburger Button)
#### 4.1.1. Click the [Hamburger] button (top left corner) 
response: Side Navigation view slides out from the left
#### 4.1.2. Click anywhere outside of the Side Navigation view
response: Side Navigation view slides out of view.

### 4.2. Test Event Add
#### 4.2.1. Click the [+] button near the top right to add an event
Response: The add event view shows up.
#### 4.2.2. Click the [save] button
Response: **BUG #18**
#### 4.2.3. Click [+] --> Click the [cancel] button
Response: Calendar view pops back up with no event created.
#### 4.2.4. Click [+] --> Fill out the event fields --> click [cancel]
Response: Calendar view pops back up with nothing changed.
#### 4.2.5. Click [+]
Response: Event fields should be empty
#### 4.2.6. Fill out event fields --> Click the [save] button
Response: Calendar view appears with new event created in the correct time with the correct information. 

### 4.3. Calendar Navigation Buttons Navigation Buttons([today], [<][>])
#### 4.3.1. Click [>] 
Response: Calendar moves to the next day, date in top left changes to next date.
#### 4.3.2. Click [today]
Response: Calendar view jumps back to the current day.
#### 4.3.3. Click [<] 
Response: Calendar moves to the previous day, Date changes to that of the previous day.

### 4.4. Calendar view
#### 4.4.1. Click an event
Response: Information for the event is displayed above the calendar, event color on calendar turns yellow. 
#### 4.4.2. Click [x] in the top right corner of the event info box.
Response: Event Information box disappears, event on calendar turns back to original color.
**BUG #21** calendar event color doesn't change back. 
#### 4.4.3. click and drag one of the events up and down.
Response: event moves time slots with your curser. 
#### 4.4.4. click the little black double bar icon located at the center bottom of an event and drag up and down.
Response: event length will change with the dragging of your curser.



## 5. WORKLIST

### 5.1. Test the Side Navigation Button (Hamburger Button)
#### 5.1.1. Click the [Hamburger] button (top left corner) 
Response: Side Navigation view slides out from the left
#### 5.1.2. Click anywhere outside of the Side Navigation view
Response: Side Navigation view slides out of view.

### 5.2. Test Add an Item
#### 5.2.1. Click [Add an Item...]
Response: opens the add an item view:
#### 5.2.2. Click [save]
Response: **BUG #22**
#### 5.2.3. Fill out the input boxes --> click [save]
Response: switches back to main worklist view, new item is added.

### 5.3. Test Items
#### 5.3.1. click any of the items in worklist.
Response: worklist item view pops up.
#### 5.3.2. click the empty circle in the top left corner of the item.
Response: circle turns blue and has a white check, top right corner drop down changes to "in progress"
#### 5.3.3. click the blue circle check box in the top left corner
Response: turns green, top right corner drop down changes to "complete"
#### 5.3.4. click the [Add a comment...] line
Response: opens a text input box.
#### 5.3.5. add a comment --> press enter
Response: comment is added with name, date and time stamp of comment.
#### 5.3.6. click the paper clip button
Response: camera view comes up.
#### 5.3.7. click the picture
Response: switches back to worklist item view, picture is added with name, date, time stamp.
#### 5.3.8. click the blue menu button in the top right corner
Response: switches back to main worklist view
#### 5.3.9. click the worklist item you were just adding items too.
Response: worklist item view shows up with all of the items you have added still there. 
#### 5.3.10. click the crossdeck menu button (top center of top menu bar)
Response: takes you back to crossdeck home screen.



## 6. Messages

### SKIP -- Application not yet completed



## 7. PQS

### 7.1. Test the Side Navigation Button (Hamburger Button)
#### 7.1.1. Click the [Hamburger] button (top left corner) 
Response: Side Navigation view slides out from the left
#### 7.1.2. Click anywhere outside of the Side Navigation view
Response: Side Navigation view slides out of view.

### 7.2. Test PQS Item
#### 7.2.1. click on a pqs item.
Response: pqs item view pops up
#### 7.2.2. click [tap to sign]
Response: signature box pops up
#### 7.2.3. sign in the box
Response: signature appears in box
#### 7.2.4. click [close]
Response: signature box closes
#### 7.2.5. click [tap to sign]
Response: signature box opens up and is empty
#### 7.2.6. sign in the signature box --> click [clear]
Response: signature box clears
#### 7.2.7. sign in the signature box --> click [save]
Response: signature becomes permanent with time stamp and name of signer, top bar percentage circle increases. 
#### 7.2.8. click the top pqs bar
Response: takes you back to main pqs view, completed percentage is now the new completed percentage. 
#### 7.2.9. click the crossdeck menu button (top center of top menu bar)
Response: takes you back to crossdeck home screen.



## 8. TRAINING

### SKIP -- Application not yet completed



## 9. ZONE INSPECTION

### 9.1. Test the Side Navigation Button (Hamburger Button)
#### 9.1.1. Click the [Hamburger] button (top left corner) 
Response: Side Navigation view slides out from the left
#### 9.1.2. Click anywhere outside of the Side Navigation view
Response: Side Navigation view slides out of view.

### 9.2. Test Zone Inspection View 
#### 9.2.1. click on a zone inspection
Response: takes you to the "zone inspection" view
#### 9.2.2. click [add a deficiency]
Response: "add deficiency" pop up box appears. 
#### 9.2.3. click cancel
Response: "add deficiency" pop up box disappears. 
#### 9.2.4. click [add] a deficiency 
Response: "add deficiency" pop up box appears.
#### 9.2.5. click [category] drop down and select an option
Response: selected option now appears in the box.
#### 9.2.6. click [space] drop down and select an option
Response: selected option now appears in the box.
#### 9.2.7. add a description
Response: Description box is filled out
#### 9.2.8. click the [+], then click the [camera] button
Response: camera capture view appears. 
#### 9.2.9. click the photo
Response: picture is taken
#### 9.2.10. click [ADD]
Response: deficiency is added
#### 9.2.11. click one of the deficiencies to view. 
Response: efficiency view pop up appears. 
#### 9.2.12. click [close]
Response: efficiency view pop up disappears.
#### 9.2.13. under "Repair Levels:", under "Material/Habitability:" click 1 ,2 and 3
Response: the number clicked turns blue and the other numbers are grey. 
#### 9.2.14. under "Repair Levels:", under "Cleanliness:" click 1, 2 and 3
Response: the number clicked turns blue and the other numbers are grey. 
#### 9.2.15. under "Repair Levels:", under "Safety/Damage Control:" click 1, 2 and 3
Response: the number clicked turns blue and the other numbers are grey. 
#### 9.2.16. under "Repair Levels:", under "Preservation:" click 1, 2 and 3
Response: the number clicked turns blue and the other numbers are grey. 
#### 9.2.17. under "Overall Grade:" click Unsatisfactory
Response: "Re-inspection date selection" field appears.
#### 9.2.18. under "Overall Grade:" click satisfactory and Outstanding
Response: "Re-inspection date selection" field is hidden and the selected button turns blue.
#### 9.2.19. click [save]
Response: saves changes.
#### 9.2.20. click [<-] (back) button
Response: returns you to the zone inspection view.

### 9.3. Add Zone Inspection
#### 9.3.1. click [+add zone inspection] 
Response: brings you to the "add zone inspection" view
#### 9.3.2. click [submit]
Response: alert notifying you that you can't create a blank zone inspection
#### 9.3.3. fill out information blocks
Response: Information blocks are now full of text
#### 9.3.4. click [<-] button 
Response: returns you to main zone inspection view
#### 9.3.5. click [+add zone inspection] --> fill out information blocks
Response: information blocks are filled out
#### 9.3.6. under "Overall Grade:" click Unsatisfactory
Response: "Re-inspection date selection" field appears.
#### 9.3.7. under "Overall Grade:" click satisfactory and Outstanding
Response: "Re-inspection date selection" field is hidden and the selected button turns blue.
#### 9.3.8. click submit
Response: returns to the main zone inspection view and has added your newly created zone inspection.



## 10. 3M - PMS

### 10.1. Test the Side Navigation Button (Hamburger Button)
#### 10.1.1. Click the [Hamburger] button (top left corner) 
Response: Side Navigation view slides out from the left
#### 10.1.2. Click anywhere outside of the Side Navigation view
Response: Side Navigation view slides out of view.

### 10.2. test 3M - PMS items
#### 10.2.1. click an item
Response: item opens up in new window. 
#### 10.2.2. click the crossdeck menu button (top center of top menu bar)
Response: takes you back to crossdeck home screen.



## 11. REPAIRS

### SKIP -- Application not yet completed



## 12. LIBRARY

### 12.1. Test the Side Navigation Button (Hamburger Button)
#### 12.1.1. Click the [Hamburger] button (top left corner) 
Response: Side Navigation view slides out from the left
#### 12.1.2. Click anywhere outside of the Side Navigation view
Response: Side Navigation view slides out of view.

### 12.2. test library items
#### 12.2.1. click an item
Response: item opens up in new window. 
#### 12.2.2. close the item.
Response: item closes
#### 12.2.3. click the edit item button
Response: allows you to edit the item

### 12.3. Test add item
#### 12.3.1. click [+ Add]
Response: add item view pops up
#### 12.3.2. click [cancel]
Response: returns you to main library view
#### 12.3.3. click [+ Add] --> fill out info --> click [cancel] --> click [+ Add]
Response: returns you to the add item view with empty input boxes.
#### 12.3.3. fill out input boxes --> click [save]
Response: top bars are highlighted in red, "PDF Document is required" appears
#### 12.3.4. **need to complete**



## 13. REFERENCES

### SKIP -- Application not yet completed



## 14. OPERATING PROCEDURES

### SKIP -- Application not yet completed



## 15. SETTINGS

### 15.1. Test the Side Navigation Button (Hamburger Button)
#### 15.1.1. Click the [Hamburger] button (top left corner) 
Response: Side Navigation view slides out from the left
#### 15.1.2. Click anywhere outside of the Side Navigation view
Response: Side Navigation view slides out of view.

### 15.2. Test views
#### 15.2.1. click "list" dot --> click the crossdeck menu button
Response: list circle turned blue, main crossdeck view is now list.
#### 15.2.2. click "settings" --> click the "Tiles" circle --> click the Crossdeck menu button
Response: crossdeck tiled main view appears.
#### 15.2.3. return to settings view --> toggle all applications to off --> click the crossdeck main menu button
Response: only the settings and logout button remain.
#### 15.2.4. return to settings --> toggle all apps back on --> return to crossdeck main menu
Response: all applications return to view.



## 16. MY PROFILE

### 16.1. Test the Side Navigation Button (Hamburger Button)
#### 16.1.1. Click the [Hamburger] button (top left corner) 
Response: Side Navigation view slides out from the left
#### 16.1.2. Click anywhere outside of the Side Navigation view
Response: Side Navigation view slides out of view.

### 16.2 test edit "My Bio"
#### 16.2.1. click [edit]
Response: edit view pops up
#### 16.2.2 **functionality not completed**



## 17. SYSADMIN

### 17.1. Test the Side Navigation Button (Hamburger Button)
#### 17.1.1. Click the [Hamburger] button (top left corner) 
Response: Side Navigation view slides out from the left
#### 17.1.2. Click anywhere outside of the Side Navigation view
Response: Side Navigation view slides out of view.

### 17.2. Test Users View
#### 17.2.1. Test Edit Users
##### 17.2.1.1. click the blue edit button on the left of one of the user profiles
Response: User profile view pops up
##### 17.2.1.2. edit each input box
Response: all input boxes are filled 
##### 17.2.1.4. Click [Take Photo]
Response: photo capture view pops up
##### 17.2.1.5. Click on the camera viewfinder.
Response: photo is taken and you are returned to the profile edit view
##### 17.2.1.5. click [cancel] --> return to the edit view
Response: returns you to the main user profile, then returns you to the profile you were editing without any of your changes being saved.
##### 17.2.1.3. edit each input box
Response: all input fields are filled
##### 17.2.1.4. Click [Take Photo]
Response: photo capture view pops up
##### 17.2.1.5. Click on the camera viewfinder.
Response: photo is taken, you are returned to the profile edit view
##### 17.2.1.6. click [save]
Response: you are returned to the main user profile view, with the account being added. 
#### 17.2.2. Test View Users
##### 17.2.2.1. click the arrow button next to the user edit button.
Response: takes you to profile view screen
##### 17.2.2.2. Click reset
Response: returns you to the main user profile view.
#### 17.2.3. Test Add Users
##### 17.2.3.1. click [+ Add] in the top right corner 
Response: takes you to the add user profile view.
##### 17.2.3.2. fill out all input fields
Response: all input fields are filled out.
##### 17.2.3.3. Click [Take Photo]
Response: takes you to picture capture view
##### 17.2.3.4. Click on the camera viewfinder.
Response: takes photo, returns you to profile add view
##### 17.2.3.5. click [cancel] --> return to the [+Add] view
Response: returns you to the user profile main view without adding a user profile.
##### 17.2.3.6. fill out all input fields
Response: all input fields are filled out
##### 17.2.3.7. Click [Take Photo]
Response: takes you to photo capture view
##### 17.2.3.8. Click on the camera viewfinder.
Response: takes photo, returns you to profile add view
##### 17.2.3.9. click [Save]
Response: returns you to the user profile view with the newly added profile.


### 17.3. Test Roles View
#### 17.3.1. Test Edit Roles
##### 17.3.1.1. Click the blue edit button to the left of one of the roles. 
Response: takes you to the roles edit view. 
##### 17.3.1.2. Fill out all of the input fields
Response: all the input fields are filled out
##### 17.3.1.3. Click [Cancel]
Response: returns you to main roles view without the role being edited.
##### 17.3.1.4. Click the blue edit button to the left of one of the roles.
Response: takes you to the edit roles view
##### 17.3.1.5. Fill out all of the input fields
Response: all the input fields are filled out.
##### 17.3.1.6. Click [Save]
Response: returns you to the main roles view with the role edited. 

#### 17.3.2. Test Add Roles
##### 17.3.2.1. click the [+ Add] button in the top right corner 
Response: takes you to the add roles view. 
##### 17.3.2.2. Fill out all of the input fields
Response: all the input fields are filled out
##### 17.3.2.3. Click [Cancel]
Response: returns you to the main roles view without adding a new role.
##### 17.3.2.4. Click the [+ Add] button in the top right corner 
Response: takes you to the add roles view.
##### 17.3.2.5. Fill out all of the input fields
Response: all the input fields are filled out
##### 17.3.2.6. Click [Save]
Response: returns you to the main roles view with the new role being added.

### 17.4. Test Groups view 
#### 17.4.1. Test Edit Groups
##### 17.4.1.1. click the blue edit button on the left of one of the group profiles
Response: takes you to the edit groups view
##### 17.4.1.2. edit each input box
Response: all input fields are filled out
##### 17.4.1.3. click [cancel] --> return to the edit view
Response: returns you to the edit groups view and all fields are empty
##### 17.4.1.4. edit each input box
Response: all input fields are filled out
##### 17.4.1.5. click [save]
Response: returns you to the main groups view with the group edited
#### 17.4.2. Test View Groups
##### 17.4.2.1. click the arrow button next to the group edit button.
Response: takes you to the groups view view
##### 17.4.2.2. Click reset
Response: returns you to the main groups view
#### 17.4.3. Test Add Groups
##### 17.4.3.1. click [+ Add] in the top right corner 
Response: takes you to the add groups view
##### 17.4.3.2. fill out all input fields
Response: all input fields are filled out
##### 17.4.3.3. click [cancel] --> return to the [+Add] view
Response: returns you to the add view with all input fields empty
##### 17.4.3.4. fill out all input fields
Response: all input fields are filled out
##### 17.4.3.5. click [Save]
Response: returns you to the main groups field with a new group added.


## 18. VTT

### 18.1. Test the Side Navigation Button (Hamburger Button)
#### 18.1.1. Click the [Hamburger] button (top left corner) 
Response: Side Navigation view slides out from the left
#### 18.1.2. Click anywhere outside of the Side Navigation view
Response: Side Navigation view slides out of view.
### 18.2. Test VTT Launch
#### 18.2.1. click one of the VTT's
Response: launches vtt in new window. (this will launch a empty window if the vtt software is not installed) 



## 19. LOGOUT

### 19.1. Test log out
#### 19.1.1. click the "log out" icon
Response: logs you out of crossdeck
