# Toll-Management-System
Object oriented paradigm using C++.
 Toll management system is the most important part of a Highway Project. This is the system that will enable the toll operating agency to efficiently and securely collect toll from the road user. Here, in this project we have enabled these features through programming concept and all these components have been included in our projects in order to manage the data and records. These data and records includes the basic information of bus truck and other vehicles,  how much it will cost for vehicles to carry that particular number of load, also what is the pickup point and destination point for every vehicles. This system allows us to store the data and records of toll fee and payment collected in a single day or a month. We have also included the feature of collecting the fee of both return type vehicles and collected fee for them. In this project we have made the feature as this system will not collect any fee from special category vehicles and categorized them as exempted vehicles whose toll fee won’t be charged.
Methodology:-
     The program is about Toll system of Naubise-Mugling section of Prithvi Highway. There are a lot of vehicle passing by this highway every day. For this, they have to pay tax. This program will keep all the information of all passed/entered vehicles. We have made six category for vehicles of collecting toll amount. The toll amount for categorized vehicles are listed in the table below:-
Category	Vehicle types:-	Single Journey(Rs.)	Return Journey(Rs.)	Monthly Pass(Rs.)
 1	Car/Jeep/Three Wheeler/LMV	50	100	2000
 2	LCV/ Tractor with Triller/LGV or Mini Bus	100	200	2500
 3	Bus/Truck/Road Roller(Two Axles)	150	300	6500
4	Three Axles Commercial Vehicle	200	400	7000
5	MAV(Four to Six Axles)	300	500	10,000
6	Oversized vehicle(Seven or more axles)	500	800	12,000
7	Exempted vehicles	No toll fee
   Our project also has a new feature of “START NEW DAY” which allows is to clear all the previous records and store new record in the starting new day. This feature allows us to store data for one day and if the new user is recruited in a single day then they can store the data for toll collected fee for that particular day only. Also, in our next category we have “ADD NEW VEHICLES” that allows us to add new vehicles collect  their respective toll fee from fee category in Tollbooth and we can add that vehicles fee in our record file. Also we have the category called “CLEAR RECORDS” which helps us to clear all the previous records and we can use this feature in the starting of new fiscal year. We also have the feature of “PRINT RECORD” that helps the user to print their toll amount and category of vehicles fee in hard copy and so user can feel trustworthy and have proof of paying toll fee. We have also made a functions that shows the list of vehicles whose toll amount is not charged and are kept in category called “EXEMPTED VEHICLES”. Finally, the user can switch between the menus and can return to options called main menu or can exit as per the user choice.
The class we have used are fare_details who function is to provide the toll fee amount for categorized vehicles and another class called toolbooth is used which we have inherited from fare_details which function is to count the total number of vehicles, total fee collected in a single day or in a month, to categorize the type of vehicles and also to choose which category of vehicles charges what amount of toll fee. These are the main functions of the two classes we have used.






The programming methods we’ve used can as summarized below:
●	 Analyzing the concept that can be used to develop proper program.
●	 Discussion on the topic that might be faced onwards.
●	 Making the project schedule.
●	 Initial coding for creating logic.
●	 Coding the program.
●	 Execution and testing the program.
●	 Debugging.
●	 Program Documentation.

Implementation:-
 In the beginning, the output screen of “TOLL MANAGEMENT SYSTEM” is displayed in console showing our project team name and the menu that is shown in the screen are listed below:-
1.	Fare Details: - This class allows us to see the category of vehicles with their toll amount.
a.)	Category 1:- This section consists of Car/Jeep/Three Wheeler/LMV with their toll amount.
b.)	Category 2:- This section consists of LCV/ Tractor with Triller/LGV or Mini Bus with their toll amount.
c.)	Category 3:- This section consists of Bus/Truck/Road Roller (Two Axles) with their toll amount.
d.)	Category 4:- This section consists of Three Axles Commercial Vehicle with their toll amount.
e.)	Category 5:- This section consists of MAV (Four to Six Axles) with their toll amount.
f.)	Category 6:- This section consists of oversized vehicle (Seven or more axles) with their toll amount.
2.	Start New Day: - This to clear all the previous records and store new record in the starting new day. This feature allows us to store data for one day and if the new user is recruited in a single day then they can store the data for toll collected fee for that particular day only.
3.	Add New Vehicles:  It allows us to add new vehicles collect their respective toll fee from fee category in Tollbooth and we can add that vehicles fee in our record file.
4.	Clear Record: - It helps us to clear all the previous records and we can use this feature in the starting of new fiscal year.
5.	Print Record: - It helps the user to print their toll amount and category of vehicles fee in hard copy and so user can feel trustworthy and have proof of paying toll fee.
6.	Exempted Vehicles: - We have also made a functions that shows the list of vehicles whose toll amount is not charged and are kept in category called “EXEMPTED VEHICLES”.
7.	Exit: - This allow the user to exit from main menu.
8.	Switch between the menus:- It helps the user to return to main menus and  can choose the above category options.

Block Diagram:-
  











