# pdfSort
Console tool to sort (or optionally verify only) PDF's based on type.  Currently, supports the following types:

        * PCS
        * MAP2015
        * Charity
        * Allscripts
        * Transfer Center

NOTE: These must be formally generated forms.  Scanned documents are not able to be parsed.

## Usage (Verify)
1. Navigate to the target directory and type (or copy/paste) the following (note the --verify argument):

       "G:\EMS-EAST\COMMUNICATIONS\_EMS Tools (Build Bins)\bin\pdfSort\pdfSort.exe" --verify

## Usage (Move/Sort)
1. Navigate to the target directory and type (or copy/paste) the following:

       "G:\EMS-EAST\COMMUNICATIONS\_EMS Tools (Build Bins)\bin\pdfSort\pdfSort.exe"

## Log File
A CSV log file will be generated in both instances which may be opened and viewed in Excel.  For example:

![img](Images/pds_1.png)
