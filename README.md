# Pewlett-Hackard-Analysis

## Overview of the analysis: Explain the purpose of this analysis.
A client at Pewlett-Hackard would like us to apply data modeling, engineering, and analysis to assist him build an employee database with SQL that could potentially be used to query employees who are retiring for the next few years. <br/>
We built a database (See the Data folder) to store, maintain, and access the data that we used to query (See Queries folder), analyze, and create tables. <br/>
The database and analysis will help Pewlett-Hackard to generate a list of all employees eligible for the retirement packages, thus, serving to determine how many positions Pewlett-Hackard will need to fill.

## Results
We used SQL to query the database that we built, and created table to answer Pewlett-Hackard questions: <br/> 
* List of Employee eligible for retirement <br/>
  This table unearths the list of all employees who are potentially eligible for retirement regardless of whether they still with the company or not. Some of the employees were     mentioned several times depending on how many times they moved from one department to another within the company. We counted about distinct 90,000 employees eligible for           retirement.
  
#### List of Employee eligible for retirement table 1: <br/>

<img width="371" alt="List of employees eligible for retirement" src="https://user-images.githubusercontent.com/34750363/153646796-20501d23-dbcb-42f9-87eb-a5e6b922e716.png">

* List of Employees eligible for retirement with their unique titles <br/>
  This table is almost like the table above, except that it does show all the employees potentially eligible for retirement with their unique job titles. Thus, there are no         duplicates.
  
#### List of Employees eligible for retirement with their unique titles table 2: <br/>

<img width="286" alt="Emp_Eligible_Ret_UnTitles" src="https://user-images.githubusercontent.com/34750363/153648436-4570af43-b7ee-4686-afa7-9c8e6f68a678.png">

* Count of employees eligible for retirement by their most recent job title <br/>
  The count of employees potentially eligible for retirement by their most recent job titles revealed that most of them will be among senior staff and senior engineers.
  
#### Count of employees eligible for retirement by their most recent job title table 3: <br/>

<img width="136" alt="Count_Unique_Emp_Titles" src="https://user-images.githubusercontent.com/34750363/153649908-5b94bc3c-819a-4b79-90f7-72fd0a9b85d5.png">

