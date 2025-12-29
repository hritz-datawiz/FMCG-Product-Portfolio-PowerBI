As part of this project, the original Global Superstore dataset is provided in the data/raw folder.

As a first step, the dataset is loaded into Power Query for further cleaning and transformation.

This document captures the thought process and rationale behind each decision taken during data cleaning, column removal, transformation, and data wrangling, ensuring transparency and reproducibility of the analysis.

DATA CLEANING:

Removing the following columns as prove irrelevance to the project goal and analysis:
1. Customer : Relevant in customer analytics projects
2. Customer Name: Relevant in customer analytics projects
3. 记录数 (Irrelevant column. No Use)
4. Row Id: Irrelevant

Although power Query does most of the work

The following dtype are changed: 
1. Ship Date: DateTime to Date--> Time relevance not valid
2. Order Date: DateTime to Date--> Time relevance not valid
3. Discount is an indicator and not in peprcentage and hence is an int 64 type


