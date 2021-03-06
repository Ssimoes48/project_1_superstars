

Group 2 (super-stars): Members: Sara Simoes, Tyler Brown, Rachel Chan, Kasey (Kassandra) Lacerda

Project Title: Health in Food Deserts Description: Evaluate health status of residents in counties with and without food deserts.
Hypothesis: The presence of a food desert in a county results in decreased health status for residents of that county.

Research Questions:
Do residents of counties with food deserts have reduced health status, as measured by various health factors (e.g. premature death, adult obesity, diabetes)

    Parse data by common characteristic (i.e. county)
    Show food deserts on a heat map (for density)
    Show health status for various health factors on a heat map (for density)
    Overlays:
        premature death and food desert maps
        adult obesity and food desert maps
        premature death and food desert maps
        diabetes and food desert maps
    Comparison of these health parameters in counties with food deserts, versus in counties without.
        Pick representative counties from each group and dive deeper into data
        Pie plots health factor for counties with and without food desert.
        other plots as needed

Bar Graphs:
In order to get valuable data for comparisons I had to take all of the significant population 
based data and normalize it to a percentage. Afterwards, I created a for loop to produce bar graphs based on
each column on a county level. 
I then created another for loop to run comparison bar graphs between food desert population and various health based
parameters accompanied by a quick t-test. Here are the comparisons that probably weren't due to random chance:
    
    LAPOP1_10
    Low access pop 1 mile urban - 10 miles rural and medicare percent
    Low access pop 1 mile urban - 10 miles rural and obese percent
    low access pop 1 mile urban - 10 miles rural and %Fair or Poor health
    
    LAPOP05_10
    low access pop 1/2 mile urban - 10 miles rural and medicare percent
    Low access pop 1/2 mile urban - 10 miles rural and obese percent
    Low access pop 1/2 mile urban - 10 miles rural and %Fair or Poor
    
    LAPOP1_20
    Low access pop 1 mile urban - 20 miles rural and medicare percent
    low access pop 1 mile urban - 20 miles rural and %Fair or Poor health
    
    *See comparison folder and bar_graphs folder

According to the bar graphs, there seems to be a relationship between obesity and the low access populations between
half a mile (urban) from supermarket and 10 miles (rural).
There also seems to be a similar relationship between the fair/poor % and half a mile from supermarkets (urban)
up to 20 miles from supermarkets (rural).
While it isn't due to random chance, I'm not entirely sure what the relationship is. However, there did seem to be a relationship
between the number of flagged flag food deserts (mainly in Big Horn County) and the percent of obese/diabetic citizens. Unfortunately, running a t-test
on that would be difficult due to the difference between the types of data displayed (difference between # of food deserts and percent obese/diabetic.

Resources:

    Health Data: https://www.countyhealthrankings.org/explore-health-rankings/rankings-data-documentation/national-data-documentation-2010-2018
    Food Desert Data: https://www.ers.usda.gov/data-products/food-access-research-atlas/download-the-data/
    County Coordinates: https://public.opendatasoft.com/explore/dataset/us-county-boundaries/map/?location=5,69.03242,-35.00244&basemap=jawg.streets
