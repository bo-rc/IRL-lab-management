# Table of Contents
* [Introduction to IRL](https://github.com/bo-rc/IRL-lab-management/blob/master/lab-manual.md#introduction-to-irl)
  * [Missions](https://github.com/bo-rc/IRL-lab-management/blob/master/lab-manual.md#missions)
  * [Organization](https://github.com/bo-rc/IRL-lab-management/blob/master/lab-manual.md#organization)
  * [Acknowledge IRL](https://github.com/bo-rc/IRL-lab-management/blob/master/lab-manual.md#acknowledge-irl)
* [Use the Lab](https://github.com/bo-rc/IRL-lab-management/blob/master/lab-manual.md#use-the-lab)
  * [Becoming a User](https://github.com/bo-rc/IRL-lab-management/blob/master/lab-manual.md#becoming-a-user)
  * [Completing Lab Training](https://github.com/bo-rc/IRL-lab-management/blob/master/lab-manual.md#completing-lab-training)
  * [Making Reservations](https://github.com/bo-rc/IRL-lab-management/blob/master/lab-manual.md#making-reservations-to-use-the-lab)
* [Lab Rules](https://github.com/bo-rc/IRL-lab-management/blob/master/lab-manual.md#lab-rules)
  * [Using IRL space](https://github.com/bo-rc/IRL-lab-management/blob/master/lab-manual.md#using-irl-space)
    * [Desk Area](https://github.com/bo-rc/IRL-lab-management/blob/master/lab-manual.md#desk-area)
    * [Bench Room](https://github.com/bo-rc/IRL-lab-management/blob/master/lab-manual.md#bench-room)
    * [Flying Arena](https://github.com/bo-rc/IRL-lab-management/blob/master/lab-manual.md#flying-arena)
  * [Safety Rules](https://github.com/bo-rc/IRL-lab-management/blob/master/lab-manual.md#safety-rules)
* [Lab Manager Office Hours](https://github.com/bo-rc/IRL-lab-management/blob/master/lab-manual.md#lab-manager-office-hours)
* [Usage Rates](https://github.com/bo-rc/IRL-lab-management/blob/master/lab-manual.md#usage-rates)
* [Vedio Tutorials](https://github.com/bo-rc/IRL-lab-management/blob/master/lab-manual.md#video-tutorials-in-development)
* [Lab Training program](https://github.com/bo-rc/IRL-lab-management/blob/master/lab-manual.md#lab-training-program-in-development)
* [Recommendations](https://github.com/bo-rc/IRL-lab-management/blob/master/lab-manual.md#recommendations)

# Introduction to IRL
The University of Illinois Intelligent Robotics Laboratory (IRL), officially established in 2015, is an initiative of the Coordinated Science Laboratory (CSL). IRL is a shared research facility which brings together world-class faculties and students to solve ambitious and challenging problems in mobile robotics. IRL is also a highly collaborative laboratory to unite research groups of various expertise across the campus to expand the frontier of robotics applications. IRL is pleased to recognize the many units of campus that embrace the notion of a shared facility designed to provide greater capabilities at lower costs for all interested faculty and who are helping fund its operations. These include:

*	College of Engineering
*	Coordinated Science Laboratory
*	Aerospace Engineering
*	Computer Science
*	Electrical and Computer Engineering
*	Mechanical Science and Engineering

The faculty associated with IRL span an even greater set of units reflecting the breadth and depth of expertise that can be drawn from by partnering with IRL. These include:

*	College of Engineering
*	College of Agricultural, Consumer and Environmental Sciences
*	Coordinated Science Laboratory
*	Aerospace Engineering
*	Civil and Environmental Engineering
*	Computer Science
*	Electrical and Computer Engineering
*	Industrial and Enterprise Systems Engineering
*	Mechanical Science and Engineering
*	Physics

IRL currently hosts an indoor drone arena, a 33x30x13 feet<sup>3</sup> (10x9x4 m<sup>3</sup>) motion-capture volume with safety nets and a cushion floor. The motion capture volume is covered by 8 Vicon T40 motion capture cameras capable of running at 370 frame per second with full frame resolution. Real-time positioning data of marker objects, captured by the Vicon motion capture system, can be streamed via local network or internet to devices interfaced with Vicon DataStream SDK. Currently the SDK supports C++ and Matlab programming. Vicon data can be also interfaced to ROS using [vicon_bridge](https://github.com/bo-rc/vicon_bridge). Example usages can be found at [IRL's GitHub](https://github.com/bo-rc/IRL/tree/master/src/Vicon).

<img src="https://cloud.githubusercontent.com/assets/14265605/16573855/2218e946-423e-11e6-9c99-0a1466258ad2.JPG" width="1000">

The research activities at IRL are supported by NASA, the Office of Naval Research, the Department of Defense, the National Science Foundation and other federal agencies, and the University of Illinois. IRL is pleased to welcome any research group that are interested in using or contributing to IRL's facility services to join the lab.  The purpose of this manual is to present lab guide and user policies in a transparent manner with emphasis on safety, fairness and collegiality. 

## Missions
IRL's missions are:
* provide facilities and expertise for users to conduct research in mobile robotics
* facilitate fast-prototyping of mobile robotics research platforms
* develop software solutions for Vicon motion capture users
* train students about remote piloting, safety procedures and skills to perform robotics-related experiments.

## Organization
*	Lab Director: Dr. Naira Hovakimyan (nhovakim@illinois.edu); 
*	Lab Associate Director: Dr. Timothy W. Bretl (tbretl@illinois.edu)
*	Lab Coordinator/Manager/Engineer: Dr. Bo Liu (boliu1@illinois.edu)

Information about IRL can be found on [IRL's website](http://robotics.illinois.edu).

## Acknowledge IRL
The following acknowledgement __must__ be included in all publications that incorporate any results obtained through the IRL facilities: 
> "... was carried out in part in the Intelligent Robotics Laboratory, University of Illinois." 

Please also send the publication information (citation, DOI, or conference name and paper/poster title) to the lab manager. 

The staff of the IRL may make major contributions to the research carried out by our users. The staff can have an important scientific role through the planning and realization of experiments, through the analysis and interpretation of data, or through a full collaboration in the research. When this occurs, the staff person should be included as a co-author on papers.

# Use the Lab

The preferred mode of operation at IRL is self-use after completing the necessary training. Staff-assisted use may be permitted before the user can complete the training. Perspective users may schedule a tour with the lab manager during [office hours](https://github.com/bo-rc/IRL-lab-management/blob/master/lab-manual.md#lab-manager-office-hours). After a brief process to become a formal user (see below) and completion of lab training, you can apply to get i-card access to the lab and reserve time for use of the lab facilities. Lab users can make lab reservations [online](http://robotics.illinois.edu/reserve-lab).

## Becoming a User
Perspective users should submit a short application (see requirements below) [online](http://robotics.illinois.edu/become-a-user/). Every effort will be made to ensure decisions about the application will be sent back to the applicant and the applicant’s supervisor within 2 business days. When approved, a project number will be provided for use when making a facility use reservation. The purpose of the application is for IRL staff to help evaluate the experiment design, discuss with the user about improvements on the design in view of IRL's resources and expertise, and finally document facility usage. In general, any mobile robotics-related project or Vicon users are encouraged to use the IRL facility.

The applicant need to prepare the following information using the online [application form](http://robotics.illinois.edu/become-a-user):
*	Title of the project
*	PI, co-PI and collaborators
*	Citizenship status 
*	The employer (if not UofI)
*	Principal point of contact (normally the primary user of the facility) and contact information (email; cell phone, work phone, etc.)
*	Status of all likely users with respect to completion of safety training including whether safety training and/or testing has been requested
*	Project funding information
*	Students and researchers assigned in this projects
*	An approximately 200 words project description
*	Configuration needs for the IRL if deviating from the standard
*	What facilities/tools/services do you expect from IRL
*	What time is expected to be requested: hours per week, number of weeks
*	Nature of hours per week: minimum block of time, daytime, evening time, night time
*	Special safety requests or exceptions based on nature of the experiment

## Completing lab training
This manual contains [training tutorials]() for new users. The lab staff holds training office hours to train new users. Office hours reserved for training will cover the following topics:
*	The Vicon motion capture system
*	The tool bench
*	Piloting mobile robots
*	Lab rules and safety measures

You may schedule a one-hour training session in [office hours] by sending an email to the lab manager. To complete the training, a perspective IRL user must pass a lab-safety quiz, demonstrate Vicon operational competency (if applicable) and a flight test if the project involves flying drones at IRL.  Completion of these elements will be recognized through the assignment of a user facilities permission status.  This will need to be included in reservation requests. 

To comply with our safety rules and insurance requirements, we recommend that no user use the lab alone. Before a user has completed lab training, such users can use the facility only when IRL staff are on-site and when they have notified the IRL staff of their intent to use the facility.  Failure to follow these rules and other rules related to IRL use could result in suspension of user privileges.  Please consider your colleagues in this manner: investigations of incidents and violations could result in closure of the facility for all users.

## Making reservations to use the lab
After completing the lab training, users can schedule time and self-use the facility as long as all lab rules are followed.  Please use the web-based [reservation form](http://robotics.illinois.edu/reserve-lab/). Please also include set-up time and reconfiguration time if you need to reconfigure the laboratory in a configuration that differs from standard.  The standard set-up is for UAS flights with foam dispersed evenly across the floor and netting fully deployed.  You will be expected to remove such foam when you require it and replace it at the end of your measurements.  Addition of large fans for gust simulation are another example of deviations from the standard configuration.

Currently, a [lab schedule](http://robotics.illinois.edu/lab-schedule/) is maintained on the [IRL's website](http://robotics.illinois.edu/reserve-lab/). Please find an open time slot and submit the reservation request form online. After the appointment is approved, the requested time will appear on the [lab schedule](http://robotics.illinois.edu/lab-schedule). 

# Lab rules

<img src="https://cloud.githubusercontent.com/assets/14265605/16720242/a8fe97a2-46f9-11e6-85f8-f11462dcc66a.png" width="1000">

## Using IRL space
Researchers who are part of an active project approved by IRL can use IRL facilities. IRL is located inside the CSL studio (1206 W. Clark, Urbana IL). As shown in the picture above, IRL users may use the Desk area, the Bench room and the Flying arena as well as the Storage room. The i-card access to the Bench room and the Flying arena can be obtained after completion of lab training.

It is worth stating again that IRL is a shared facility. As such IRL has strived to develop use policies that are fair to all.  We also emphasize the importance for these facilities to be used safely and maintained in good operational order for all users and their respective colleagues. 

### Desk area
IRL includes twelve CSL studio desks numbered from 53 to 64. IRL explicitly labels those desks with labels from D1 to D12. Cubic desks at the desk area are used as hoteling seats, which may be reserved by users. Desk D9 and D10 are reserved for IRL daily users who have appointments shown on the online schedule. Frequent users of IRL may apply through the IRL staff to use the space for a long period provided the following rules are followed:
*	The user must have an active project at IRL approved by the IRL staff.
*	The longest use time that can be requested at one time is two months.
*	Renewal is possible and must be approved by the IRL staff.
  *	IRL staff may turn down the renewal for reasons including but not limited to the following: the space is not used more than 50% of the requested time, project priority, high demand of the Desk area from other users currently in the waiting list.
*	All lab rules are followed by the user.  Failure to follow lab rules may result in consequences up to and including immediate termination of rights to use desk space.
*	Failure to pay an applicable “hoteling fee” if such a fee is applicable
*	Failure to maintain and clean spaces after use may result in cleaning charges imposed to the user and user’s supervisor.
Daily users may use D9 and D10 which are not allocated to long-time users. Desks D9 and D10 must be cleaned daily.
If all cubic desks are filled and a user want to have a desk for a long period, the user can email the lab manager who keeps a waiting list for requests of cubic desks. The user on the top of the waiting list will be served first when a desk is available. The IRL staff reserve the right to terminate the use of the Desk area and other lab facilities at any time.

IRL users can use the cubic desks at the Desk area for their office need. The cubic desk should not be used as a working bench to build or repair robots. The cubic desks are meant for users to read papers, web-browsing for the purpose of the experiment etc. Please do not use the cubic desks as a working bench. However, the users can connect their computers to their robots for data downloading and other analysis provided that:
*	the robot is not powered by the main battery and any moving part of the robot is secured or removed.
*	any drone that weighs more than 250g must not carry propellers in the Desk area.
*	any loud buzzer on the vehicle is disabled.

### Bench room
The Bench room is used a staging area for flight tests in the Flying arena and as an innovation center to build robotic platforms. IRL provides common tools for building and maintaining robots, as shown in the picture below. IRL users may recommend new tools for IRL to purchase. Please send your wish list to the IRL lab manager and include a brief explanation why IRL should have the tools you are recommending and how such tools might benefit other user, if applicable. The IRL staff will work their best to serve your research needs although budgetary considerations may limit IRL’s ability to acquire such tools promptly.  

Specialized tools of use to a particular experiment or use can be brought by the user to IRL.  The user should notify the Lab Coordinator/Manager and if reasonable, the lab manager will provide storage space for such equipment while the related project is completed. 

<img src="https://cloud.githubusercontent.com/assets/14265605/17108845/e17ccf1a-525a-11e6-8c75-0357b67c082e.JPG" width="600">

All eleven benches are labeled by IRL from B1 to B11. B3 and B5 are IRL's dedicated working bench area and are reserved for IRL daily users who have appointments on the online [schedule](http://robotics.illinois.edu/lab-schedule/). Users may apply to use other working benches for a long term following rules:
*	The user must have an active project at IRL approved by the IRL staff.
*	Any project material/equipment brought in and out of IRL must be reported on the log book at the entrance of room 1257.
*	Hazardous material should not be stored in the Bench room.
*	No more than two benches can be used by a single group if no more benches are available and there are demands from other groups.
*	The longest time span that can be reserved at one time is one month.
*	Renewal is possible and must be approved by the IRL staff.
  *	IRL staff may turn down the renewal for reasons including but not limited to the following: the bench is not used more than 50% of the requested time, project priority, high demand of the Bench room from other users currently in the waiting list.
*	All lab rules are followed by the user.

Other rules in the Bench room:
*	Material/equipment brought in and out of the 1207 and 1208 must be reported to the lab manager and logged into a the log book at the entrance of room 1257.  Materials/equipment belonging to IRL must not be removed from 1207 and 1208 unless written permission has been obtained from the Lab Manager.  
*	Do not arm the motors of your multirotors if you have propellers on. i.e. disable the motor if you have propellers on the vehicle. 
*	Do not drill or cut carbon-fiber material indoors: carbon-fiber power is toxic, you must talk to the lab coordinator/manager if your project requires modifying carbon-fiber material.
*	At the end of your experiment day, make sure to:
  *	Clean and tidy your bench.
  *	Restore the tool bench to its original configuration.
  *	Unplug all power plugs.
  *	Store your batteries according to the lab safety rules (See below).
  *	Store any bulky equipment in the storage room 1256.
  *	Shutdown your computers and close the door at 1257.
*	All lab rules are followed by the user.  Failure to follow lab rules may result in consequences up to and including immediate termination of rights to use desk space.

### Flying Arena
Room 1258 hosts the flying arena and Vicon motion capture cameras. The IRL working bench B3 and B5 will be automatically reserved with your reservation of room 1258. Please reserve your time online at least 2 days ahead of your experiment day. Please cancel any reserved time as soon as possible and at least 48 hours in advance if at all possible.  At most two teams can share and alternate the use of the IRL working bench and the flying arena at the same session. If you do not want to share the usage with another team, you can specify it in your online reservation form. Reoccurring schedule is possible, please follow the format of the online reservation form and indicate your re-occurring experiments. A confirmation about your schedule will be sent back to you via email.  Note that users who consistently reserve and cancel time in the facility may find their access limited at the discretion of the lab manager.  

Flying arena rules:
*	Vicon camera calibration will be checked daily at 10:00am. If the calibration wand measurement is off by more than 1%, a new camera calibration will be performed at once. Monthly camera calibration will be performed at 10:00am the first Monday in the month.
*	The Vicon computer must be used for motion-capture related tasks.
*	Any vehicles must be approved by the Lab manager before they can be operated at IRL.
*	Pilots can fly their drones only after passing the flight test of the lab training session.
*	Drones that weigh more than 250g or have larger-than-5-inch propellers must be armed and flown inside the netted area.
*	All vehicles operated at IRL must have a printed preflight checklist, a fail-safe setup and a kill-switch setup that are approved by the IRL lab manager.  Non-flying vehicles (ground autonomous vehicles or equipment, for example) must provide equally safe and preventive check lists.
  *	Preflight check: a check list of states of your robot system before you should arm and operate the robot.
  *	Fail-safe setup: when the vehicle loses connection to the controller, the vehicle should stop moving.
  *	Kill-switch: when the kill-switch is engaged, the vehicle should be disarmed and all moving parts should stop.
*	Drones must not be flown closer than 2m to any Vicon camera.
*	When flying drones that have larger-than-5-inch propellers or are powered by 3S LiPo or more powerful batteries, safety glasses must be worn and safety gloves must be worn when handling the drone. IRL has provided safety glasses and safety gloves at the entrance of the flying arena. Please restore the safety equipment after usage.
*	When flying a vehicle tethered to the ground using a safety cable provided by IRL, no more than 3 people can be inside the netting arena simultaneously. When flying a free vehicle, no one can be inside the netting arena; everyone should be outside the netting arena before the vehicle can take off.
*	No carbon-fiber or metal prop-vehicles can be operated inside IRL.
  *	spinning carbon-fiber or metal propellers are extremely dangerous.
  *	The benefit of using them is minimum inside IRL flying arena.
*	When operating your robots inside IRL, be alert and clear. You should:
  *	stand at least five feet away from vehicle
  *	everyone must be mentally alert
  *	before making any move, communicate with others loud and deliberate
  *	Before arming, the pilot must shout it out: "Arming!"
  *	Before taking off, the pilot must shout it out: "Taking off"
  *	To land the vehicle, the pilot must shout it out: "Landing"
  *	Only after disarming a landed vehicle, the pilot must shout it out: "Disarmed"
  *	Disconnect the main battery to your vehicle as soon as you can after the vehicle is landed.
*	User must use extra caution to recover a crash or when performing a maiden flight/experiment 
*	When retrieving a crashed drone other possibly damaged equipment or autonomous vehicle, safety glasses and safety gloves must be worn and proper shoes and attire must be worn.  If uncertain of the safety of the operation to be undertaken, you must notify the IRL Lab Manager or other senior CSL official and obtain permission before proceeding.
*	All lab rules are followed by the user.  Failure to follow lab rules may result in consequences up to and including immediate termination of rights to use desk space.

## Safety rules
Most of the lab safety rules are already described above in lab rules.  Here additional safety rules are specified and some important safety rules are repeated.

__handling LiPo batteries__:
* Fully charged LiPo batteries must be stored in fire-resistant sacks.
* Always use “1C” to charge your LiPo battery, namely the maximum charging rate you can use is 1 times the battery capacity rating, with the units changed to amps, e.g. if your battery has a capacity rating of 2200mah, you should charge your battery at 2.2 amp.
* Always charge batteries inside the provided fire-resistant container, shown in the picture below: 

<img src="https://cloud.githubusercontent.com/assets/14265605/17108852/ec86e4a4-525a-11e6-991e-c164f22a03fa.JPG" width="600">

*	To dispose old LiPo batteries, properly discharge the battery using the discharge function of the charger, submerge them in salt water for at least a week then you can safely throw them into trash; LiPo batteries are environmentally safe. If you want to dispose a LiPo battery at IRL, talk to the lab manager who will handle the disposal for you.
*	Never use a punctured LiPo battery; if your LiPo battery gets a puncture in a crash for example, go find the lab manager immediately. Never try to charge or discharge a punctured LiPo battery; fire or explosion could occur. The lab manager is the only authorized person to handle a punctured LiPo battery at IRL.
*	When not using the LiPo battery for more than 10 days, please use the storage function of the charger to properly maintain the LiPo battery per-cell voltage at the storage value (~3.8 V).
*	Fire extinguishers are located at the entrance of room 1257 in case of fire, always notify the Lab manager or other Senior CSL staff and contact fire department by calling 911.

__handling flight tests__:
Please refer to the [Flying arena rules](https://github.com/bo-rc/IRL-lab-management/blob/master/lab-manual.md#flying-arena)

__using IRL space__:
*	Flight tests can be performed in the flying arena only.
*	Aerial robots that weigh more than 250g cannot carry propellers with main battery plugged outside of the flying arena room 1258.
*	Hardware building and maintenance should be carried out in the Bench room 1257.
*	Bulky equipment should be put into the Storage room 1256 at the end your experiment day. You can store some bulky equipment in the Storage room 1256 for a long period provided that you have an active project at IRL and the equipment is required in your experiments.
*	Please keep your cubic spaces clean and tidy.
*	You may keep your experiment setup on your working bench overnight provided you disconnect all power cords and properly organized the space such that it is clean and tidy.
*	Batteries not in use must be stored in fire-resistant LiPo sacks. If the batteries won’t be used in more than 10 days, please use the storage function of the charger to properly maintain the LiPo battery per-cell voltage at the storage value (~3.8 V).
*	Please lock all doors if you are the last person leaving the lab.

__Violations to safety rules__: the user who violates IRL's safety rules will be subject to consequences up to and including the suspension of user privileges; such users will also be required to go through IRL lab training again. Before the violator can pass the lab training, the violator cannot use facilities at IRL.  Violations of safety will be reported to the supervisor of the violator, the CSL facilities manager and be recorded in the Lab Manager’s logbook. Damages resulting from violations may be billed and expected to be paid for by the violator and/or the violator’s superior. 

# Lab Manager Office Hours
The lab manager has the following office hours:
*	Vicon motion capture training: 10:00am - 11:00am on Mondays.
*	Multicopter pilot training: 4:00pm - 5:00pm on Mondays.
*	Bench tools and safety training: 10:00am – 11:00am Tuesdays.
*	Project-specific support: 4:00pm – 5:00pm on Tuesdays.
*	General inquires: 10:00am – 11:00pm on Thursdays.
*	Additional hours may be added upon request.

You may want to schedule a time for your training purposes by sending a request via email to the lab manager.

# Usage Rates (In development)
IRL is a shared facility that must recover costs and be able to invest in regular upgrades in order to continue to operate and maintain its ability to permit its users to undertake cutting edge research.  As such, the following rates have been developed and approved by the F&S facilities office for different types of users. 
*	IRL Facilities
  *	For University of Illinois at Urbana-Champaign users
    * Those whose primary appointment is in departments supporting IRL operations
      * First year of access
      * Subsequent years
    * Those whose primary appointment is in departments not supporting IRL operations
    * Those assigning equipment of high benefit to IRL and its user community.  Special arrangement will be considered and negotiated.
  * For industry users
    * These will require the completion and approval of a facilities use agreement
*	IRL Services – IRL may offer services as they are implemented such as calibration services and set-up services for flight experiments in other indoor and outdoor facilities or areas. 
  *	For University of Illinois at Urbana-Champaign users
*	We anticipate usage policies and fees to be reviewed on an annual basis to reflect changes in support and costing.

# Video Tutorials (In development)
A number of general safety tutorials are available on-line. The following are required. Users should complete these and print certificate of completions for inclusion in their user qualification materials.  These are:
* [LiPo battary]() 
* [Radio fail safe settings]()
* [Fire distinguisher]()
* [Safe soldering]()

A number of additional safety or equipment use videos are recommended for viewing if they are applicable to the experiments users are expecting to undertake.  Examples include:
* 

Until IRL specialized video tutorials are completed, users should go to training session with the Lab Manager to complete training requirements.  Topics to be covered are as listed for future tutorial listed below:

## Vicon
* How to do calibration at IRL
* A walk-through of the Tracker 3.2 software interface
* Using Vicon DataStream
  * Introduction to SDK
  * Use SDK in Matlab
  * Use SDK with C++
  * Use ROS with Vicon
  * Broadcast DataStream via WiFi

## Knowledge base
* Radio transmitter and receiver
  * Radio channels and control
* common airframes.
  * fixed-wing
    * Aileron/Elevator/Rudder
    * delta-wing
      * radio mixing
  * collective-pitch helicopters
  * multirotors
    * Classification of Rotors
    * Power-train setup for multirotors
  * flight control and autopilot

## Tools
* Prototyping tools 
* soldering
* LiPo Charger

# Lab Training program (In development)
The lab training program includes the following:
## Introduction to general lab rules
## Pilot training for multirotors
* 2-hour flight time with a multirotor Simulator on computers
* 1-hour instructor-assited flight time using paired radio controllers for new multirotor pilots
* Flight tests for new multirotor pilots: new pilots must be able to perform the following maneuvers with the IRL training quadcopter:
  * Hovering at 4 orientations
  * Bank-turn circling
  * Figure-8 circling
* Finally, pilots who will use their own aerial robotic platforms must demonstrate a flight with their own equipment:
  * Perform the pre-flight check using their own pre-flight checklist.
  * Perform a typical flight in the actual experiment
  * Demonstrate the fail-safe and kill switch settings

## Pilot training for fixed-wings
This will be a collaboration with Champaign County R/C Club. Student pilots will be introduced to the CCRCC flight school. The training is free-of-charge.

# Recommendations 
IRL staff are open to suggestions for improvement of operations and facilitation of usage to the extent possible. Please email such suggestions to the IRL Facility Coordinator/Manager or talk to this individual during office hours or in an ad hoc manner.  If you feel that your comments and suggestions are not being addressed in a reasonable time frame, feel free to contact the IRL Lab Director directly. 
