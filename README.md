
## Reasons Behind Failed Medical Appointments ##
### [Case Study: Brazil]

**Name of Dataset:** Medical Appointments No Shows
**Description of Dataset:**
This dataset collects information from over 100k medical appointments in Brazil and is focused on the question of whether or not patients show up for their appointment and the associated characteristics of each patient.

## Data Wrangling Overview

Before exploring the data set, it was read into jupyter notebook as a dataframe using pandas *.read_csv()* method. After which, the dataframe was assessed for tidiness and quality issues. The result of the assessment showed that the column names and the *Handcap* column records had quality issues and needed modification. While duplicate records were dropped. Furthermore, the assessment confirmed that there were no missing records, outliers, or null values. 

## Summary of Findings

My analysis of this data set focused on which age group were more responsive to their medical appointments and what were the likely factors that contributed to their response. Exploratory analysis revealed that adults between the age range of 25 to 65 years old were most responsive to their appointments. With the majority being between 25-38 years of age. Also, most adults suffered from hypertension and those within this category seemed to be more concerned about their health than others as they were most responsive to their appointments. Additionally, text message reminders as well as enrollment in the scholarship program did not have any impact in the responsiveness of those who visited on the day of their appointment.

## Key Insights for Presentation 

To get the age group that were most responsive to their medical appointment, I classified each age value into one of four age group I created (children, youths, adults, seniors) and store them as entries/values in a new column called *age-grp*. Afterwards, I filtered the dataframe selecting only rows where the *visits* column value was *yes* indicating that the patient responded to the appointmnt. Then I made a bar plot to visualize the frequency by age group to find out which age group had the most visits. From the plot returned, adults aged between 25 to 65 years of age had the most response followed by children, youths, and finally seniors. 

> More details of the insights from the analysis can be found in the *html* or *ipynb* file of this project
































