# The query results were exported into four separate CSV files, all of which are saved in the report/ folder of the project repository. 
The Python script used to run the queries and generate these CSV files is included as query_analysis_load_to_csv.py in the same directory. 
All visualizations were created using Looker Studio by connecting directly to a PostgreSQL database hosted in the GitHub Codespace environment.
For the Gold_Ranked_Players data source, two custom fields were created within Looker Studio: one to classify players by type (Player Type) 
and another to calculate their win/loss ratio. For the Active_Players data source, average monthly players, peak players, and average-to-peak 
ratios were computed as metrics. 


Unlisted links to Looker reports: 
Gold Ranked Players:
https://lookerstudio.google.com/reporting/e922eb17-f17e-4b48-a4f4-9665a956c131

Active Players:
https://lookerstudio.google.com/reporting/fffcaf7e-17ae-4196-839c-32ba2203014d

