#  The Legacy of Redlining Los Angeles County
## Homework Assignment 2 

![Historical Redlining in Los Angeles County (Source: PBS SoCal)](https://salazarcenter.colostate.edu/wp-content/uploads/sites/12/2020/06/01-redlining-maps-los-angeles-1920x768.jpg)


## Background

In the 1930s, the Home Owners Loan Corporation (HOLC) gave Americans  the opportunity to purchase homes amidst the economic collapse of the Great Depression. The HOLC allowed individuals to purchase homes without large down-payments and issued low-interest loans to a million homeowners who had lost their homes. Though these opportunities were not given out equally. The HOLC created a rating system that gave neighborhoods scores from A to D to assess mortage risk. Areas were rated as follows:
    
- A
    - best investments for homowners and banks (green)
- B 
    - neighborhoods that were still desirable (blue)
- C 
    - neighborhoods in decline (yellow)
- D 
    - areas considered as hazardous (red)
 
 This rating system, most commonly known as redlining, allowed racism to proliferate. Most commonly, communities zoned in as yellow and red were home to African-Americans, Mexican-Americans, Asian-Americans, working class people, and immigrant groups. In consequence, private investors largely avoided these neighborhoods.  


## Purpose
This repository explores the legacy of redlining in Los Angeles by examining the distribution of low income status, particulate matter exposure, low life expectancy, and pedestrian & bicycle accidents and fatalities among the HOLC grades. In Part 1, the map shows the geographic locations of HOLC graded areas in Los Angeles county. The plots shows current conditions of low income status, particulate matter exposure, and low life expectancy in each HOLC grade. Part 2 shows the percentage of bike and pedestrian crashes and fatalities within each HOLC grade. 


## Repository Organization

```
EDS223-HW2
├── .gitignore
│   └── data 
|       ├── ejscreen
│       ├── mapping-inequality
│       └── SWITRS_LA
├── HW2.qmd
└── README.md
```
Data was placed in the `.gitignore` folder due to large size.


## Data access
The Los Angeles County census block groups data used for the analysis comes from the United States Environmental Protection Agency's [EJScreen](https://pedp-ejscreen.azurewebsites.net/): Environmental Justice Screening and Mapping Tool. HOLC Redlining [data](https://dsl.richmond.edu/panorama/redlining/#loc=5/39.1/-94.58&text=downloads) comes from the Digital Scholarship Lab at the University of Richmond. Data from Bike and Pedestrian Crash Reports comes from the Statewide Integrated Traffic Records System (SWITRS), hosted on the [Transportation Information Mapping System](https://tims.berkeley.edu) which was developed by UC Berkeley researchers.

More concisely, all data was downloaded from a provided [folder](https://drive.google.com/file/d/14x1CTz3ZUJdm8_8625OGM5W32TkcCife/view?usp=sharing).

## Contributors

Assignment given by Annie Adams for EDS223 Fall 2026.


## References

“Segregation in the City of Angels: A 1939 Map of Housing Inequality in L.A.” PBS SoCal, 15 Nov. 2017, https://www.pbssocal.org/shows/lost-la/segregation-in-the-city-of-angels-a-1939-map-of-housing-inequality-in-l-a.
