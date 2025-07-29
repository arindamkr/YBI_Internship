# YBI_Internship
This repo contain the files of ybi internship
Weekly Meal Schedule for HealthyBites Kitchen
Overview
To develop a Python CLI tool that enables HealthyBites Kitchen to schedule weekly meals, manage ingredient usage, and export shopping-ready ingredient summaries.

Core Features

Add meals: Enter meal name, scheduled date (validated to be today or future), and list of ingredients.

Unique IDs: Assign unique identifiers to each meal using a set to prevent duplicates.

View meals: List upcoming meals in chronological order.

Ingredient tracking: Aggregate ingredient usage across all scheduled meals using Pandas and export totals to a CSV file.

Export function: Generate ingredients.csv summarizing ingredient counts for procurement.

Technical Stack

Language & Libraries: Python, standard datetime, and pandas (for DataFrame aggregation) 
medium.com
projectpro.io
+4
linkedin.com
+4
geeksforgeeks.org
+4
youtube.com
en.wikipedia.org
.

Data Structures:

meals: list of dicts (id, name, date, ingredients)

meal_ids: set for ID tracking

Key Functions: add_meal, view_meals, generate_ingredients_df, export_ingredients_csv

Benefits

Efficiency: Streamlines weekly meal planning and procurement.

Organization: Prevents duplicate entries and ensures date consistency.

Scalability: Foundation supports future features such as persistent storage, editable entries, and a web-based interface.
