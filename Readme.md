# Vacation Tracking System
### The Vacation Sysytem Idea is presented in the [Object Oriented Analysis And Design textbook, 3rd edition]

## Index
- [System Features](#system-features)
- [List of Actors](#Actors)
- [Use Cases](#use-cases)
- [Database Design](#database-design-for-the-system)
- [Manage Time Use Case Details](#manage-time-use-case)
   - [Request State Diagram](#request-state-diagram)
   - [Manage Time Flow Diagram](#Manage-Time-flow-diagram)
   - [Manage Time Sequence Diagram](#Manage-Time-sequence-diagram)
   - [Manage Time Pseudo Code](#Manage-Time-psuedo-code)
- [Cancel Request Use Case Details](#Cancel-request-use-case)
   - [Cancel Request Flow Diagram](#Cancel-request-flow-diagram)
   - [Cancel Request Sequence Diagram](#Cancel-request-sequence-diagram)
- [Edit Request Use Case Details](#Edit-request-use-case)
   - [Edit Request Flow Diagram](#Edit-request-flow-diagram)
   - [Edit Request Sequence Diagram](#Edit-request-sequence-diagram)


# System features
**Vision:**
A Vacation Tracking System (VTS) will provide individual employees with the
capability to manage their own vacation time, sick leave, and personal time off,
without having to be an expert in company policy or the local facility’s leave
policies



**Functional:**
- use internal User Authentication 
- Display available vacation days
- Display calendar for 6 month before and 18 month after 
- Display all past requests and its status
- manager approval
- email notification 
- enable overrides by HR and system admin with logging



**Non Functional:**
- ease of use 
- record all activity logs
- performance 


**Constraints:**
- The system must use existing hardware and middleware. 
- Interface with HR department legacy systems for employee information and changes.
- Provide a web service interface for other internal systems to query vacation request summaries.

# List of Actors
- Employee
- Manager 
- HR Clerk 
- System Admin

# Use Cases
-  Manage Time
   - Create Request
   - Cancel Request
   - Edit Request (Edit or Withdraw)
         
  
  
## Database Design
![image](https://github.com/AboubakrNasef/Vacation-Tracking-System/assets/105270767/c5c256e7-0701-485a-a632-9a50538d4d2c)


# Manage Time Use Case Details
  ## Request State Diagram
  ![image](https://github.com/AboubakrNasef/Vacation-Tracking-System/assets/105270767/fa1bfdc6-c286-44d7-8140-00b809bb0ca2)

  ## Manage Time Flow Diagram
![image](https://github.com/AboubakrNasef/Vacation-Tracking-System/assets/105270767/0c93e123-eca1-487b-9381-995c45b9d4ba)


   ## Manage Time Sequence Diagram 
![image](https://github.com/AboubakrNasef/Vacation-Tracking-System/assets/105270767/53f8a727-d608-4ed2-8013-54e2cd7dea16)

   ## Manage Time Pseudo Code
![image](https://github.com/AboubakrNasef/Vacation-Tracking-System/assets/105270767/77a59158-e26a-45f1-b901-2351edb20288)

![image](https://github.com/AboubakrNasef/Vacation-Tracking-System/assets/105270767/fd50016d-2a6c-4d1c-9840-ca6b7795e4e2)



# Cancel Request Use Case Details

  ## Cancel Request Flow Diagram
  ![image](https://github.com/AboubakrNasef/Vacation-Tracking-System/assets/105270767/e403260d-4554-44da-bd13-28c73def018c)
  ## Cancel Request Sequence Diagram
  ![image](https://github.com/AboubakrNasef/Vacation-Tracking-System/assets/105270767/efc0299e-794e-4fea-9f8d-ec8880a2e7f7)

# Edit Request Use Case Details
  ## Edit Request Flow Diagram
  ![image](https://github.com/AboubakrNasef/Vacation-Tracking-System/assets/105270767/1634511f-d61b-4842-bbec-c99fca196748)

 ## Edit Request Sequence Diagram
 ![image](https://github.com/AboubakrNasef/Vacation-Tracking-System/assets/105270767/123a698a-433c-4f95-becc-dfcee66406da)

