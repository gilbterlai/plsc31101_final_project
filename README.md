# plsc31101_final_project

This is Gilbert's final project for PLSC31101

## Short Description

This code webscraped People's Daily to get articles about "China Threat", and then get China's GDP, military expenditure and Polity V data. By doing a regression of the above data, we can know which drives "China Threat" discourse.

## Dependencies

R, 4.0.2

## Files

### /

1. Narrative.Rmd: Provides a 3-5 page narrative of the project, main challenges, solutions, and results.
2. Narrative.pdf: A knitted pdf of Narrative.Rmd. 
3. Presentation.pptx: Slides for brief presentation of code and results
4. preamble.tex: I include this in the Narrative.Rmd to fix the position of figures.

### Code/

Note that I used Rmd. rather than R. because I find it more convenient to include text.

1. People's_Daily_Webscraping.Rmd: webscrapes People's Daily to get articles about "China Threat."
2. Data_Manipulation.Rmd: processes data about "China Threat," China's GDP, military expenditure, and Polity V score.
3. Data_Analysis.Rmd: Using the data we get, do a plot and regression.

### Data/

1. webscraping_df.csv: data scraped from People's Daily saved here.
2. military_raw.xls: military expenditure data from World Bank Database.
3. GDP_raw.xls: GDP data from World Bank Database.
4. p5v2018.xls: Polity V index from Polity Project.
5. df_final.csv: data resulted from Data_Manipulation.Rmd, including number of arctiles about China Threat as a whole, China as an economic threat, miliary trhreat, and political threat, also including China's GDP, military expenditure and Polity V score.
6. df_threat.csv: a long format of data about China Threat as a whole, China as an economic threat, miliary trhreat, and political threat.

### Results/

1. China_Threat_Discourse_Over_Time.png: "China Threat" discourse over time.
2. China_Threat_With_Changing_Capabilities.png: "China Threat" and China's changing GDP, military expenditure and Polity V.
3. Regression_Plot.png: does a regression with the above data.
4. regression_table.html: regression model by using stargazer.
5. regression_table.png: the picture format of the above model.
6. Plot_Annotated.png: "China Threat" discourse over time with annotation that marks the three highest peaks. 

## More Information
Gilbert Lai
University of Chicago
