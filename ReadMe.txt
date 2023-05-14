Update: 3/21/2022
DURING EXPERIMENTS: ALWAYS NAME COMPLETE NAME OF THE FILTERS(eg; AEAZ-0061-5.Sample.Raw)

1. Make 3 Folders; 1. ALL PM2.5(Containing 1 XLS File) 2. ALL Reflectance(1 XLS File/Filter) 3. ALL Transimittance(1XLS File/Filter)
2. Copy all the filter data files into these folders.
3. All Blank Filter Files should be named "A.Blank.Sample.Raw" followed by the number doublespace and (#) (eg; A.Blank.Sample.Raw  (1))
### PLEASE NOTE THE SPACE AFTER THE "A.Blank.Sample.Raw" Name
4. All Filter T & R Data Files should be named "XXXX-YYYY-#.Sample.Raw" format. (eg; AEAZ-0061-5.Sample.Raw)
5. All files should be present in the same ORDER across all folders and PM2.5 filenames(eg; Alphabetically)
6. For Every Filter Ensure that there is a Row in "ALL PM2.5" and a file in each "ALL Reflectance" and "ALL Transmitance" folder.
7. Put the Code File in ALL PM2.5// Set the Code Paths & do some required changes// Run the Code
8. A new file "Analysis" will be generated containing all the parameters for every filter name.
9. Copy the "Analysis" file data and Put it into the "Dashboard" XLS File.
10. Extend the range of the plots's data selection to all the rows present.
10. Filter the rows by locations to see the plots for individual cities.
11: If BLANK plots are shown, simply scroll up and down. It should pop up.


Data Manupulation Instructions:
For Blank Filters:
If Mass == 0: Change it to 1
If Volume == 0: Change it to 1

For NO FILTERs: NF
Change the Mass and Volumes to
Mass = 1
Volume = 1

For Normal Filters:
If Volume = 0 OR Mass = 0
Delete the Filter Files from Both Reflectance and Transmittance

**Take care of the order of files present in the all 3 R, T & PM2.5 Folders.

***Change code lines where applicable for Filters of different locations(eg. CASH, BUDDU etc) and get results

@Joshin Kumar
PHD, WUSTL
