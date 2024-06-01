# COVID-19_US_National_Averages
This is part 1 of my Capstone for the University of Colorado Boulder's Data Analysis with Tidyverse Certificate.

The COVID-19 pandemic is a global health crisis caused by the SARS-CoV-2 virus, which had a devastating impact on global health, economies, and societies. The World Health Organization (WHO) declared the outbreak a Public Health Emergency of International Concern (PHEIC) on January 20th, 2020. WHO then categorized the outbreak as a pandemic on March 11th, 2020 although initial cases were reported in Wuhan, China in December of 2019.  

Countries around the world implemented lockdowns, travel restrictions, and mask mandates to slow the transmission of the virus. However, many countries have since lifted those restrictions as cases and deaths have declined. This is thanks to the development of vaccines and antiviral medications targeting the SARS-CoV-2 virus. 

Given the magnitude of this pandemic in such a scientifically advanced age, let's look at the COVID-19 cases and deaths statistics in the United States for exploratory analysis.

In this project, I ustilize the Tidyverse package in R to analyze the COVID-19 dataset imported from The New York Times. 

I calculate and plot the total numner of COVID-19 cases and deaths in the United States from March 15, 2020 to December 31, 2022. I then calculate the number of new cases and deaths per day and the 7-day average. With those calculations, I look at the days during the pandemic with the fewest number new cases & deaths, as well as the days with the largest number of new cases & deaths.  I also look at the difference between the average number of new cases & deaths and the median number of new cases & deaths, which was a difference of about 35%.

Finally, I imported population estimate data to calculate the number of new cases & deaths as well as the 7-day average per 100,000 people. With that I was able to plot a time series graph comparing the 7-day average of cases per 100,000 people to the 7-day average of deaths per 100,000 people. The plot showed some striking extremes as well as some expected trends. For instance, the 7-day average of both cases and deaths reached maximums during the winter months of each year, and the minimums occurred during the summer months. 

