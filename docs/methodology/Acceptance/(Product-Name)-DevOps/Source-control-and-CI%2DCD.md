#**Source Control**

This is and essential tool for Data Science Team and allow developers collaborate on code and track changes that are made to the code base.

- Ability to track|audit changes
- Ability to revert changes that introduced bugs

#**Continuos Integration and Continuos Delivery/Deployment (CI/CD)**

Continuous integration is the practice of testing each change made to your codebase automatically and as early as possible. Continuous delivery follows the testing that happens during continuous integration and pushes changes to a staging or production system.

In Azure Data Factory, CI/CD means to moving Data Factory pipelines from one environment (development, test, production) to another.

#**How is the CI/CD Lifecycle?**

- Data Facrtory is created and configured with Azure Repos Git. All members should have permision to access Data Factory resources.
- When developers made changes in their feature branches, they should debug their pipelines with the recent changes.
- When changes satisfy the developers, they create the **Pull-Request** from their feature branch to the **master branch**.
- The changes will be reviewed by peers.
- After the pull is approved and the changes are merged in the master, the changes are published in the development factory.
- When the team is ready to deploy the changes to the test factory and then to the production factory, the team exports the Resource Manager template from the master branch.
- The exported Resource Manager template is deployed with different parameter files to the test factory and the production factory.

##**Best Practices for Git Integration**

- All members should have **read** permission to the Data Factory
- Only a few members should be allow to publish to the Data Factory environment.

**Ref:**

https://docs.microsoft.com/en-us/azure/data-factory/source-control
https://docs.microsoft.com/en-us/azure/data-factory/continuous-integration-deployment
