# Section A – Simple Programming Task documentation
Please navigate to "Section A – Simple Programming Task" documentation to check the solution:
 https://github.com/rshw8487/SportsBookTechQATask/tree/master/src/main/java/SectionA
 
# Section B - Real life case

 # Case 1: Automation
 
 Please navigate to "Section B - Real life case documentation" to check the solution:
 https://github.com/rshw8487/SportsBookTechQATask/tree/master/src/main/java/SectionB
 
 # Case 2 : Performance
 
Without any implementation needed, how would you execute the following different types of performance tests on
any endpoint of your choosing?
• Load testing,
• Stress testing,
• Endurance testing,
• Spike testing,
• Volume testing, and
• Scalability testing.

How would you store your result set, what KPI’s would you be after, and how could you make the tests consistently
reproducible on demand? 

 # Solution:
1.Load Testing:

Load Testing Load testing includes increasing the load and see how the system behaves under higher load.
We can monitor response times, throughput, server conditions, and more.
The goal is to find metrics for system performance under high load.
In or case:

mockaroo API is limited for 1000 rows to download (Free);
openweathermap API is limited to 60 calls per minute (Free);
xignite API 250 hits for 7 days (Free Trial, valid to )

2.Stress Testing

The goal of stress test is exactly that, to find the load volume where the system actually breaks or is close to breaking.
So we need to find the system breaking point.
As you may check openweathermap API breaks after 60 calls because of Free Plan limitation.
And in the and count of advices of SunnyWetherAdvicer get only 5 cases (src/main/resources/recommendedSunnyCitiesList.txt)

3.Scalability Testing

For example, a larger number of incoming requests should cause proportial increase in the response time.
In the end we can use metrics and check if the system performance changes appropriately to the load.
Test could be runned from src/test/java/SoupUiTest.java
Test results would be stored to SportBookTechQATask-soapui-project.xml

4.Endurance Testing

Endurance testing determines the longevity of components, and if the system can withstand average to peak load over a predefined duration. Memory utilization should be observed to detect potential failures. The testing will also measure that throughput and response times after sustained activity continues to meet performance goals.

5.Spike Testing

It is conducted to find out the stability of the system when it is loaded in burst of very small time and releasing the load quickly.
For example – viewing real time replays of video streams (games) while there is a goal / wicket / six.

6.Scalability Testing

Scalability differs from Load Testing in the fact that scalability test measures the system at the minimum and maximum loads at all levels, including the software, hardware and database levels. Once the maximum load is found out, developers need to respond appropriately to ensure that the system is scalable after a particular load.
For Example - If scalability testing determines the maximum load to be 10,000 users, then for the system to be scalable, developers need to take measures on factors such as decreasing response time after 10,000 user limit is reached or increasing the RAM size to accommodate the growing user data.

Regarding "KPI’s would you be after, and how could you make the tests consistently reproducible on demand" - 
It's really depends of the project needs and purposes.
