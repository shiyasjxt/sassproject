# sassproject

# How to generate css file from sass

1. Write your sass code in a style.scss file
2. Access the folder path from the terminal
3. Run below command, the css file for the scss file is generated - 
JXTs-Mac-mini-2:sassproject Shiyas$ sass --update styles.scss

4. invoke this css file from you html file.




# Command to generate CSS file into a new file name
sass --update styles.scss:mysheet.css

# Command to generate CSS file for all scss in a folder
sass --update sourcefolder:targetfolder

# Command to watch a folder for any changes in scss file and update css
sass --watch sourcefolder:targetfolder
