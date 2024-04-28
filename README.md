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
Our dataset describes all of the crimes that were reported in the City of Los Angeles area from 2020 to the present. The dataset is currently being updated bi-weekly to be up to date. We obtained our data from [https://catalog.data.gov/dataset](https://catalog.data.gov/dataset), and the specific link to our dataset is [https://catalog.data.gov/dataset/crime-data-from-2020-to-present](https://catalog.data.gov/dataset/crime-data-from-2020-to-present). Although our data contains much information about each crime, the notable attributes are the date the crime was reported, when the crime occurred, details about the offender, details about the victim, and different location measures of the crime. Each row in the dataset corresponds to one reported crime identified by a DR_NO or a department report number.

***Columns:***

![image](https://github.com/SamuelMiller2/MIST-4610-Project-2/assets/150087690/2e041c9a-60ed-4c29-8a51-147cb24fadcf)![image](https://github.com/SamuelMiller2/MIST-4610-Project-2/assets/150087690/59ea9c2e-d7f1-4b5d-b856-b2d4d6ca432d)![image](https://github.com/SamuelMiller2/MIST-4610-Project-2/assets/150087690/d6e30bf9-c92e-4ad2-ab8a-79342188441b)





# Questions and Analysis
## Question 1
**What are the average ages for minor victims (under 18) for each crime type within the data set?**

Importance: Understanding the average age of minor victims affected by each crime type is crucial for improving safety measures within the Los Angeles school system. By pinpointing when students are most vulnerable to different types of crimes, schools can tailor interventions and programs to specific grade levels or age groups, ensuring maximum effectiveness. Additionally, this knowledge enables schools to offer targeted victim support services, reaching out to the age groups most affected and providing relevant assistance. Also, by moving away from a one-size-fits-all approach to safety, schools can cater their educational efforts to the developmental stage of each student. In other words, they will be able to address relevant crimes and preventive measures at the appropriate maturity level when the students can comprehend the difficult concepts. Furthermore, by having insight into the age demographics of crime victims, the city of Los Angeles can craft more effective safety campaigns that resonate with each age group's specific interests and concerns. Finally, the city of Los Angeles will be able to better educate parents on how to protect their kids and which crimes they should be vigilant of during each stage of their child's development. 

Analysis: Upon analyzing the data, we segmented the victims into age brackets of 5 years for our analysis. For children aged 0-5 years, the most prevalent crime against them is childhood abandonment. It would be hard to educate these children considering they cannot speak or read, so we would focus more on educating parents about planned pregnancy or the adoption process. In the 6-10 year age group, prevalent crimes include child neglect, simple battery, and offenses against children. Despite the emphasis on "stranger danger" in educational settings, it's crucial to also educate children on recognizing signs of neglect and promoting healthy family dynamics. Tailoring age-appropriate guidance on basic defense tactics or conflict resolution would be especially useful. In particular, we would want to do this training around age 9 because  10-year-olds show the largest increase in simple battery cases. Moving to the 11-15 year age group, child abuse emerges as the primary concern. Given that abuse often originates within the family unit, it is important to promote discussions on healthy familial relationships. Providing resources such as contact information for shelters, self-defense classes, and therapy could help mitigate familial tensions and empower adolescents to seek help when needed. In the 16-18 year age bracket, crimes such as unlawful sex, human trafficking, and kidnapping are more prevalent. By this age, adolescents should have received training to identify uncomfortable and risky situations in general. However, it becomes essential to focus discussions on sexual acts and related risks because this age group is mature enough to comprehend the topics and is disproportionately affected. Implementing these policies is critical to equipping children with the knowledge and skills to recognize dangerous situations to protect themselves and their peers.

## Question 2
**What is the trend in the quantity of burglaries for the month of December**

Importance: This question is economically significant and is important for public safety planning, as understanding seasonal trends and predicting a forecast for future occurrences of burglaries can help law enforcement allocate resources more efficiently and potentially reduce crime rates. The December analysis might reveal specific vulnerabilities or patterns that could inform the police to execute preventative measures during high-risk periods. The month of December experiences an increased rate of burglaries and theft due to the holidays and individuals trying to acquire gifts for their families. This makes the modeling for December especially important. Predicting a forecast the first month allows police departments to prepare adequately, by increasing patrols or community alerts during expected peaks in criminal activity. Understanding these trends also assists in budget planning and resource allocation for community policing efforts. The data set for this question would include crime incident reports collected over time, enabling trend analysis and predictive modeling to forecast future occurrences based on historical data. This kind of analysis not only aids in immediate law enforcement response but also in long-term community safety strategies.

# Manipulations
One manipulation that we performed on the data was removing the time from the date/time column. There is a separate column for time already, and this was redundant data that was removed to improve readability. We did this by opening the dataset in Excel and using a function to perform said manipulation.

For one of our questions, we decided to forecast the number of specific crimes by month. To do this, we opened the data in Excel and created a new column specifically for the month. This new column helped us to visualize our data and improve readability. This would normally be a problem if the data spanned multiple years as the months in separate years would overlap, but because data is contained in 2020, the month of crime would not cross years.


# Results
## Question 1 Visualization
<img width="808" alt="image" src="https://github.com/SamuelMiller2/MIST-4610-Project-2/assets/163002732/168b9809-2462-4fef-87a7-8cb624e87624">

## Question 2 Visualization
![image](https://github.com/SamuelMiller2/MIST-4610-Project-2/assets/150087690/bca5ac15-1c63-40e4-bc21-d9d0f0404cb1)
![image](https://github.com/SamuelMiller2/MIST-4610-Project-2/assets/150087690/b956e60a-2b4a-40b7-9513-cd70fd044207)




# Tableau Packaged Workbook
Note: We had to upload them to Google Drive, our workbook files are too large for GitHub.
https://drive.google.com/drive/folders/1pgqyDfCVWh4S1eCxYFqDDsgaDenliVnM?usp=drive_link
