# North Carolina School Enrollment 

This is a comparison between the enrollment rates or age groups, from preschool to university, of North Carolina Students in public and private schools. Both the enrollment of public and private schools are also compared to the total enrollment rate across all students in the state. 

## Data Sourcing 

The data used was sourced from the United States Census Bureau 
This data is a combination of estimations and information collected in 2022 by the American Community Survey

The data can be found using this link 
[https://data.census.gov/](https://data.census.gov/table/ACSST1Y2022.S1401?q=schools%20in%20north%20carolina)

## About the Data 
### Findings 

The purpose of this repository was to investigate the enrollment differences between the makeup of private and public schools in North Carolina 

### The Starting Point: Large Data Set

The large data set from the Census Bureau, *NCed*, contained estimates and percentages across total enrollment, private school enrollment, and public school enrollment

### Analyzing The Large Data: Subsets

From this larger dataset, a new dataset *Enrolled* was created only showing the percent of the eligible population enrolled in every school age group

*Enrolled*, as a controlled variable, was collected and placed into a visualization expressed in percent of total eligible population 

![enrollment-bar-chart](images/TotalEnroll.jpeg)

Another subset was created, *PrivatePublic*, separating the enrollment rates of school age groups in public and private schools

Then, using the variables *Percent in Public School Estimate* and *Percent in Private School Estimate* the two enrollment rates were separated and compared to each other 

![enrollment-bar-chart](images/PrivPubBarChart.jpeg)

## Conclusions

From these subests, we can see that enrollment rates are consistently higher in public schools in the state of North Carolina

From Kindergarten through Graduate school, there is an average of nearly 75% enrollment in public institutions, and about 25% in private

The only exception to this is nursery school/preschool
Perhaps due to high childcare costs or the ways these instutions are classified, this data point is an outlier as enrollment in public and private schools for children aged 3-5 is nearly even

## About the Repository

This repository is made and maintained by Kara Dugan, with the intent of clearly outlining the differences between public and private schools for future use discussing the funding allocated to these institutions and the perceptions surrounding them 

For clear, unedited data, users should refer to the original source for help with interpretation

The data can be found using this link 
[https://data.census.gov/](https://data.census.gov/table/ACSST1Y2022.S1401?q=schools%20in%20north%20carolina)
