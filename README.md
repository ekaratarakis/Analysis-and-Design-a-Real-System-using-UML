# Analysis-and-Design-a-Real-System-using-UML
The goal of this project is to analyze and design a whole real software system that can be in use from any local authority service in a city or a town such as the **Municipality** in terms of optimizing the services that the minicipality provides to the people and all the benefits people can receive from their local aythority service, using the UML (Unified Modeling Language). Our analysis and design on this system is focused in the need of the **Technical Service** of the municipality which is responsible for scheduling, studying, building and supervising projects that will be in great benefit to the people and improve radically their every day lives. Additionally, the technical servise is responsible for preserving the public buildings in good condition, keeping the public spaces clean and taking care of all the green fields and areas in the city or town. Thus, this system is developed to be implemented and improve the organizing and managing standards of the technical service.
## Project framework description
At first the technical service is composed of the departments below.
- Department of technical, electromechanical projects and transportations.
- Department of urban planning, environment and civil protection.
- Department of cleaning, recycling and preserving green.  

The software system we have designed performs the below functionalities and has the following features.
- An introductional and welcoming front page with information and able to accept registration data from the citizens and the members of the technical service.
- An electronic database where will be stored all the data from the registration as well as information about the technical service (e.g. human resourses, machinery etc).
- Capability of communication between citizens and municipality as well as of communication between employees and the city counsil.
- Faster execution and maintainance of projects.
- Optimization and management of financial resourses and raw materials.
- Minimizing bureaucracy.
- Better insurance and protection of the municipality's files.
## System Requirements Analysis
- **Functional Requirements :** The functional requirements are specifically important as they define the functionality of the system. During the phase of design several meatings with the people in charge in the municipality took place in order to define which are the exact desired functionalities of the system. So we came up with the following plan.
  - Guest : A guest can have access to all general information and data which are not require further access to the system (lon in).
  - Low level user : A low level user can be a citizen or an emplyee and can have access in specific fucntionalities according to his status. For citizens,
    - They have the right of resister (sign up) or delete which must be accepted by the administrator.
    - They can log in to the system only with registration data.
    - They have only one account per citizen.
    - They can send requests of a technical nature.
    - They can send requests of complaining if the above requests are not satisfied.
    - They can watch the status of the requests.
    
    For guests,
    - They can watch the total number of requests that are been received.
    - They can refer the requests to the respective department.
    - They can register the requests in the history file (requests file).
    - They can remove inappropriate or non-relevant messages.
    - They can answer to request whether there is reason to do so.
    - They can update the status of the request so that the citizen can know its path.
  - High level user : A high level user can be either a manager of the Technical Service or the Mayor. They will have the rights to organize better the system, to improve the services and to supervise the procedure. For both the manager and the Mayor,
    - They can send a request to the administrator for database's updating according to the needs of the Technical Service.
    - They can watch the status and the evolution of the requests.
    - They can accept requests with complains.
    - They can have access to low level users rights.
  - Administrator : Well, is the administrator of the system :) For the Administrator,
    - He/She can edit and update the database.
    - He/She can insert or delete user accounts.
    - He/She can upadate the system.
## Non - Functional Requirements
The non - funstional requirements are guarrantee the safety, the information management and flow by optimizing the efficiency of the functional rewuirements. At the same time, they are constrains for out system too. More specifically, the non - functional requirements are,
### Time and Hardware Constrains
- The response time during a log in must not overcome the 4 sec due to the great number of users (thousands of citizens).
- The response time for any other action after log in must not overcome the 3 sec.
- A server with more features is required in order to ensure the smooth operation of the system.
- The computer application must not require more than the existing hardware.
- The system must support the simoultanous connection of 300 users.
- The system must log out automatically every user that has been inactive for the last 5 minutes.
- The system must not allow the sent of messages with more than 100 characters.
- The user must be able to familirize themselves with the system in less than a month.
- The system must function continuously.
### Safety
- The system will be host in the municipality's servers and therefore must be protected from any attacks thanks to the firewall.
- The communication must be encrypted with RSA.
- The system must not allow the sing up of a user with the same name and/or the same e-mail.
- The system must not allow a user to change the password without to confirm the current password.
### Store and Safe
- The system must store the municipality's files an well as the personal data of not more than 2000 users.
- Every user mustn't allocate more than 500 kbytes of memory.
- The system must perform backups in daily bases after the end of the actions.
### Strart Up and Shut Down
- The reboot of the system must not take more than 5 minutes and must be performed only by the server.
- In case of a possible downfall of the server there must be a restore of the data through the backup files.
- The system must not fall more than 2 times per year with a time difference of 5 months.
- In case of a possible downfall the users must see the message "Connection to the server is not available. Please call the Municipality for further information".
## Analysis and Design using UML diagrams
### Use Case Diagrams
To begin with, we present a use case diagram where there are included all kind of use cases as well as all kind of users of the system.

