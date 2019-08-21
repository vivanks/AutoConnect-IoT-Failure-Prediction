# AutoConnect-IoT-Failure-Prediction

## Note to readers
The version of the project showcased here is an abstract version of the real product but highlights the origin and thought process of the product.

<b> IPR 
This project has been presented at multiple platforms and has been endorsed by various govenment and private estblishments like IET On Campus - VIT and VIT-TBI (Department of Science and Technology, Govt. of India). The product is protected by IPR laws.
The purpose of this repository is to help readers gain technical insights over various domains of technology that intersected here and NOT to be considered as free for development at personal level.
</b>

## Problems Considered:
Most cases of automobile failures are due to negligence of the owner about their vehicle. In most cases, the owner is unaware of the fault diagnostic methods or finds it to be a tedious task. It's only when a mechanic checks the vehicle, that the issues at brought to knowledge of service stations.

Service stations generally  don't have the knowledge of conditions of the vehicles near them.

Clearly, there is a gap of information sharing between the two since it's not possible for the technicians to inspect each and every vehicle everyday to ensure optimum health. To cover this, service stations generally contact customers at random which has proved to be inconvenient for the customers.

## Proposed Solution:
All the systems should be embedded with sensors such that all crucial data of systems of automobile  is being uploaded to a database on cloud which is accessible by the owner and service centre. This would enable the service centre to analyse which vehicles need repairs and schedule appointments accordingly. 

Once the schedule is made, procurements can be planned accordingly, ensuring much lesser wastage. 

A mobile app with integrated chatbot facility will be with all customers to view all data of the vehicle's systems, review health and see the health metric of their vehicle. Immediate alerts and scheduled appointments for service stations should also be made available in the app. 

The data obtained through this whole system can be further analysed to see if there is any defect in manufacturing from the company's side. 

## Goals:
### Sensors for different systems of automobile: 
Since most owners are unable to check crucial parameters of systems, sensors need to be integrated with the systems such that the data can be obtained on a common platform/cloud.

### Common Database for Service stations and Users: 
Parameters of different vehicles across the city/registered with the service centre will be accessible by the service centre. In order to eliminate risks associated with Cyber Security, Firebase will be used to store data on cloud.

### Fault Detection Algorithm: 
Algorithms need to be made to identify if any system of a certain vehicle is faulty and how faulty it is. Accordingly, the prescribed time of getting repairs/updates will be updated on the database.

### Appointment Scheduling Algorithm: 
Once the data of prescribed time for repair is now on the common Database, a schedule needs to be made, giving high priority to urgent cases and carefully making appointments for different vehicles with major to minor defects/need of repairs. This helps in giving the service station idea of whom to contact and how to plan procurements for the upcoming week.

### Mobile application for user: 
Data of crucial parameters of different components of systems in the vehicle will be viewed by user after logging in. This will give 'profile’ of the automobile, similar to Facebook profile, showing all parameters, displaying a health metric and setting up and alerting the customers to  attend scheduled appointments. Option to book a technician or schedule a pick-up or schedule appointments manually will be available. In case of serious faults, red alerts will also be displayed.
