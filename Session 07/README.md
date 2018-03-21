# Business Intelligence and Data Warehouse Course

## Session 7

The topic of this session is **Data Integration**. This repository includes the content discussed in class.

  - ETL processes
  - Videos
  - Data Sets

## How to use this content

  - Download the folder
  - Required Software:
	  - MySQL
	  - Pentaho Data Integration
	  - Java JDK
  - All ETL processes have been created with Pentaho Data Integration.
  - Transformation TR8-P1 and TRA8-P2 require MySQL.
  
## FAQ

### Does PDI support user input?

Yes. It supports arguments, parameters and variables. You can read about it [here](https://help.pentaho.com/Documentation/8.0/Products/Data_Integration/Data_Integration_Perspective/050).

### How we can create an ETL environment independent?

Using varialble in the path such as

``` 
${Internal.Entry.Current.Directory}
``` 
