# CROPWEEDDETECTION_KREDDYPRASAD_USC_UCT
# Crop_weed_detection
INDUSTRIAL INTERNSHIP REPORT ON
CROP AND WEED DETECTION
Prepared by
K. Reddyprasad
Madanapalle Institute Of Technology and Science.

6 WEEKS( June -1 to July 15)



Executive Summary
This report provides details of the Industrial Internship provided by upskill Campus and The IoT Academy in collaboration with Industrial Partner UniConverge Technologies Pvt Ltd (UCT).
This internship was focused on a project/problem statement provided by UCT. We had to finish the project including the report in 6 weeks’ time.
My project was (Tell about ur Project)
This internship gave me a very good opportunity to get exposure to Industrial problems and design/implement solution for that. It was an overall great experience to have this internship.






TABLE OF CONTENTS
1.Preface………………………………………………………………………………………………...3
2.Introduction	4
2.1About UniConverge Technologies Pvt Ltd	4
2.2About upskill Campus (USC)	8
2.3Objectives of this Internship program	9
2.4Reference	9
    2.5Glossary…………………………………………………………………………………………………………………………………….9
3.Problem Statement…………………………………………………………………………………..10
4.Existed and Proposed statement……………………………………………………………………..10
    4.1Exisiting Approach………………………………………………………………………………10
     4.2Proposed Solution…………………………………………………………………………………………………………………..10
     4.3Code Submission (Github Link)…………...………………………………………………………………………………….10
     4.4Report Submission (Github Link)…………………………………………………………………………………………….10
5.Proposed Design/Model……………………………………………………………………………………………………………….11
    5.1High Level Diagram………………………………………………………………………………………………………………….11
    5.2Low Level Diagram…………………………………………………………………………………………………………………..11
    5.3Interfaces……………………………………………………………………………………………………………………………..…11
6.Performance Test………………………………………………………………………………………………………………………….12
    6.1Test Performance/Test case……………………………………………………………………………………………………..12
7.Result and Analysis.………………………………………………………………………………………………………………………12
8.Conclusion…………………………………………………………………………………………………………………………………….12
9.Future Work………………………………………………………………………………………………………………………………….12
10.My Learnings………………………………………………………………………………………………………………………………13







1. Preface
Summary of the whole 6 weeks’ work.
About need of relevant Internship in career development.
Brief about Your project/problem statement.
Opportunity given by USC/UCT.
How Program was planned
 
Your Learnings and overall experience.
Thank to all (with names), who have helped you directly or indirectly. 
Your message to your juniors and peers.
 
2.Introduction
2.1About UniConverge Technologies Pvt Ltd
A company established in 2013 and working in Digital Transformation domain and providing Industrial solutions with prime focus on sustainability and RoI.
For developing its products and solutions it is leveraging various Cutting Edge Technologies e.g. Internet of Things (IoT), Cyber Security, Cloud computing (AWS, Azure), Machine Learning, Communication Technologies (4G/5G/LoRaWAN), Java Full Stack, Python, Front end etc.
 
i.	UCT IoT Platform ( )
UCT Insight is an IOT platform designed for quick deployment of IOT applications on the same time providing valuable “insight” for your process/business. It has been built in Java for backend and ReactJS for Front end. It has support for MySQL and various NoSql Databases.
•	It enables device connectivity via industry standard IoT protocols - MQTT, CoAP, HTTP, Modbus TCP, OPC UA 
•	It supports both cloud and on-premises deployments.
It has features to
• Build Your own dashboard
• Analytics and Reporting
• Alert and Notification
• Integration with third party application(Power BI, SAP, ERP)
• Rule Engine

   


ii.	Smart Factory Platform ( )
Factory watch is a platform for smart factory needs.
It provides Users/ Factory 
•	with a scalable solution for their Production and asset monitoring
•	OEE and predictive maintenance solution scaling up to digital twin for your assets.
•	to unleased the true potential of the data that their machines are generating and helps to identify the KPIs and also improve them.
•	A modular architecture that allows users to choose the service that they what to start and then can scale to more complex solutions as per their demands.
Its unique SaaS model helps users to save time, cost and money.

(iii)  based Solution
UCT  is one of the early adopters of LoRAWAN teschnology and providing solution in Agritech, Smart cities, Industrial Monitoring, Smart Street Light, Smart Water/ Gas/ Electricity metering solutions etc.
iii.	Predictive Maintenance
UCT is providing Industrial Machine health monitoring and Predictive maintenance solution leveraging Embedded system, Industrial IoT and Machine Learning Technologies by finding Remaining useful life time of various Machines used in production process.

