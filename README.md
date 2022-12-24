# Crowdfunding_ETL


## Overview

This project focused on applying the ETL process to crowdfunding data for Independent Funding. The data was moved from a large Excel file onto a PostgreSQL database so that we could conduct analysis and generate reports for the company, its stakeholders, and backers. The first part of the project dealt with extracting and transforming data from one Excel file into four separate CSV files. Then, using an ERD, a PostgreSQL database was created to store the separate tables of data and perform analysis. 

The second part of the project dealt with applying the same ETL process to live crowdfunding project data. A new dataset containing information on backers and their pledges to live projects was obtained. The data was extracted, transformed and loaded into the PostgreSQL database. Analysis was performed to assess the number of backers per crowdfunding id for live campaigns. Next, a table and csv file were generated so that the contact for each live campaign could be reached in order to inform them of how much of the goal remains. Finally, another table and csv file were generated so the backers could be notified of how much of the goal remains for each live campaign they've pledged.
