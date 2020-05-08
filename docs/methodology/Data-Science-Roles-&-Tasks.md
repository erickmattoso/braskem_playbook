[https://github.com/Azure/Microsoft-TDSP/blob/master/Docs/roles-tasks.md]()
##Team Data Science Process: Roles and tasks
This document outlines the key personnel roles and their associated tasks.

------------
**Definition of Four TDSP Roles**

**Group Manager** (Leader of Digital Factory) 
- Is the manager of our entire DS unit. 

**Team Lead** (DS coordinator)
- Is the manager of a team in a DS unit.

**DS Teams** 
- Multiple Data Scientists.

**Project Lead** (Scrum Master)
- Manages the daily activities of individual DS on a specific DS project. 

**Project Individual Contributor**
- Is our team members, compose by: Data Scientists, Data Engineering, Designers, Scrum Masters, etc.

**OBS**: The team lead and Goup Manager can be the same person.

-----------------------
**Definition of the tasks by TDSP Roles**

**Group Manager** 
- Create a **Group Account** on code hosting platform, like GitHub
- Create a **Project Template Repository** on the group account.
- Create a **Utility Repository**, utilities to make the work of DS more efficient.
- Create the **Security Control Policy** of these repositories on our group account.

**Team Lead**
- Create the **Team Project Template Repository** about the team project.
- Create the *Team Utility Repository** and add some team-specific utilities to the repository.
- Create the **Azure File Storage & Data Science Virtual Machine** to store useful data assets.
- Set up the **Security Control** by adding team members and configure their privileges.

**Project Lead:**
- Create a **Project Repository** under the team project, seed it from the Team project template repository.
- Create a **Azure File Storage & DSVM** to store data assets of the project.
- Set up the **Security Control** by adding project members and configure their privileges.
---------------
**Project Individual Contributor**
- Clone the **Project Repository** set up by the **Project Lead**.
- Mount the shared *Azure File Storage and DSVM**.
- **Execute** the project.
---------------------------

**DS Project Execution**
- All members, excluding the manager, can create work items to track all tasks and stages of the project.
- Essential Version Control in these Artifacts.
- Sprint Planning (Project Lead - Scrum Master)
- Developing artifacts on Git Branches to address work items (DS)
- Code Review and merging branches with master (Data Engineer)


Ref:
***Group Manager Detail Link***:
https://github.com/Azure/Microsoft-TDSP/blob/master/Docs/group-manager-tasks.md
***Team Lead Tasks Detail Link:***
https://github.com/Azure/Microsoft-TDSP/blob/master/Docs/team-lead-tasks.md
***Project Lead Tasks Detail Link:***
https://github.com/Azure/Microsoft-TDSP/blob/master/Docs/project-lead-tasks.md
***Project Individual Contributor Detail Link***
https://github.com/Azure/Microsoft-TDSP/blob/master/Docs/project-ic-tasks.md
**Execution**
https://github.com/Azure/Microsoft-TDSP/blob/master/Docs/project-execution.md