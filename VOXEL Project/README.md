# Project Overview

![46914416941964196](https://github.com/Amir-Hassanein/PowerBI/assets/33359756/3c32e3ad-af1b-4de4-9609-81786189ef3b)

Quellaveco is a copper mine located in the Moquegua region of Peru. Anglo American has invested approximately $5.5 billion to make Quellaveco their first 100% digital mine, and began construction in 2018. Quellaveco is estimated to contain 8.9 million tons of copper.

In a new milestone for the company, Anglo American has deployed a fleet of autonomous trucks to haul materials out of the Quellaveco mine. This fleet is called the Autonomous Haulage System (AHS), and was developed by the equipment manufacturer Caterpillar. It is the first autonomous fleet of its kind to be deployed in Peru. AHS vehicles are autonomous haul trucks, a specialized type of dump truck designed to haul large payloads of raw ore from the mine.

The Operations Manager (OM) of the mine is interested in analyzing the new system, including the sizes of the payloads carried and the average vehicle speeds across the different routes within the mine. Using the price of copper and the payload size, the total value of the product mined can be ascertained in USD.

The OM has also asked that you ensure daily spot price of copper differences are addressed as part of your model, so that he can accurately see the values in USD.

To review and analyze the accuracy of your data model, you’ll create simple card, table and matrix visualizations summarizing total payload, average speed and total copper value for each month by route grade, route, truck, and month. While your output should be easy to read, it’s not necessary to add any bells and whistles to your report view.

Note: This data is synthetically generated.

When you complete this assignment, tab 1 of your report will look like this:

![9414494191496](https://github.com/Amir-Hassanein/PowerBI/assets/33359756/f8cac2fb-deae-4290-8eea-ceadb896bbc6)
*Tab 1: Quarterly Analysis*

* …and tab 2 will look like this:

![49611461469](https://github.com/Amir-Hassanein/PowerBI/assets/33359756/2dd90a61-b4e9-4d84-a467-b55515cee07e)
*Tab 2: Truck Analysis*

***

## Operations Manager's Requirements

To satisfy the OM's requirements, we will need to calculate the average speed and value of copper extracted.

Commodity prices is a tricky (and common) problem you may run into as you grow as a BI analyst. When you face this situation in future, remember to carefully define the requirements on how the currency exchange needs to be reflected in reporting. As we discussed earlier in the course, an exchange rate may be daily, monthly, or run on a rolling average. And it can require more complex data modeling to satisfy reporting needs for multiple currencies. How you handle exchange rates through your data model structure will vary based on the desired end result.

Luckily for us, the OM provided really clear guidelines. They are only really interested in seeing the total copper value in USD, and the breakdown per quarter as in the dashboard matrix, though they would like it to reflect daily commodity rate fluctuations.

The OM has asked you to calculate:

1. Average speed in km/hr
2. Total copper value in USD
   
The OM has also reminded us that 1 kg of ore mined does not equate to 1 kg of copper sold on the market, and therefore a ratio needs to be used when trying to derive the mass of recovered copper metal from ore; that value is calculated as 0.06471 kg of copper per 1 kg of ore.

The units of measurement for the different numeric values are:

* Price of copper in USD/kg (United States dollars per kilogram)
* Payload is in tons (1 ton = 1000 kilograms)
* Distances are in km (kilometers)
* Truck Payloads are in t

***

## Stand Out Suggestions

### Suggestion 1: Visualization

* Create a visualization for the time series of price of copper over the year (what can be observed)

### Suggestion 2: New Measure

* Create a new measure to answer a possible business question. For example, what percentage of cycles are empty and have no payloads on them?
