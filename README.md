# Team-Graphical Insights-DAEN-690
George Mason DAEN 690 Capstone Project Repository

## GMU Faculty and Researcher Experts List

**Product Owner:** Arias, Joseph Lacayo  
**Scrum Master:** Gundumogula, Koushik  
**Developers:** Jakku, Bhargav Teja | Roy, Koustav | Choi, Seung Gyu  

**Client:** GMU C4I & Cyber Center  
**Project POC:** Dr. Linton Wells, ll  
**Knowledge Domains:** Systems Engineering, Data Engineering, Data Mining, Natural Language Processing(NLP)  
**Skill Sets:** Screen scraping, Natural Language Processing, Python  
**New/Follow-on Project:** Follow-on Project  

**Problem Description:**  
Dr.Wells at the GMU C4I & Cyber Center, a source of frustration has been the difficulty in quickly locating individuals working on various related subjects, including Puerto Rico, AI, cybersecurity, European politics, and community resilience. His main objective was to find solutions to the problems faced through multidisciplinary collaboration. 

This project is based on the team project of the previous team, Demystifiers, which was based on the elements of data collection, natural language processing, database implementation, and database visualization. Therefore, in order to take it to the next level, we have expanded it in three main aspects: adding more accurate information about the people list, providing visualization and analysis tools in different ways to suit the needs of users, and migrating it to a cloud service so that all the information is easily accessible. 

The target scope of our project database is limited to the College of Engineering and Computing department. However, the previous team faced a lot of difficulties in obtaining more accurate information about the people within the CEC department. However, in this project, a list of academics provided by the CEC Human Resource Department allows us to include the status of academics within the department more accurately and reflect it in the overall project. In addition, the cloud environment has been built in such a way that different analysis and query tools can be used depending on the user's desired requirements. 

Neo4J offers a cloud service called Aura DB, which has the highest compatibility with their service. Aura DB also provides a free service that can be utilized depending on the capacity and purpose. Therefore, our team migrated all existing databases from the local version of Neo4J to the free cloud version of Aura DB so that we could access the service anytime, anywhere. 


**Project Goals:**  
The ultimate goal of the project was to help scholars find appropriate and effective multidisciplinary collaboration partners for their specific disciplines and research topics. The team's goals are broken down into three main elements:
- 1. The information of each scholar had to be as accurate as possible to reflect the number of faculty members in the CEC department.
- 2. All the information had to be accessible in a cloud environment, and how to effectively utilize the graph database had to be tailored to the user's needs to provide effective results. Therefore, our team provided a seamless user experience through Bloom, NeoDash, and Data Science tools provided by Aura DB, which can be utilized in various ways to meet user needs.
- 3. Provide a user experience for adding and modifying updated information through a web experience. However, the free Aura DB version has limited the use of REST APIs and connectable endpoints, so a service that allows scholars to update via the web remains a future work. 
 



**Project Deliverables:**  
Showcase Presentation & PowerPoint Slides  
Final Project Report  
GitHub Repository for data and code artifiacts  
Working Prototype 

**Repository Contents:**  
All of the code and datasets used in the project have been uploaded to the GitHub repository. For all code and data, the file classification and organization follow the below explanation :

-	Data Cleaning: This folder contains all the files used for data cleaning or created from the data cleaning process.

-	Data Scraping: This folder contains all the data collection files. This folder is where the self-built web scrapers are located.

-	Data: The folder contains all the data collected from the web scrapers or the final data generated through the data cleaning process.  

-   Natural Language Processing: This folder contains all the files used to complete the Natural Language Processing and obtained output files.

