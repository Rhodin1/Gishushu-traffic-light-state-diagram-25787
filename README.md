# Gishushu Traffic Light State Diagram
### Overview:
In this enhanced state diagram, we have four primary directions (north, south, east, west) and four diagonal directions (northeast, northwest, southeast, southwest). Each direction has vehicle lights (red, yellow, green) and pedestrian crossing signals.
### Operating Rules:
#### Traffic Light Control:
i. only one direction(either a main or a diagonal) is green at any moment.
ii. Each green phase includes a yellow phase to alert drivers to prepare to stop.
iii. An all red phase occurs briefly between each green light phase to clear the intersection.
#### Pedestrian Light Control:
i. Pedestrian crossings are allowed only when perpendicular vehicular traffic is red.
ii. Each pedestrian crossing follows a similar pattern, aligning with traffic light changes.
### Traffic light Sequence:
#### North-South Green Phase:
i. Vehicles travel north-south.
ii. Pedestrians cross east-west.
#### North-South Yellow Phase:
i. North-south traffic prepares to stop.
ii. Pedestrians prepare to stop.
#### East-west Green phase:
i. Vehicles tyravel east-west.
ii. Pedestrians cross north-south.
#### East-west Yellow phase:
i. East-west traffic prepare to stop.
ii. Pedestrians prepare to stop.
#### Northeast-Southwest Green Phase:
i. Vehicles travel northeast-southwest.
ii. Pedestrians cross northeast-southwest.
#### Northeast-Southwest Yellow Phase:
i. Northeast-southwest traffic prepares to stop.
ii. Pedestrians prepare to stop.
#### Northwest-Southeast Green Phase:
i. Northwest-southeast vehicles proceed.
ii. Pedestrians cross northeast-southwest.
#### Northwest-Southeast Yellow Phase:
i. Northwest-southeast traffic prepares to stop.
ii. Pedestrians prepare to stop.
#### All Red Phase:
Final all-red phase before the cycle restarts.
### Exception:
When anyone in charger to manage and control the traffic he/she is the priority over all the traffic light. 
