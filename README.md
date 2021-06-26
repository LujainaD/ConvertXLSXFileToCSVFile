
ConverterXLSXFileToCSVFile
==============================
It is a simple java application which created by using netbeans software and java language . 
The aim of this application is to convert Excel(.xlsx) file to (.csv) file.


Technologies 
------------

- Apache NetBeans IDE 11.3
- Java 14
- jar files should be added to lib file

	commons-collections4-4.1.jar\
	poi-3.17.jar \
	poi-ooxml-3.17.jar \
	poi-ooxml-schemas-3.17.jar \
	xmlbeans-2.6.0.jar\
	opencsv-2.2.jar 


Instructions
------------

- You need to have an Excel File , then change the path of the file in the following code 
	, then change the name of the Excel file in the code which called "new.xlsx"

        File excelFile = new File("C:\\Users\\lujai\\OneDrive\\Documents\\new.xlsx");
        File excelFile = new File("file_Path\\name_of_Excel_file.xlsx");



