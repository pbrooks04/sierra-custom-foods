# sierra-custom-foods

You can download the application directly by clicking on 'SierraRecordTrackerV# - ##.exe' and then 'View Raw'

## Version 1.05
#### What's new
1. Output data is sent to Excel sheets instead of text files
2. Custom save paths (See below)
3. New Scrollable Interface
4. Confirmation before Publishing and Clearing data
5. File names contain date and exact time

##### Custom Save Paths
If you want the SRT to save data to another location, create a file "savepath.txt" in the same directory as the app.
Add only a single line to the file with the desired file path, only the first line will be read.
An example direct file path, C:\Path\That\App\Will\Save\To


## Version 1.04
#### What's new

1. Log tracking
2. Organized directory paths

## Version 1.03
#### What's new 
1. Clear button
2. App does not close on Publish
3. Back colour is a darker blue
4. Help form colour is a lighter blue


## Version 1.02
#### What's new
1. Product Code field
2. Total cut amount displayed in output file


## Version 1.01
#### What's New
1. Publish also prints the start time
2. Lot # field 
3. Load employees from 'SierraEmployeeList.txt' by entering employee number (see below for syntax rules)
4. Size adjustment ( given screen pixel size as 2160 x 1440 (should still be a little less than) )
5. View employee numbers (if you forgot ( one minor 'bug', see below ) )

#####SierraEmployeeList.txt
Create a text file (.txt) with the same name as above in the same directory as 'SierraRecordTrackerV1-01.exe'
Enter employee number then name separated by ':' (ex '1234:Employee Name')
Put each individual name and number on a new line

#####"bug"
If you add employees to 'SierraEmployeeList.txt' while the app has started, they will be listed in the Loaded Employees form but
they won't be loaded into the program
