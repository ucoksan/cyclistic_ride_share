# Cyclistic Trip Share

Cyclistic a bike-share company with a fleet of 5,824 geotracked bicycles and locked into around 692 stations across Chicago. The bikes can be unlocked from one station and returned to other station in the system anytime. 

To using the bike share, Cyclistic offers pricing plans to customer: single ride passes, full ride passes and annual memberships. Customers who purchased single day or full day passes are referred to as casual riders. Customers who purchase annual memberships are Cyclistic members.

## Business Task

The company have concluded that annual members are much profitable than casual riders. For this reason, the company wants to increase the annual members. Instead of approaching a new customers, the company's marketing decide to convert casual riders into annual members.

By understanding what and how both group differs in using bike-share, the next marketing strategy to fulfill the goals can be determined.

## Data Source

1. The source of data: https://divvy-tripdata.s3.amazonaws.com/index.html
2. The dataset is from real case made by **Motivational International Inc.** under this license (https://www.divvybikes.com/data-license-agreement) using for study since the Cyclistic is a fictional company.
3. The dataset consist of ride id, the type of used bike, start and end of riding period, name and id of the start/ finish station including the coordinate and the membership categories.
4. Around 14% of data have missing value of station name because the location is not detected as listed station based on recorded location coordinate. 

## Data Preparation Process

For this dataset, preparing and cleaning is by using **RStudio**

The dataset is stored in : "D:/Data Analytics Course/Data/Cyclistic Data/Annual Data"

## What We Got from Analysis Result

1. The trips by casual riders population is higher than the members.
2. Number of members trip in weekday (Mon -  Fri) is higher than casual riders, while in the weekend (Sat – Sun) in the casual rider’s trips is higher than the members.
3. Casual riders tend to have longest average trip duration than the trip by members.
4. There is no significant change of the average trip duration of member riders within the last 12 months, while casual riders have significant rise in average trip duration on February 2021.
5. Casual riders have significant increase in trip number from 2020 to 2021. In Jul-August 2021 casual riders have more trips than members.
6. Members have higher portion in classic bike use. While casual riders have higher portion in docked bike. For electric bike, both rider types have similar portion.
