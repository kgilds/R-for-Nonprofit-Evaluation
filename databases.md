# Data Management

Quality in, quality out, a critical factor for an evaluation project is the quality of the data you are going to be analyzing. Hopefully you have control of the data that you are analyzing.  Ideally, you start with your interesting question that you want answered and you can determine the best method to collect the data you want answered. 

Effectively working with data encompasses the ability to split, apply, and combine. 

* split; you want to split your data into groups
* apply; find something out about your data, summary statistic. 
* Combine a different data set to complete the analysis. 



# Tidy Data

Tidy data i

# Connecting Data

An important skill is being able to connect separate data sets to analyze the results In spreadsheets, a way to do this is a lookup function either Vertical or Horizontal. The concept in a spreadsheet to do this is called lookup value.  A suitable lookup value to connect data sets  is typically a numeric value that is shared between data-sets the uniquely identifies a row \(person, thing, record\).



# Databases

The world runs on databases. Have you bought anything from Amazon? If so, most likely you are in a customer database table and the record of your order in another table.  It is a good idea to have a basic idea of how they work.  You could think of a  database as  an Excel Workbook with a lot of sheets/or tabs in it. However, most of  the sheets would be  are somehow related to one another by relationship  key. Two types of keys are primary keys and foreign keys.   The power of databases is that a database will tie related data together through the use of keys.

Databases are split into multiple tables or you could think of them as sheets. In a well constructed database each table would have key to uniquely identify a record.  Typically this is a customer identification number or Refer Number,  CIRTS ID. 

In CIRTS, think of the demographic screen as a seperate table of information. When you create a new record in CIRTS, the computer generates a CIRTS ID and that uniquely identifies the individual. This table has one CIRTS ID to record information about an individual. In theory we should have one demographic record for an individual.  \(Don't think about duplicate entries for the time being\)

Think of the all the screens in CIRTS:  Assessments, Enrollment, Medwaiver Timeline.

You have multiple assessments, you have multiple records in the Enrollment Screen, multiple enteries in the Medwaiver Timeline and all of this is tied together by the CIRTS ID. 

Between the demographic screen and those other screens is a one to many relationship. 

One CIRTS Id tied to many assessments, enrollment record, and MedWaiver Timeline record. 

What are keys? D

## Key-terms

Primary key:   A uniquie idendtifier. 

One to many: 