2.2About upskill Campus (USC)
upskill Campus along with The IoT Academy and in association with Uniconverge technologies has facilitated the smooth execution of the complete internship process.
USC is a career development platform that delivers personalized executive coaching in a more affordable, scalable and measurable way.

1	The IoT Academy
The IoT academy is EdTech Division of UCT that is running long executive certification programs in collaboration with EICT Academy, IITK, IITR and IITG in multiple domains.

2.3Objectives of this Internship program

The objective for this internship program was to
 ☛ get practical experience of working in the industry.
 ☛ to solve real world problems.
 ☛ to have improved job prospects.
 ☛ to have Improved understanding of our field and its applications. 
 ☛ to have Personal growth like better communication and problem solving.


2.4Reference
•	Introduction to data science and machine learning and data science by Davy Cielen, Arno D.B. Meysman, Mohamed Ali.
•	An introduction to probability and statistics by Vijay K. Rohatgi and A.K.Md. Ehsanes Saleh.
•	Introduction to Machine Learning by Alex Smola and S.V.N. Viswanathan

2.5	Glossary 
Terms 	Acronym 
Numpy  	An Open First, I can’t library, that’s used in almost every field of Computer science and engineering 
Pandas 	A python Library used for working with data set 
Decision tree 	A type of supervised machine learning used to categorize or make predictions based on how a previous set of questions were answered 
Sklearn 	An open-source data analysis, library function and the gold standard for machine learning in python ecosystem. 
Matplotlib 	Across play the song, database relation and graphical plotting library for python, and it’s numerical extension Numpy 




3. Problem Statement

Agricultural fields often face challenges in differentiating between crops and weeds. Weeds can hinder crop growth by competing for resources such as sunlight, water, and nutrients. Manual weed detection and management are time-consuming and labor-intensive tasks. Therefore, the need for an automated crop and weed detection system arises to aid farmers in making informed decisions regarding weed control and crop management.

4. Existing and Proposed Solution

4.1 Existing Approaches

Before the internship, various techniques, including manual inspection, traditional computer vision methods, and rule-based systems, were used for crop and weed detection. However, these approaches lacked accuracy, efficiency, and scalability.

4.2 Proposed Solution

To overcome the limitations of existing approaches, I proposed the development of a machine learning model for crop and weed detection. The model would be trained on a dataset containing labeled images of crops and weeds. By leveraging deep learning techniques and advanced image analysis algorithms, the model aimed to accurately classify and locate crops and weeds within images.

4.3 Code Submission (Github Link) 
https://github.com/YasinKhanP/Crop_weed_detection.git
4.4Report submission (Github link)  :
https://github.com/YasinKhanP/Crop_weed_detection/blob/main/README.md


5. Proposed Design/Model

5.1 High-Level Diagram

The proposed solution involves a high-level architecture that consists of data preprocessing, model training, and prediction stages. The input images undergo preprocessing steps such as resizing, normalization, and augmentation before being fed into the machine learning model.

5.2 Low-Level Diagram

At a lower level, the machine learning model comprises convolutional neural networks (CNNs) such as ResNet or VGG, which are trained on the labeled dataset. These CNNs extract relevant features from the images and make predictions regarding the presence and location of crops and weeds.

5.3 Interfaces

The developed model can be integrated into an intuitive user interface, allowing farmers to upload their field images for analysis. The interface would provide the classification results and highlight regions of potential weed growth.


6. Performance Test

6.1 Test Plan/Test Cases
To evaluate the performance of the crop and weed detection model, a comprehensive test plan was devised. Test cases included a variety of field images captured under different lighting conditions, perspectives, and weed densities. The performance metrics focused on accuracy, precision, recall, and F1 score.

7. Results and Analysis

The developed machine learning model demonstrated promising results in crop and weed detection. The accuracy achieved was X%, with precision, recall, and F1 score of X%, X%, and X%, respectively. The model successfully distinguished between crops and weeds, providing farmers with valuable insights for weed management strategies.

8. Conclusion

The internship provided a valuable opportunity to work on the challenging task of crop and weed detection using machine learning and data science. The developed model showcased promising results in accurately identifying and locating crops and weeds in agricultural images. This has the potential to revolutionize weed management practices and optimize crop yield for farmers.

9. Future Work

Future enhancements to the crop and weed detection system could include:
- Integration with satellite imagery and drone data for large-scale monitoring.
- Continuous model refinement through active learning and transfer learning techniques.
- Development of a mobile application for real-time on-field analysis and decision-making support.



10.My Learnings

This internship report provides a comprehensive overview of the project on crop and weed detection using machine learning and data science. The successful development of a machine learning model for accurate crop and weed identification has the potential to significantly impact the agricultural industry. It is hoped that the findings and recommendations presented in this report will contribute to ongoing research and innovation in the field of agricultural technology.
