1. PEAS framework 

Performance measure - Reach Kisumu from Nairobi using the shortest total road distance, while maintaining safety, obeying traffic rules, avoiding collisions and minimizing fuel consumption. 

Environment - Kenya's highway network, including roads, towns and cities in Nairobi, Central Highlands, Rift Valley and Lake Victoria Basin, together with other vehicles, pedestrians, road conditions and traffic. 

Actuators - Steering, accelerator, brakes, gear control, indicators and other vehicle controls used to follow the selected route safely. 

Sensors - GPS, cameras, radar, wheel-speed sensors and navigation/ traffic data used to determine the trailer's location and detect road conditions and obstacles. 

 

Environment properties 

Partially observable. The trailer can use GPS and sensors to observe its surroundings, but cannot know every hidden hazard or future traffic event. 

Stochastic. Traffic, weather, road incidents and the actions of other road users make outcomes uncertain. 

Sequential. Each driving action affects the trailer's location and the options available for subsequent actions. 

Dynamic. Traffic, pedestrians, road conditions and obstacles can change while the trailer is travelling. 

Continuous. Speed, position and steering angle are continuous. The route level problem can be abstracted as discrete. 

 

 
 

2. Directed Graph 

![Directed Graph](Graph.png)

Distance in Kms 

Drawn on canva 

 
![Search tree ](Searchtree.png)
Used canva 

 

3. 

Nairobi – Thika – Nyeri – Meru  = 294.3 kms (goal not reached) 

Nairobi – Naivasha – Nakuru – Kericho – Kisumu =354.2 kms ( Most optimum) 

Nairobi – Naivasha – Nakuru – Eldoret – Kakamega – Kisumu = 478.6 kms 

Minutes of meeting
Date:16 October 2026
Assignment: Design of Searching Agents
Members: Mikebrian, Cynthia, and Peter
Meeting type:Online group discussion for the assignment.

Agenda

Review the assignment questions and submission requirements.

Discuss the design of the agents.

Divide the work among members.

Agreement on who will submit the work .

2.Division of Work

Mikebrian

Handled the search tree representation.

compiled and edited the final markdown document and submitted the work.

Cynthia

Worked on the directed graph .

Peter

Worked on the path cost funtion.

Worked on the PEAS framework design.

3. Discussion and Decisions

The group reviewed the requirements for the assignment and agreed to split the work up between the three members. Each member was responsible for his/her own part as well as the overall completeness of the task.

They agreed to combine all of the individual contributions into a single Markdown document, which they called design.md, and store it in a GitHub repository called PS-Agents.

4. Conclusions

The meeting ended with agreement on the division of work, preparation of the final assignment document, and the GitHub submission requirements.

   
