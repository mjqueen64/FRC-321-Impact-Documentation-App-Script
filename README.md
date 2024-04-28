This repository holds the Google Apps Script code for the FRC 321 Outreach Managment and Impact Documentation System.

It is used in collaboration with this folder of files: https://drive.google.com/drive/folders/11UG0-MoAccn1tr--Hl-rnhAgqLhWXMS-?usp=sharing

Currently there are 4 functions involved in integratting these files.

## Setup
createTimeDrivenTriggers  
Sets up the refresh rate of the google form to allow up to date selections

getItemID
Required to populate google form questions  
currentlys set up to return the item Id of a dropdown menu

## Form Population
eventNamesToForm
populates the forms event dropdown with events from the last 7 days

teamNamesToForm
populates the forms team dropdown with the names of each team provided
