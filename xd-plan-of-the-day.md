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

## [BACK TO MAIN](https://github.com/MilitaryMobile/xd-regression-test/blob/master/README.md)
