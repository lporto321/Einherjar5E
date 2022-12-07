# Einherjar D&D 5E modern setting adaptation
### A new approach of a modern norse setting for the 5E of Dungeons & Dragons.
#### About:
The main idea behind this sheet is easy access to common character information and auto calculation & population of fields. To see a demo, [click here](https://lporto321.github.io/Einherjar5E/) 

Currently, this is meant to be an offline character sheet for the game of Dungeons and Dragons. It has been rewritten to have a modern responsive layout in w3's lightweight css.

The only part that relies on connecting online is the use of FontAwesome, which is only used in the drop down menu. It utilizes jQuery to load a character from a JSON file and automatically fill out most of the sheet based on your attributes. 

A default Character Sheet has been made to show how this form is meant to be used.  This includes a 'saveSheet.json', 'character.jpeg', and 'symbol.jpeg'. 

#### Credits:
Credit goes to Chee32 for the JQuery which remains largely unchanged. Modern adaptation and full new approach for the norse setting was entirely done by myself.

## Things to know when using this sheet.
### How to:
#### Make your own character sheet: 
1. Download or clone the repository.
2. Fill out all the fields staring with Proficeincy Bonus and Attribute Scores.
3. Save your sheet (in the menu).

#### Save the sheet:
1. Click the 'hamburger' bars to open the menu.
2. In the 'Options' drop-down menu, click 'Save'.
3. A JSON sheet will be download.
4. Copy the new sheet into the 'sheet' folder of the project.
5. You can now refresh the page or click the 'Load' button in the 'Options' drop-down menu.

#### Change Character & Alliance images:
1. Upload your images into the 'imgs' folder
2. For the Character Appearance name the file 'character.jpeg'.
3. For the Alliance Symbol, name the file 'symbol.jpeg'.
4. Currently, if you want to change the name or file type of these images you will have to go into the 'app.css' and change the values.

#### To 'Lock' the sheet:
Locking stops the scripts from running on the sheet if you want to calculate all of your information yourself.
To turn on the lock:
1. Click the 'hamburger' bars to open the menu.
2. In the 'Options' drop-down menu, click 'Lock'.
    - Currently this has to be set every time you load up the sheet.

### Fields that don't populate.
Some fields do not auto-populate based off of the attributes. 
#### Some of the less obvious ones are:
- AC: The reason for this is that your armor and class features mainly determine your AC. I felt it was better to just leave it to you to set it.
- Initiative Bonus: Again, a lot of things can change this other than attributes.
- Proficiency Bonus: This mainly changes with level so I felt it was easy enough to set.
- Current Hit Dice: Again, mainly based on level and not attributes.
- Max Health: This is mainly based off of class and level. It can also be rolled if you chose to so I didn't want this to change if someone added more hit dice.
---

## Issue Reporting & Pull Requests.
### Issues:
If you find any issues, feel free to report them and I will try to address them. Please include as much detail as possible on how to re-create the problem, thanks!

### Pull Requests & Forks:
Feel free to make contributions or fork this project. Please just credit the original author and myself. Thanks!
