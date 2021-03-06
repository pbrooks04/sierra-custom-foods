# sierra-custom-foods

You can download the application directly by clicking on 'SierraRecordTrackerV# - ##.exe' and then 'View Raw'

## Version 1.14
#### What's new
1. Only cut files are password protected now

## Version 1.13
#### What's new
1. More fields to support up to 30 workers
2. Added apostrophe " ' " character in Excel Docs to allow for leading zeros in Employee Numbers

## Version 1.12
#### What's new
1. Textbox to manually alter intervals.
2. Password protected files.

## Version 1.11
#### What's new
1. Load up to 8 support worker types by writing each type into a text file named 'SupportWorkerList.txt' saved
   in the \Archive\AppData directory. Separate each entry by a new line.
2. Scroll down to enter values for each worker type either manually or with buttons.
3. Support worker values are written to cut logs.


## Version 1.10
#### What's new
1. Manual input fields for start and end times. 
2. Input time formats are verified and published


## Version 1.09
#### What's new
1. Publish bug should be fixed now


## Version 1.08
#### What's new
1. Running total displayed for all cuts


## Version 1.07
#### What's new
 1. Confirm on Exit and prompt to publish


## Version 1.06
#### What's new
 1. Displays at most 13 employees
 2. No longer need to scroll to view employees


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
