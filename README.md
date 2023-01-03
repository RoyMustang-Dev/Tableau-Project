# Tableau-Project

## Comparative Study of Countries

### `Problem Statement:`

***Create a dashboard to do a comparative study on various parameters of different countries using the sample insurance dataset <br/> and world development indicators dataset.***

### `Datasets :`

1. Primary Dataset – Insurance Sample Dataset
2. Secondary Dataset – Global Financial Development Database

**`Hint:`** (Use Data Blending with Relationships between Country Code, Country, and Year)

### `Dashboard Description :`

1. A geographic map showing countries field. Color the map based on Income column from the secondary dataset.
    * To include a filter of income group to the dashboard.
2. Include a webpage to show data from world bank webpage driven by an URL action from geography graph.
    * The country names in the map will act as the trigger [example](https://data.worldbank.org/country/<country>?view=chart)

3. Create a KPI Table to show the comparison between the selected period and the prior period to the selected one.
    * Create two parameters for Year Selection and Category Selection.
    * Category Parameter to have Life Insurance Share, Market Share, Penetration, Ratio of Reinsurance Accepted & Retention Ratio
    * Create a calculated field to calculate the Growth %.
    * Create a table to show these values as shown.
    * Title to be updated based on the category selection

4. Create Growth Indicator Shapes based on the Growth %.
    * Growth indicator to display Negative, No Change and Positive as values and corresponding shapes against it.

5. Create a trend line to show the selected category values.
    * The line to show with a arrow/triangle at the last mark

6. Dashboard filter for income group to be applied for all charts with the filter action enabled in the map as well
7. Formatting to be done appropriately


### `Solution:`

The solutions are in the below files
* Tableau Dashboard - Comparative Study of Countries.twbx
* Ms Word Document - Comparative Study of Countries.docx
