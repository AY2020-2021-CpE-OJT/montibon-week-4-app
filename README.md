# montibon-week-4-app
Phonebook Application Task 4 Week 4: Modify and Delete Contacts

Application starts at Display Contacts Screen by default

Display Contacts shows the first and last name, then the phone numbers of each contacts in a Card with two Floating Action Buttons, one for edit and one for delete

Pressing the edit button proceeds to the Update Contact Screen which by default starts with Textformfields with the contact information as the intial values, a suffixIcon for the phone numbers that if pressed, deletes the text form field if there are multiple or clears the data inside the textformfield if only one remains

At the bottom there are two textbuttons one for adding extra phone numbers and the other for saving changes. Pressing the former adds an empty textformfield while the latter saves the changes to the database and returns to the Display Contact Screen

Editing the first or last name into null shows a Snackbar that warns the user of the invalid input

The user can modify both first and last names, edit, add or remove phone numbers, and then save the changes or simply exit from the screen by pressing back or the back button without affecting the document information

The user can also add as many phone numbers as he wants and even if the textformfields are null, it will be automatically deleted if the save button is pressed

The second floating action button in the Display Contacts Screen is the delete button which on press, shows an alert dialog that asks for confirmation about the user's decision

Hitting 'Confirm' deletes the document from the database, pops the alert dialog, and refreshes the Display Contacts Screen

Hitting 'Cancel' simply pops the alert dialog

At the bottom right is an Add floating action button that is used to create another contact
