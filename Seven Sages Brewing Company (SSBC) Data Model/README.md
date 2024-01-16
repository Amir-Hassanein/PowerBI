## Project Overview

In this project, you'll create a data model and Power BI report for Seven Sages Brewing Company that combines information from all over the company. Your data model will make it possible for the company's CFO to quickly review and analyze what beers sell well and which ones generate the highest profitability.

At the end, you will have applied the key concepts of this course to combine and centralize data that was previously siloed, solving a very common issue facing many companies. More importantly, you'll have a solid foundation to build on when it comes to more complex reporting visualization demands, advanced DAX requirements, or larger data models. No matter how large the data models get as your career progresses, the core principles remain the same.

When you complete this assignment, tab 1 of your report will look like this:

![4691414196](https://github.com/Amir-Hassanein/PowerBI/assets/33359756/bcd5648c-184d-4f3e-94ce-bfbb2d3dca90)

…and tab 2 will look like this:

![496419641994](https://github.com/Amir-Hassanein/PowerBI/assets/33359756/6a4fe676-4846-4bf8-bfb0-9b1f0d94f7c9)

***

## CFO Requirements

To satisfy the CFO's requirements, we will need to calculate Sales, Cost of Sales and Gross Profit Margin in two different currencies.

Currency exchange is a tricky (and common) problem you may run into as you grow as a BI analyst. When you face this situation in future, remember to carefully define the requirements on how the currency exchange needs to be reflected in reporting. As we discussed earlier in the course, an exchange rate may be daily, monthly, or run on a rolling average. And it can require more complex data modeling to satisfy reporting needs for multiple currencies. How you handle exchange rates through your data model structure will vary based on the desired end result.

Luckily for us, the CFO provided really clear guidelines. She's only really interested in seeing the Sales total in CAD (Canadian dollars), though she would like it to reflect daily currency exchange rate fluctuations.

When you initially reviewed your starter materials, you may have noticed that the sales record only tracked units sold without applying sales totals. Since the per-unit cost price and sales price values are all in USD, we already have a "standardized" currency to calculate off of and can just apply CAD exchange rates from the currency tables off of that base 1 USD value.

***

## Stand Out Suggestions


### Suggestion 1: Product Type

So far, we've helped the CFO better understand how sales and profitability translate by customer and we've learned more about profitability relative to sales by each beer.

Next, we want to dig in a little deeper and figure out what product type is most profitable per serving for serving for SSBC.


### Suggestion 2: Seasonality

Does SSBC’s beer sell differently by month? In this Stand Out, we'll analyze the share of each product name (beer) purchased over the course of a calendar year to determine whether sales reflect any seasonal trends by create a new measure called “servings sold” to help create a standard measure that accurately reflects the amount of beer sold by product type according to the number of servings provided. Use this measure to create a matrix with product name (e.g., “Bamboo Grove Grolsch”) as rows and calendar months (i.e., “January”, rather than fiscal period 5) as columns.

Summarize any seasonality you notice in sales below the matrix. Label the tab “SO2 - Seasonality”.
