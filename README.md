# MIST-4610-Project-2

# Team Name
47114 Group 6
# Team Members
Samuel Miller

Sophia Scarangello 

Arika Chiluvuri

Riley Eckstrom

Owen Donnelly

Michael Banks

# Dataset Description
Our dataset describes all of the crimes that were reported in the City of Los Angeles area from 2020 to present. The dataset is currently being updated bi-weekly to be up to date. We obtained our data from [https://catalog.data.gov/dataset](https://catalog.data.gov/dataset), and the specific link to our dataset is [https://catalog.data.gov/dataset/crime-data-from-2020-to-present](https://catalog.data.gov/dataset/crime-data-from-2020-to-present). Although our data contains much information about each crime, the notable attributes are the date the crime was reported, when the crime occurred, details about the offender, details about the victim, and different location measures of the crime. Each row in the dataset corresponds to one reported crime identified by a DR_NO or a department report number.

**Columns:**
DR_NO: This stands for "Division Report Number" or "Department Report Number," which is a unique identifier assigned to each crime incident report. (Number (whole))

Date Rptd: The date when the crime was reported to the authorities. (Date & Time)

DATE OCC: The date when the crime actually occurred. (Date & Time)

TIME OCC: The time when the crime occurred. (Number (whole))

MONTH OCC: The month of when the crime occurred. (String)

AREA: A numerical code representing the specific geographic area within Los Angeles where the crime took place. (Number (whole))

AREA NAME: The name of the geographic area corresponding to the AREA code. (String)

Rpt Dist No: This stands for "Reporting District Number," which is a smaller geographic unit within an AREA used for reporting and tracking crimes. (Number (whole))

Part 1-2: This could indicate whether the crime is classified as a Part 1 (more serious) or Part 2 (less serious) offense based on the FBI's Uniform Crime Reporting (UCR) system. (Number (whole))

Crm Cd: A numerical code representing the specific type of crime committed. (Number (whole))

Crm Cd Desc: A brief description of the crime corresponding to the Crm Cd. (String)

Mocodes: Additional codes that provide more details about the modus operandi (MO) or characteristics of the crime. (Number (whole))

Vict Age: The age of the victim. (Number (whole))

Vict Sex: The gender of the victim. (String)

Vict Descent: The descent or ethnicity of the victim. (String)

Premis Cd: A code representing the type of premises where the crime occurred. This could be a residence, commercial building, park, etc. (Number (whole))

Premis Desc: A description of the premises corresponding to the Premis Cd. (String)

Weapon Used Cd: A code indicating the type of weapon used in the crime, if any. (Number (whole))

Weapon Desc: A description of the weapon corresponding to the Weapon Used Cd. (String)

Status: A code indicating the current status of the crime investigation or case. (String)

Status Desc: A description of the status corresponding to the Status code. (String)

Crm Cd 1, Crm Cd 2, Crm Cd 3, Crm Cd 4: Additional crime codes if the incident involved multiple offenses. (Number (whole))

LOCATION: The location where the crime occurred, provided to the nearest hundred block address for privacy reasons. (String)

Cross Street: The nearest cross street to the location of the crime. (String)

LAT: The latitude coordinate of the crime location (missing data noted as (0°, 0°)). (Number (decimal))

LON: The longitude coordinate of the crime location (missing data noted as (0°, 0°)). (Number (decimal))


# Questions and Analyses
## Question 1
**What are the trends in average age for drug possession and trespassing crime types in LA in 2020?**

Importance: The trends in average age for drug possession and trespassing crime types from Los Angeles in 2020 provides an understanding of the demographics most involved in these crime types. This provides effective resource allocation, policy forming, and social service assistance. By analyzing trends in the average age of people arrested for drug possession and trespassing, policymakers and law enforcement can better understand if these issues affect specific age groups, such as youth or adults. This information can help with the creation of age-specific prevention and education programs, such as youth outreach programs or adult rehab services. Additionally, this analysis could reveal changes in crime trends over time, which is important for assessing the effectiveness of current policies. The data set used likely includes arrest records from law enforcement, which would provide the correct demographic details to conduct this analysis.

## Question 2
**What is the trend in the quantity of burglaries for the month of december and the forecast for the next 4 months of 2021.**

Importance: This question is significant economically and is important for public safety planning, as understanding seasonal trends and forecasting future occurrences of burglaries can help law enforcement allocate resources more efficiently and potentially reduce crime rates. The December analysis might reveal specific vulnerabilities or patterns that could inform the police to execute preventative measures during high-risk periods. Forecasting the next months allows police departments to prepare adequately, by increasing patrols or community alerts during expected peaks in criminal activity. Understanding these trends also assists in budget planning and resource allocation for community policing efforts. The data set for this question would include crime incident reports collected over time, enabling trend analysis and predictive modeling to forecast future occurrences based on historical data. This kind of analysis not only aids in immediate law enforcement response but also in long-term community safety strategies.

# Manipulations
One manipulation that we performed on the data was removing the time from the date/time column. There is a separate column for time already, and this was redundant data that was removed to improve readability. We did this by importing the data into excel, creating a separate column to clean the data, and performing the manipulation.

For one of our questions, we decided to forecast the quantity of specific crimes by month. In order to do this, we imported the data in excel to create a new column specifically for the month. With this new column, it allows us to more easily visualize our data and have a more readable data set. This would normally be a problem if the data spanned multiple years as the months in separate years would overlap, but the data is contained only within 2020, and the month of crime would not cross years.


# Results
## Question 1 Visualizations

## Question 2 Visualizations
