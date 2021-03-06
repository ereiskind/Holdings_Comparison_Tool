# Holdings Management/Alma Holdings Comparison Tool
This repository contains a program to compare the holdings in a CSV downloaded from EBSCOadmin's Holdings Management and an Excel .xls file resulting from the extended export of a portfolio list in Alma. The program is effectively instructions for using OpenRefine, so the computer running the program must also have OpenRefine, which can be downloaded at https://openrefine.org/download.html.

## Questions
### Regarding Program Functionality
* Should the holdings dates be compared to Alma defaults?
* In instances where a KBID matches multiple portfolios (a title change seems to create a new Alma title, and each title in a collection is its own portfolio)--how should evaluating these holdings and their date ranges be handled?
* Should data other than holdings dates be compared?

### Regarding Alma and This Program
* If using local/custom dates is selected in Alma but no no dates are actually provided, are the default/global dates copied down to the local/custom dates section, or will Alma not not save the selection? If local dates are being used, will Alma allow for all the local date ranges to be deleted? Overall, can a situation arise where Alma says local/custom dates are being used, but there aren't any local/custom dates in Alma?