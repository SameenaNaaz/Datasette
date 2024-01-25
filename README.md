<img width="182" alt="image" src="https://github.com/SameenaNaaz/Datasette/assets/156209298/449de62c-a404-4f8e-a974-0eace97da885">

 
**Datasette Lite**

We will be using csv files from https://github.com/SameenaNaaz/Datasette

Open Datasette Lite in your browser by clicking on the link below:

https://lite.datasette.io/

<img width="331" alt="image" src="https://github.com/SameenaNaaz/Datasette/assets/156209298/69643dfb-3edd-4a11-977f-8c181b7cd65a">

 
Figure 1

Click on Load CSV and copy and paste the URL of the executives.csv file from https://github.com/SameenaNaaz/Datasette

Click on the executives link to open the executives file in Datasette.

<img width="352" alt="image" src="https://github.com/SameenaNaaz/Datasette/assets/156209298/b08c4486-f62e-40c5-af68-7be1a4e659f8">

 
Figure 2

**Using facets**

Facets are one of the most powerful Datasette features. They can help you take a table with thousands of rows and start quickly identifying interesting trends and patterns within that data.
Here we show some examples using the executives.csv file.

Facets can be applied by selecting an option from the "suggested facets" list, 

<img width="357" alt="image" src="https://github.com/SameenaNaaz/Datasette/assets/156209298/03b86b41-3774-4225-97dc-5744ff269fe6">

 
Figure 3

Once selected, the facet interface is shown above the table as shown below: 

<img width="317" alt="image" src="https://github.com/SameenaNaaz/Datasette/assets/156209298/a05ba1db-8806-4dc1-8cf9-77070fe64a75">


 
Figure 4

Each facet shows a list of the most common values for that column, with a total count number for each of those values.

These numbers will update as you further filter the data: if you select "Democratic" you will see just the rows matching that party, and the "type" facet will update to show you that there have been 16 vice presidential and 9 presidential terms for that party and all 25 were males.

 <img width="301" alt="image" src="https://github.com/SameenaNaaz/Datasette/assets/156209298/18a1a65f-1c69-47f1-baf7-45466cbe9e87">


Figure 5

**Exercises**

1.	Apply the type, state and party facets to the legislator_terms table. 
2.	Use them to filter just to Republican Senators from North Carolina (NC)
3.	Figure out which state has had the highest number of senatorial terms held by a member of the Republican party. 

**Using filters**

When you select a facet, you're applying a filter to the data. These are reflected in the boxes at the top of the page:

<img width="320" alt="image" src="https://github.com/SameenaNaaz/Datasette/assets/156209298/8929c706-b26c-467d-acb1-53ed3abc5b09">

 
Figure 6

You don't have to use faceting for these - you can edit them directly.

To see Republican Vice Presidents just for the 1800s, we can add a filter for rows where the 'start' column begins with '18'. Here's the result of that query.

<img width="301" alt="image" src="https://github.com/SameenaNaaz/Datasette/assets/156209298/2d1ad5c3-2577-41d2-8162-38eac4bfa558">

 

Figure 7

**Exercises**

Using the legislator_terms table, find:
1.	Every senatorial term served in Delaware (DE)
2.	... that started in a year starting with 18.
3.	... and then facet by party to see which parties had the most senatorial terms.

**Exporting data**

If you can see it in Datasette, you can export the raw data. This is a fundamental principle of the project.
Look for the CSV and .json links on any page to export the data in those formats.

 <img width="320" alt="image" src="https://github.com/SameenaNaaz/Datasette/assets/156209298/18de91f8-1de3-43d7-b996-f1fc04a3a87c">


Figure 8

