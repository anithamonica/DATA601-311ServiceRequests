# 311 SERVICE REQUESTS
311 is a non-emergency government service that helps citizens to report issues and access city information. It can be accessed by phone, online, or through mobile apps and often includes multilingual support and services for vulnerable populations like the senior residents. The 311 system collects all requests, which are then routed to the responsible city department for resolution. It operates 24/7 and allows users to track the progress of their requests, ensuring transparency and accountability. Thus the 311 services make the lives of the residents easier and saves their time by eliminating the need to contact multiple departments for resolving their concerns. The user-friendly interface of 311 also makes the communication with the local government effortless, convenient and accessible for everyone.


## DATA ANALYSIS
Analysis of 311 data over a long period of time helps us in determining the most frequent service requests which can be addressed more efficiently by allocating adequate resources. This can also be used to identify the efficiencies of different departments and the gaps where improvement is required. Seasonal patterns and long term trends can also be identified which can be used to predict the future demands and optimize the public services. By tracking types of requests, response times, and areas with frequent complaints, resources can be allocated more effectively, and operational inefficiencies can be identified and resolved. The residents will get a clear picture regarding the handling of their concerns which promotes transparency. Proactive planning is made possible, allowing for better resource distribution and improved service delivery. Ultimately, systemic issues can be identified, and solutions can be developed,leading to improved city planning and enhanced community satisfaction.

## REPO PURPOSE:
This is a Python Project for Analysis and Visualization of "311 Service Requests" submitted for The City Of Calgary. It includes data analysis and visualization for 311 Service Requests of Calgary for the years 2023 and 2024.
  
## Files Included in the Repo: 
1. Documents Folder:
   1. Project Proposal PDF
   2. Project Proposal PPT
2. ReadMe.md
3. Final report ipynb:
   311ServiceRequestFinalReport.ipynb
4. Project Report PPT
5. Datasets:
   1. 311_Service_Requests_2yrs.csv : dataset for 311 requests
   2. CSV_SECTORS.csv  : Community Sectors
   3. Community_District_Boundaries_GeoJson.csv : Calagary district boundary

## DATA SOURCE: 
The City Of Calgary Open Data Portal: 311 Service Requests- Services And Amenities.


## PROJECT OBJECTIVE AND FOCUS AREAS:
1. Gerographic analysis of 311 requests
2. Identification of Seasonal Trends
3. Request resouce study and suggest improvements
4. Detailed study on Response efficiency
5. Analysis of Trends Over time.


## INSIGHTS GAINED

### Geographical Insights: 
The Downtown community has the largest number of requests, potentially making it a key area for focusing efforts in terms of both service delivery and resource allocation. Communities like 05G show fewer requests, possibly indicating a need to investigate why this is the case — whether it's due to lower demand or a gap in service awareness or it is under development. Road-related services remain in high demand across multiple sectors, while there’s also a critical need for Waste and Water Management Services (WRS), particularly in the Southeast region. This highlights regional disparities and may require more localized resource allocation.

<img width="500" alt="Screenshot 2025-02-13 at 9 50 13 PM" src="https://github.com/user-attachments/assets/8d023ad0-a63b-4398-80b2-2d8934f50286" />

### Service Request Trends: 
Seasonal demand patterns indicate high demand in Summer and Autumn, while there is a slight dip in Spring and decrease in Winter. This suggests that planning and resources should be allocated more heavily during peak months.

<img width="500" alt="Screenshot 2025-02-13 at 10 10 53 PM" src="https://github.com/user-attachments/assets/f4ed8260-2e19-4d0c-9164-94282b53a4a8" />

### Agency Load: 
Operational Services and Compliance agencies are receiving the most requests, which could imply a higher volume of work or a need for better resource management to handle the influx. Agencies like Fleet and Inventory are managing fewer requests, which might suggest a more balanced workload or a potential area where additional support could be needed for future demand.

<img width="500" alt="Screenshot 2025-02-13 at 10 10 00 PM" src="https://github.com/user-attachments/assets/a33ed1eb-e7db-43d6-b5b2-7f8f5270972b" />

### Request Sources: 
Majority of 311 service requests come from email and social media, making it the most used source. Phone and mobile apps follow, showing significant usage. However web requests are minimal indicating a strong preference for other channels.

<img width="500" alt="Screenshot 2025-02-13 at 10 08 42 PM" src="https://github.com/user-attachments/assets/0affd846-59f0-41d5-9a6a-bfe3d6c623c1" />

### Type of Service Requests: 
Roads and Waste and Recycling Services appear as the most frequent service requests, which may suggest that maintaining and upgrading these infrastructures should be prioritized.

### Response Efficiency: 
The average response rate for 311 service requests for the two years 2023 and 2024 is 0.99 which indicates the responsiveness of the system. The requests were handled and closed within an average time of 12.63 days.

<img width="481" alt="Screenshot 2025-02-13 at 10 07 37 PM" src="https://github.com/user-attachments/assets/04980ea8-0ddb-4627-b28e-ffffc1f42493" />

The service categories Roads(24 days) and Water Service (20 days) have the longest response times, highlighting potential bottlenecks. Bylaw, CT, and Corporate services also show moderate delays (around 14–16 days). In contrast, WRS, DBBS Inspection, and CBS Inspection are the quickest, averaging under 5 days. Overall, infrastructure-related services face slower responses, while inspections and waste services are more efficient.

<img width="500" alt="Screenshot 2025-02-13 at 10 06 42 PM" src="https://github.com/user-attachments/assets/e14f8f52-0c71-4d6e-bca8-2c4095931f67" />

The agencies with the least response delays are Elected Officials, Office of the City Auditor,Corporate Wide Service Requests. The agencies with the highest response delays of over 15 days are Operational Services and Compliance, Information Services, Community Services.The first two has improved their response times significantly in 2024 compared to 2023. In 2024, all the closed requests were addressed and handled by the respective agencies under 16 days.

<img width="500" alt="Screenshot 2025-02-13 at 9 47 58 PM" src="https://github.com/user-attachments/assets/e29b7a75-43cf-4b69-852c-88dd193f0d4f" />


### Trends Over Time: 
It is observed that the number of service requests saw a sharp spike in mid 2023, decline after the peak and there is a small rise by mid 2024, but it is lower than previous peak. A steady delcine after mid 2024 towards early 2025 is also observed. This could be due to seasonal factors, specific events or other time sensitive issues.

<img width="500" alt="Screenshot 2025-02-13 at 10 04 29 PM" src="https://github.com/user-attachments/assets/dc2150e4-6ac6-49fb-bf0a-8ab512c624e3" />

## SUMMARY

The analysis shows that service requests peak in Summer and Autumn. "Operational Services and Compliance" handles the most requests, while "Fleet and Inventory" handles the least. Response times improved in 2024, but infrastructure services still face delays. There is a high demand for roads and waste management, especially in the Center. The Downtown area has the most requests, while the 05G area has the least.
Requests are higher on weekends, mainly coming from Email and Social Media, with few from the web. The volume of requests peaked in mid-2023, dipped, rose slightly in 2024, then steadily dropped. Roads and Water Services have the longest delays, showing bottlenecks. The Finance department is the most engaged in addressing requests.

## SUGGESTIONS

1. address the identified bottlenecks in Roads and Water Services, we recommend increasing resources and improving processes in these areas to reduce delays
2. Considering the seasonal peaks and weekend surges in service requests, it is essential to plan for increased staffing and resource allocation during these times.
3. Although this analysis provides valuable insights, further investigation into the specific causes of delays in infrastructure services is needed to develop more targeted solutions.
