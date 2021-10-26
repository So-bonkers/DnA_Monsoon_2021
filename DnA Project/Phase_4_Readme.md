## Data and Applications
### Monsoon 2021
--- 
### Project Phase - 4 (CLI Coding)

### Part A
  ```Contains the SQL commands to create the table in 3NF and the latter part of the code contains all the foreign keys according to the corresponding relationships```

### Part B
```The functions that help to carry out the functionalities of the queries have been implemented. Here we broadly define the funcitons in three subcategories:```

a. Insert Functions

b. Retrieval Functions

c. Update Functions

d. Other Miscellanous Helper Functions

#### Insert Functions
1.  insert_scp - This function is required to add a row of data to the entity SCP
2.  insert_site - This function is required to add a row of data to the entity SITE
3.  insert_airbase - This function is required to add a row of data to the entity AIRBASE
4.  insert_goi - This function is required to add a row of data to the entity GOI
5.  insert_Active_Location - This function is required to add a row of data to the entity Active Locations
6.  insert_mtf - This functions is required to add a row of data to the entity MTF
7.  insert_mtf_codename - This functions is required to add a row of data to the entity MTF Codename
8.  insert_mtf_comoff - This functions is required to add a row of data to the entity Commanding Officer
9.  insert_spec_proc - This functions is required to add a row of data to the entity Special Procedures
10. insert_personnel - This functions is required to add a row of data to the entity Personnel
11. insert_address - This functions is required to add a row of data to the entity ADDRESS
12. insert_conv_inv - This functions is required to add a row of data to the entity Containment Involvement
13. insert_conv_inv2 - This functions is required to add a row of data to the entity Containment Involvement 2
14. insert_relationship - This functions is required to insert a relationship value

### Retrieval Functions
1. scp_by_item - Selecting SCP by its item number
2. num_of_scp -  Number of SCP counts by counting the number of columns of the primary key
3. years_in_containment - Gives the number of years in containment
4. aggregate_avg - Average number of SCPs per SITE

### Update Functions
1. update_mtf - Update the MTF data (only the coomanding officer)
2. update_scp - Updates only the Object Class and Special Containment Procedures
3. update_site - Updates the site number, site capacity and staff size

### Miscellanous Functions 
1. dispatch - Helper function to map to other functions
2. make_queries - ALL :)
