**Data Science Process Lifecycle** 
Is an iterative agile methodology, the main goal is to deliver predictive analytics and intelligent applications efficiently.
Helps improve team collaboration and it's good to understand how team works best together.

This Document has the goal to create a solid **Data Science Licycle definition**, with a **Standardized Project Structure**, well defined **Infraestructure and Resources** for DS projects and **Tools and Utilities** to manage the project execution.

In this **Lifecyle** we have **four phases**:
- **Business Understanding**
- **Data Acquisition and Understanding**
- **Modeling**
- **Deployment**
- **Customer Acceptance**

![image.png](/.attachments/image-e106a42b-4c42-431e-89d7-09c89a4cdc8d.png)

We will define the **Goals, Tasks and Documentation Artifacts** for each role in this DS lifecycle, the roles will be define in another topic.

Roles in DS Lifecycle:
- **Project manager**
- **Project lead**
- **Solution architect**
- **Data scientist**

Visual Example about roles, tasks and acceptance criteria
![tdsp-tasks-by-roles.png](/.attachments/tdsp-tasks-by-roles-662b6751-3100-4162-b0e5-68cc50360376.png)

**Project Structure**

All Projects must be standardized, in a directory with templates available, so it will be easy to team members find crucial information about any project.
Codes and Documents will be storage in a Version Control System (VCS), we use the Azure DevOps environment (Repos). 
This will allow teams to closer-control codes for individual features. It's good to create separate repositories for each project in the Version Control System, so you can have more information security and collaboration.

**Infrastructure and Resources**

Our Azure infrastructure provide resources to store our raw data and to process datasets, this structure enable reproducible analysis, avoids duplication and  unnecessary infrastructure costs.

**Tools and Utilities**

This tools and utilities are designed to provide a fast pace in common tasks in the data science lifecycle, such as data exploration, modeling and acceptance criteria reports.

**Ref:**
https://docs.microsoft.com/en-us/azure/machine-learning/team-data-science-process/
