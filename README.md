# **SpaceX  Falcon 9 first stage Landing Prediction**

# Lab 1: Collecting the data
In this capstone, will predict if the Falcon 9 first stage will land successfully. SpaceX advertises Falcon 9 rocket launches on its website with a cost of 62 million dollars; other providers cost upward of 165 million dollars each, much of the savings is because SpaceX can reuse the first stage. Therefore if we can determine if the first stage will land, we can determine the cost of a launch. This information can be used if an alternate company wants to bid against SpaceX for a rocket launch. In this lab, will collect and make sure the data is in the correct format from an API. The following is an example of a successful and launch.

<img src="https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBMDeveloperSkillsNetwork-DS0701EN-SkillsNetwork/lab_v2/images/landing_1.gif">

Several examples of an unsuccessful landing are shown here:

<img src="https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBMDeveloperSkillsNetwork-DS0701EN-SkillsNetwork/lab_v2/images/crash.gif">

Most unsuccessful landings are planned. Space X performs a controlled landing in the oceans. 

## Objectives
In this lab, will make a get request to the SpaceX API. You will also do some basic data wrangling and formating. 
- Request to the SpaceX API
- Clean the requested data

## Web scraping Falcon 9 and Falcon Heavy Launches Records from Wikipedia
In this lab, you will be performing web scraping to collect Falcon 9 historical launch records from a Wikipedia page titled `List of Falcon 9 and Falcon Heavy launches`

https://en.wikipedia.org/wiki/List_of_Falcon_9_and_Falcon_Heavy_launches

![](https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBM-DS0321EN-SkillsNetwork/labs/module_1_L2/images/Falcon9_rocket_family.svg)
