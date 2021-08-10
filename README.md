# CitiBike_Tableu

## Purpose

Analyze CitiBike data for Jersey City Summer of 2019 for trends and visualize them using Tableau Public. View the Tableau Public workbook https://public.tableau.com/views/CitiBike_16281173516890/Ridership?:language=en-US&:display_count=n&:origin=viz_share_link.

## Data Cleanup

Prior to using Tableau, I first cleaned the data via Python and the Pandas library in a Jupyter Notebook. I concatenated monthly data for June, July and August  2019 to  create a summer csv for easier reading. In the new csv I converted  trip duration to minutes and dropped rows where the trip duration fell under 2 minutes and where the starting and ending stations were the same to eliminate any faulty bikes.
