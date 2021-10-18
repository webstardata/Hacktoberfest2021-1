
=======================================================

Article Title: Crowd Control For Covid-19 
Author Name: Crowd Control For Covid-19 
Author Profile: https://github.com/tanmaysinha00
Date: 18/10/2021

=======================================================

Abstract
					
a) Background 
With the rise in the number of Covid-19 cases over the world, social distancing has become an important safety measure. 
It is advised to stay at a distance of at least 6 feet from other people to reduce the spread of the virus. 
However, it is very difficult to maintain social distancing in public places like malls and stores due to the large crowd present in an enclosed area.
This has caused many problems for shop owners and other market sellers to keep track of the number of customers in their shops so that social distancing can be practiced optimally.
The current method of tracking customers in a given shop is manual, by keeping a watchman, which is very tedious, expensive to implement, and not reliable.

b) Problem Definition 
Manually counting the number of people in a location is very tedious.
It also involves adding more people like watchmen to the area and hence also increases the count of people along with the risk of contracting Covid. 
Hence, there is a need to fulfill the above role without engaging manpower in it. 
The primary aim of our project is to solve the above problem by counting people in a store or mall in real-time and alerting the authorities if the maximum limit is reached. 
We plan to tackle the above-mentioned problem using Computer Vision. The CCTV Camera feed will be retrieved in real-time and will be passed through our model. 
It will detect the number of people entering and leaving an area and the data will be stored. This concept has multiple benefits over manual counting and is yet to be implemented in malls and stores. 
We plan to build this solution for local business stores and malls to give them more control over their customer counts. The use case is counting people in real-time and sending an alert if the limit is reached. 
The camera feed can be directly retrieved from the CCTV cameras already installed in the stores. Hence, this solution has a negligible hardware cost. This project can be scaled for larger regions and areas too. 
The real-time stream can also be optimized for better performance using threading. Schedulers and timers also make the work of shopkeepers easy. 
This acts as a measure towards footfall analysis and in a way to tackle COVID-19.




Objective (Five major contributions to the project):

1. Real-Time people counter:
This is the main feature of our project. It counts the number of people present in an enclosed
area by taking data from the CCTV real-time stream. This enables a shop to get to know how
many people are present in their shop.

2. Real-Time alert:
This feature will send an alert to the user (shopkeeper or staff) in real-time. If the total
number of people (say 10 or 30) is exceeded in a store/building, we simply alert the staff so
that they can take necessary action to maintain social distancing. The maximum value of the
total number of people can be set by the staff. This is very useful considering the COVID-19
Scenario.

3. Threading to handle lag in the real-time stream:
A common problem faced by image processing devices is a noticeable lag or delay in the
real-time stream. If your system is not capable of simultaneously processing and outputting
the result, you might see a delay in the stream. This is where threading comes into action.
Threading removes OpenCV's internal buffer (which basically stores the new frames yet to
be processed until your system processes the old frames) and thus reduces the lag/increases
fps. It is most suitable for a solid performance on complex real-time applications.

4. Scheduler and Timer:
Another feature of our project is to automatically schedule when to start and run the
software. The user can configure it to run at the desired regular intervals as per his/her need,
be it at any time of the day, or daily from Monday to Friday. The user can also enable a timer
to run the software for a specific time, say 5 hours.
This is extremely useful in a business scenario, where shopkeepers are busy running their
businesses and can simply schedule the software once for the whole week and month, by
choosing their desired time intervals (say 9 to 5).

5. Log and analysis:
This logs all data at the end of the day and stores it in the database. After that, the user can
see and analyze the data and understand his/her crowd distribution at different parts of the
day and take necessary measures. This will be a data analysis tool.



