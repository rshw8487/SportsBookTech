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
