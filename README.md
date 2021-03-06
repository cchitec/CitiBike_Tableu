# CitiBike_Tableu

## Purpose

Analyze CitiBike data for Jersey City Summer of 2019 for trends and visualize them using Tableau Public. View the Tableau Public workbook https://public.tableau.com/views/CitiBike_16281173516890/Ridership?:language=en-US&:display_count=n&:origin=viz_share_link.

## Data Cleanup

Prior to using Tableau, I first cleaned the data via Python and the Pandas library in a Jupyter Notebook. I concatenated monthly data for June, July and August  2019 to  create a summer csv for easier reading. In the new csv I converted  trip duration to minutes and dropped rows where the trip duration fell under 2 minutes and where the starting and ending stations were the same to eliminate any faulty bikes. The gender column previously  numerically coded was then converted into strings. 

## Analysis

I focused on Generational and Gender patterns with regards to usage. 
Asking the following questions, among others:
  - Which group had the most bike rental?
  - Which spots where a trend for each generation or even gender? 
  - Which generation was more likely to have a subscription? 
  - Which was the most popular day to rent a bike across the generations?

It became evident that bike usage was most common amongs Millenial males, closely followed by Gen X males, as visible below:

<img width="1002" alt="Screen Shot 2021-08-10 at 2 04 45 AM" src="https://user-images.githubusercontent.com/79786994/128831216-62565f72-5a9b-4c5c-aced-57d5cd5b7a9c.png">

The most popular day to rent a bike varied amongst the generations as shown below:

<img width="1004" alt="Screen Shot 2021-08-10 at 2 07 07 AM" src="https://user-images.githubusercontent.com/79786994/128831616-d263dae1-677e-4f33-92ce-862be6ae1026.png">
