


The Following Project will be completed in accordance to Agile Manifesto and Principles, albeit personal. 

## Adapted Agile Workflow: 

1. Define Goals 
-->
2. Create Project Outline 
--> 
3. Create a List of tasks
              - Procedures listed in order of completion and/or importance
-->
4. Set up sprint schedule:
              - Allocate appropriate time for each subtask
-->
5. Kanban Task-Tracking
              - Kanban and Scrum not Necessary 
              - Progress report will be made on separate .md file
-->
6. Reflection after each sprint
              - Recorded on separate .md file

              


## Project Goals 

This project aims to compile past data and pinpoints potential trends, issues, discrepancies of Young Immigrant Workforce. 

## Project Outline 

1. Collect Data from Various sources (Described Below) 
        - Use SQL to extract data from various sources, such as databases, manually-retrieved CSV, and APIs
2. Transform Data: 
        - Use SQL to clean, normalize, and transform data to be loaded into data warehouse. 
3. Load Data:
        - Use SQL to load data into data warehouse
4. Design the data warehouse:
        - Use ERD to plan out data warehouse schema, relationships and indexes
5. Implement Data warehouse: 
        - Amazon Redshift or Google BigQuery
6. Create intelligence platform reports with Tableau
7. Verify Data integrity (See integrity notes below) 



## Data Sources

1. Official Government Agencies:   US. Bureau of Labor Statistics,   U.S. Census Bureau 
2. Non-profit think tanks: Migration Policy Institute, Center for Migration Studies, and American Immigration Council 

On International Students Studying in the U.S

3.  Institute of International Education -> Open Doors report:    https://opendoorsdata.org/data/international-students/ 
4. U.S. Department of Homeland Security -> Student and Exchange Visitor Program: 

On Immigrant Entrepreneurship 

5. National Foundation for American Policy 
6. Ewing Marion Kauffman Foundation
7. New American Economy


## Data Integrity Validation Principles 

1. Checksums For Quantitative Data 
    -A checksum is a value that is calculated from the data, and can be used to verify that the data has not been modified. When data is transmitted or           stored, the checksum is also sent or stored, and when the data is received or retrieved, the checksum is recalculated and compared to the                 original checksum to verify integrity.
    
2. Hash

    -A function that returns a fixed-size string of characters for comparison 





