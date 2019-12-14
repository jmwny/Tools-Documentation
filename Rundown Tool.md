# RundownTool
Tool to generate FDNY / NYPEMS ambulance rundown sheets

## Usage
1. Download the WhenToWork export file for the proper date:
    * From the WhenToWork website, select 'Reports'
    * Under 'Begin Date', select today's date
    * Under 'End Date', select tomorrow's date
    * Select 'Assigned Shift Details - General (most popular)'
    * Ensure that 'Employee Last Name' is selected on the pop-up window:

![test](Images\rdt_1.png)

2. Run the tool and select the "Open Export" button.  A file open dialog will appear which will allow you to select the recent exported <i>EXPORT.CSV</i>

3. Once the file is processed, you can either go ahead and process the rundown sheets or update vehicle and radio assignments.  To do so, double click the appropriate block and enter the new assignment.  Any changes made will propagate to all of the other tours for that vehicle.

![test](Images\rdt_2.png)

4. Any open tours will be highlighted in red.  This is purely a cosmetic notification.
