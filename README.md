# FDA Data Mining Application

## What it does

The FDA Data Mining Application is a desktop application developed for Celestica Inc. that takes a company name (firm name on the openFDA database), retrieves information regarding the products made by the company and the sites at which they are made. 
  
  *Site information includes name, address, registration and FEI numbers, U.S. agent or official correspondent, and total numbers of the different classifications of products made there. 
  *Product information includes description, activity type, code, class, and regulation number.

This information is used to generate a report in excel format. Specific instructions given to Celestica employees using the program are detailed in the "FDA Data Mining Tool User Manual".

**NOTE:** Some data such as some site official correspondents could not be retrieved from the openFDA database that can be found on the [FDA's Establishment Registration & Device Listing Search](https://www.accessdata.fda.gov/scripts/cdrh/cfdocs/cfrl/rl.cfm).

## Sample Output

The screenshots are taken from the Excel file found in the "sample output" folder. 

![Sample1](https://github.com/JMichaelHerder/FDA-Data-Mining-Application/blob/master/sample%20output/SampleOutput1.PNG "Sample Output 1")

![Sample2](https://github.com/JMichaelHerder/FDA-Data-Mining-Application/blob/master/sample%20output/SampleOutput2.PNG "Sample Output 2")

## Acknowledgments

Thanks to Frank Haigh, Tristan Gay, Jay Silver, and Sayan Bhattacharjee for their work on this project.

All libraries use are open source, they include: openpyxl, requests, urllib, json, tkinter (UI library), datetime.


