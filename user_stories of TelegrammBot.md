#Telegram Bot Specification

###Information about the "BirthdayBot`

* This telegram bot is necessary to save the date of birth of friends,
relatives or other people.
* The main goal of the project is to be able to enter data about the birthday
person in the format first name last name degree of kinship date of birth day month year, phone number.
* When the birthday date is approaching, get information about those who have a birthday today.



## User story:

### Narrative
* As a telegram bot user
* I want to save information about a person's birthday in telegram bot
* So that I will be notifide about the person birthday by telegramm bot beforehand to be able to congratulate this person in time

### Acceptance criteria
####show help scenario

* Given a user initiated an interaction with a bot
* When the user chooses to get help
* Then the bot shows help message 

___
#### user adds a reminder scenario
* Given a user selected an option to add reminder
* Than The telegramm bot asks the user: first name,last name,Personality description,date
* When user entered everything corectly 
* Then bot saves this information in database 
* And bot shows the user a message "Reminder was added"
* And bot shows the main menu
___
####scenario show active reminders
* Given a user selected an option to show active reminders
* Then The telegramm bot will display all active birthday dates


#### show past reminders scenario
* Given a user selected an option to show past reminders
* Then The telegramm bot will display all pass birthday dates


#### double reminders scenario
* Given a user selected an option to add reminder
* When the user entered the information presented in  memory
* Then The telegram bot will display message about double data  

#### user remove the reminder scenario
* Given a user selected an option to remove the reminder about birthday day
* When The telegramm bot asks the user: first name,last name
* Then bot delited information from memory

#### add a notification target scenario