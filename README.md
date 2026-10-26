# CS 255 System Analysis and Design Portfolio 8-2 Journal

## DriverPass Project Summary

DriverPass was a client that wanted to improve how students prepare for their driving tests. The company needed a web-based system that would give customers access to online practice exams, training packages, and behind-the-wheel lessons. The system also needed to support the employees running the business, including the secretary, driving instructors, owner, and IT officer. My design covered customer registration, package selection, lesson scheduling, practice test results, driver notes, reports, account security, and updates from the DMV.

## What I Did Well

I believe one of the strongest parts of my work was turning the DriverPass interview into specific system requirements. Instead of only listing broad features, I identified who would use each feature, what information they would need, and how the system should respond. For example, scheduling a lesson requires the system to check both the assigned driver and vehicle for the full two-hour appointment. The secretary also needs to perform the same scheduling tasks for customers who call or visit the office.

I also did well connecting the requirements to the UML diagrams. The use case diagrams show what each person can do, while the activity and sequence diagrams explain how important processes move from beginning to end. The class diagram then shows how the information behind those processes is organized. Because the complete system involved several users and functions, I divided some of the larger diagrams into focused views. This kept the connector lines readable without removing important relationships.

## What I Would Revise

If I could revise one part of the project, I would continue improving the connectors and relationship labels in the use case and class diagrams. The number of users, actions, and classes made the diagrams crowded when too much information appeared in one view. I would plan the layout earlier, keep related items closer together, and use a more consistent direction for the connector lines. I would also perform another review of the class relationships and use case connections to confirm that each one communicates its purpose without requiring the reader to trace lines across the entire diagram.

## Interpreting the User’s Needs

I interpreted the users’ needs by treating the DriverPass interview as the main source of requirements. I separated the interview into users, actions, information, business rules, and limitations. That approach helped me catch details that could easily be missed, such as customers needing to change or cancel appointments, drivers recording lesson notes, the owner disabling packages, and the IT officer managing employee access. I also accounted for the company’s ten drivers and ten vehicles, the need for an internet connection when changing live information, and the option to download reports for offline review.

Considering the user’s needs is important because a system can work technically and still fail the people expected to use it. If the scheduling process does not match how DriverPass handles appointments, or if employees receive the wrong level of access, the system creates more problems than it solves. Understanding each user’s responsibilities helped me design the system around the way DriverPass actually operates.

## My Approach to Software Design

My approach is to understand the problem and the people involved before deciding how the system should be built. I start by identifying the users, what each user needs to accomplish, what information the system must store, and which rules control those actions. I then use process models to examine how work moves from one step to another and object models to organize the information and relationships behind those processes.

In future projects, I would continue using use case, activity, sequence, and class diagrams together because each one exposes a different part of the design. I would also use short user scenarios to test the diagrams, including situations where information is missing, a resource is unavailable, or someone attempts an action outside their role. Reviewing the design against realistic situations makes it easier to find gaps before development begins. This project showed me that good system design comes from asking detailed questions early instead of leaving developers or users to figure out the missing pieces later.
