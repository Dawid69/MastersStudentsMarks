# MastersStudentsMarks

# This is an excel file with 3 sheets.

## studentInput:

The main sheet where Data will be entered 

## studentList: 

The output sheet where a list of students will be found 

## lists: 

A sheet holding calculation data and lists used for the Drop down menus. 

# studentInput Sheet: 

This sheet is where the data will be input of each student: 

## Fields: 
    Name:
      Where the student name is entered
    Surname: 
      Where the student surname is entered
    Field choice: 
      Drop down where the Choice of field is chosen
### Section A:
    Masters (Psyc) Mark:
      If the student has completed their M in Psyc then their grade average is entered here. 
    PhD (Psyc) Completed: 
      If the student has completed a Psyc PhD then a one is entered into the field. Otherwise a 0 is entered. 
    University: 
      The university of the student is entered
    Hons:
      Location:
        The location where Hons was completed
      Year: 
        The Year that Hons was attempted
#### Section A Subject Info:
    Name:
      A soft Dropdown of the Subject that is to be entered
    Year: 
      The year Level of the subject
    Grade: 
      The percentage grade that the student received
### Section B: 
    Work Experience: 
      Drop down of the relevant work experience that the student has.
    Academic (Non psycology):
      Drop down of the highest level of academic progress achieved
      
**Section B Work experience will be flagged when exporting student if the experience contains a value Designated as 'other'**

## Using studentInput sheet:
### Meanings of buttons: 
#### New Student: 
  Clears all data and increments a counter to keep track of the studentList sheet
#### Add Subject: 
  Adds the information entered into the Subject info fields to the table on the right hand side. 
#### Undo Subject: 
  Removes the last entered subject and resets the counter. 
  **DO NOT REMOVE AN INCORRECT SUBJECT ANY OTHER WAY!!!!**
#### Export student:
  Sends the entered info to the studentList sheet. 
  
# lists sheet: 
  Here a collection of tables thats values are self evident can be found. 
  
  Also included is the control panel. This data should not be changed unless a mistake was made or other data needs to be changed:
  
## Control panel: 

- Line Counter: A counter used to keep track of the Row Cloumn of stdentList
- Unique Years: The number of unique Years used in the calculation of Section A 
- Current Year: The current year of data input. 
- Y1: total of grades for Year One in section A
- Y2: total of grades for Year Two in section A
- Y3: total of grades for Year Three in section A
- YH: total of grades for Honours in section A
- YM: The average achieved in masters
- YPHD: Whether a PHD was achieved
- Section A: total for section A
- X: The calculated amount of X 
- Work Exp Weight: The weight of work Experience
- Academic Exp Weight: Weight of Academic experience
- Y: Calculated amount of Y
- Final Score: The final calculated Score

***The Other Values in control panel should not be adapted UNDER ANY CIRCUMSTANCES***
