# Pizza-sales:
An interactive dashboard I created using raw unstructured data from a US Pizza sales data set.

What I did:

I have made a data model from this sales data. Firstly I renamed some columns as the names across the sheets didn’t align, therefore to avoid confusion I matched the column names.

I then made tables and reformatted the data to align with the column width and also named the tables so that later on the data modelling sections wouldn’t be confused.

Once all the sheets were on the data model, I went back to excel to understand the context of what I am working with in detail.
I understood that the sales are the fact table and the rest of the tables are dimension tables. I linked the branch data from the branch table to the sales table.

The reason for this is that the sales from the sales table have sales from places around the whole country and the data isn’t organised.
By linking the 2 data I would be organising the sales via the places they originated from rather than it being random jargon.
Using that logic as the basis of my understanding, I was able to link the other tables. Created a relationship between the date from the daily target table to the sales target table.

Linking the pizza type from the sales target table to the pizza type of the sales table. 

The sales table is the FACT table whilst the other 3 tables are the dimension tables.

Now that the data modelling has been completed, I now focus on the tables themselves. For the sales table, I create a total cost column by doing quantity*price.

This will be useful later when am making the graphs. Now I need to make pivot tables from the tables themselves, create graphs, slicers, and a timeline,e and then finally formatted the dashboard.

Now that I know what I will be doing, I need to decide what graphs I will make, what sort of information would be in the slicers and how will I organise my dashboard to make it look simple and organised.

I want to make 3 graphs, one regarding the sales target for each of the pizza types and comparing it to the actual sales made.
Another graph comparing the number of sales made before 9 am and 9 pm.

And another graph showing the top 5 pizzas which are ordered in bulk (in quantities)

I will then further narrow down the search and make data more accessible by including slicers that have information regarding the states within it.
As well as a timeline that shows the days when the sale was made.

After that I then organised and cleaned the graphs to make them simpler, I optimised what graph suits what chart the best, made a dashboard page, and just did the finishing touches on it.

I then copied and pasted the graphs from their pages (where the pivot table originated from) and put them on the dashboard page.
Then finally made the dashboard page easy to the eye and as simple as possible, the reason being that the goal of a data analyst is to build dashboards for a non-professional to understand.

