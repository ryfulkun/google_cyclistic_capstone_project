# Google Cyclistic Capstone Project.

## Capstone project for google data analytics course



### ASK: Identify the Business Task:
---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
Cyclistic is a successful Bike sharing company with 5824 bicycles in its fleet, geotracked and locked into 692 Stations all across the city of Chicago. They also provide accessible bikes as well the standard 2 Wheeler Bikes to include all types of people.

There are 3 types of riders, 

Single-ride users
Full day pass users
Annual Memberships

Cyclistic have identified that Annual Memberships are the most profitable. They believe that turning the casual riders(single-ride, Full day pass users) into Annual Memberships will drive up profits for Cyclistic and they want to know how Annual Members and Casual riders differ.

They key questions we will be asking are:

- How much do casual riders represent all riders compared to members?
- What is the average time spent on the bikes by each user?
- Where are the most popular stations?
- Which days of week are casual riders using the service more compared to members?
- Which months has the most riders?

this will help us answer the main question "How do annual members and casual riders use Cyclistic bikes differently and provide recommendations for the marketing and finacial team.

### Prepare:
---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

The data was provided by Cyclistic stored on their database server. It is given in .zip files and organised in .csv files. The Data user data from April 2020 - September 2021. The Data is secure and only provided for use of this analysis. All privacy information has been excluded and will not be included to answer the key questions.

The Dataset used consisted of 12 .cvs files which include columns:

- ride_id
- rideable_type
- started_at
- ended_at
- start_station_name
- start_station_id
- end_station_id
- end_station_name
- end_station_id
- start_lat
- start_lng
- end_lat
- end_lng
- member_casual

Upon Discovering such a large data set I have ruled out the use of excel as it would be far too time-consuming to load and clean the data, so I have decided my main tool will be to use R Programming. Once cleaned i can export summary .cvs files to do extended analysis. both R and excel will be used to visualization of the data.

### Process:
---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

Firstly the data need to organise and clean the data before analysis is done

### Tools 
R programming is used to gather the datasets into one file and clean the data where Excel was used for further analysis.

* Click here to view my R Markdown file for the complete analysis process used

```












