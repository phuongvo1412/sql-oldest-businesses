# Uncovering the World’s Oldest Businesses

This project explores the characteristics that help businesses endure over centuries using a multi-table SQL analysis. The dataset, provided by BusinessFinancing.co.uk and cleaned for educational use, includes the oldest businesses in nearly every country along with country and category information.

## Objectives

Using SQL, the project answers three main questions:

1. **What is the oldest business on each continent?**
2. **How many countries per continent lack data on the oldest businesses, and does including new business data change this?**
3. **Which business categories are best suited to last over centuries, and where?**

## Data Overview

The analysis is based on multiple tables:

- `businesses`: Contains business names, founding years, category codes, and country codes.
- `new_businesses`: Additional business records not found in the original dataset.
- `countries`: Maps country codes to countries and continents.
- `categories`: Maps category codes to descriptive business categories.

## Skills Practiced

- Complex SQL joins (INNER JOIN, LEFT JOIN, USING)
- UNION ALL
- Aggregation with `GROUP BY`
- Filtering with `WHERE IS NULL`
- Subqueries and derived tables

## Tools

- SQL (via DataCamp’s SQL workspace)

## Author

Project by Phuong Vo, as part of SQL learning on DataCamp.