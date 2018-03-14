
**Driver Risk Assessment and Monitoring**

The total number of automobile accidents and fatalities has been on the increase in most States. If a person has had many accidents in the past, car insurance companies and transformation network companies (like Uber, Lyft etc.,) logically assume that the person is likely to have more accidents in the future. 
- The project aims to look at certain other data points along with the driving history and identify the risky and cautious drivers. 
- It also facilitates monitoring the driving behavior and provide key signs of unsafe and aggressive driving practices.

Our solution aims to look at the below data points and identify the risky and cautious auto drivers

- DMV “points”: The point system used by DMV to monitor the driving habits of all licensed drivers.
- VIN (Vehicle Identification Number): VINs summarize information about the vehicle.
- Credit Score: Good credit indicates that one is responsible and pay bills on time.
- Location: City dwellers pay more for insurance because there are more people in cities, raising the likelihood of accidents.
- Age: Drivers under 25 years old and those over 65 years old are statistically more likely to be involved in accidents.
- Gender: As per stats men drive more miles on an average than their female counterparts, automatically raising the likelihood of collision.
-  Marital Status: Married people are known  to abide by the traffic rules and relatively safe than than the unmarried people.
- Driving experience: The more the experience, the safer the driver is considered.
- Annual mileage: More annual mileage, means more likelihood of being involved in accidents.

**User Stories**
================
- As an Insurance Company Personnel, I can assess the Risk category of the driver and also decide on the insurance premium to be charged based on this. I can also monitor his driving pattern on regular intervals. If proven safe and trustworthy, the insurance premium can be reduced.

- As a Cab Service company Associate, I can check the past driving history of the driver before employing him and also monitor him regularly to assess his driving behavior. I can also check his driving mannerism in case of any complaint or concerns raised by my customers.

- As an individual, I can also check my driving score, before applying to companies like Uber.

**Architecture Diagram**
=======================
1) <b>System architecture for Risk analysis implememtation </b>

<p align="center">
<img src ="/Artifacts/systemarchitecture.jpg?raw=true"/>
</p>

2) <b>Driver behavior monitor architecture: </b>
<p align="center">
<img src ="/Artifacts/DriverMonitor.jpg?raw=true"/>
</p>

<b>Node-RED workflow for driver behavior monitoring:</b>
<div> <span>
<img src ="/Artifacts/NodeRedFlow2.jpg?raw=true"/>
<img src ="/Artifacts/NodeRedFlow1.jpg?raw=true"/>
</span></div>
</br>

<b>Map UI displaying vehicle trace and driving behavior segments:</b>
<P align = "center">
<img src ="/Artifacts/Map2.jpg?raw=true"/>
</P>


**Working Model on AWS**

http://ec2-54-149-92-43.us-west-2.compute.amazonaws.com/

**Team 19**

> [Poojitha Amin](https://github.com/poojithaamin)

> [Sneha Vadakkemadathil](https://github.com/SnehaVM)

> [Shivam Kumar Gupta](https://github.com/shivamgupta01)

> [Rovin Singh Patwal](https://github.com/Rovin284)




