# Product Hypothesis

## Product Features

- As a developer I want to visualize easily the status of my projects so that 
    I can focus my attention where is more needed.
- As a developer I want to easily integrate changes between environments so I have less errors.
- As a developer I want to create test environments so others can verify my work.
- As a developer I want to notify others when my changes are ready to test so the team can proceed rapidly.
- As a developer I want to replicate the configuration of other environments to identify and fix errors.
- As a developer I want to visualize the status of my services to react accordingly to each situation.
- As a tester I want to notify the status of a set of changes to my coworkers.
- As a project leader I want to create a project easily so that I can start to work quickly
- As a project I want to know the lead time between sets of changes to improve my process.
- As a project leader I want to deploy code to different environments with a set of rules, to test and
  integrate changes.
- As a project leader I want to change existing configuration or add more services to change it 
  according to my needs
- As a project leader I want to integrate my new team members fastly so I spend more time on other activities. 
- As a project leader I want to deliver changes constantly to test them an react more quickly.
- As a project manager I want to add more people to an existing project so I can give him permissions over it.
- As a project manager I want to quickly integrate people on a project so that they have less lead time integrating on the team.
- As a project manager I want to send changes faster to my customer to react to its needs.

## Product Benefits

    1. Start with development faster
        * Create projects within minutes with the tools of your needs.
    2. Replicate projects in minutes:
        * Locally(virtualized)
        * In-house
        * In the cloud(VPS)
    3. Improve your projects
        * Add new tools instantly.
        * Add changes, test them and apply them.
    4. Manage easily your projects.
        * Improve, replicate and create your projects from the interface.
    5. Collaborate with your team.
        * Notifications on changes.
        * Download full projects and go directly to development.
        * Track the state of deploys in different stages.
        * Visualize your infrastructure and services. 

## Intellectual property

Released code will be put under an OSS Licence (MIT mostly).

## Dependency Analysis

Our product heavily depends on the widespread adoption of VPS or computing in the cloud, also that these providers actually have a public API that can be used to consume and create new VPS.

This product will bring a big impact in the customer development process, to be a successful tool the customer must adopt a set of practices.

## Product Delivery Schedule

| Stage           | Comment                                       | Release Date   |
| :-------------- | :-------------------------------------------- | :------------- |
| Alpha 1         | Create servers and provision them             | 25-October-16  |
| Alpha 2         | First recipes based on real customers         | December       |
| Alpha 3         | Create local environments                     | January 2017   |
| Alpha 4         | Create and track another environments         | February 2017  |
| Alpha 5         | Add other providers                           | March 2017     |
| Alpha 6         | Basic monitoring                              | April 2017     |
| Alpha 7         | Visualize status of services                  | May 2017       |
| Alpha 8         | Project user management                       | June 2017      |
| Alpha 9         | Continuous Integration integrations           | July 2017      |
| Beta 1          | Hooks for deploys                             | August 2017    |
| Beta 2          | Start to add modules (i.e. security, testing) | September 2017 |
| Beta 3          | Collaborative integrations (slack)            | October 2017   | 
| Beta 4          | User permissions fine tuning                  | November 2017  |
| Beta 5          | Rules for destroying servers                  | December 2017  |
| Beta 6          | Permissions for servers (create, destroy)     | January 2018   |



## Total Cost of Ownership/Adoption

A total cost is hard to define right now, but the principal variables to adopt, which are time and human capital, since this can suppose a total change of practices, the following can be the persons that can adopt our product.

### Anarchy in the UK

Has no defined process, makes all the the changes directly in production, this implies a total overhaul of practices, can require more time to fully adopt the product, this can lead to an increased usage of infrastructure, or unexpected errors while adopting a new workflow. This types of customers require more education on how and why to use different development environments and stages.

### Has a process, but no automation

Some client might have a process, but they have no automation, while they can have scripts written in bash or simply configuring the servers by hand, they have a defined process of how new features should be implemented in production, they could use disposable infrastructure or have long-running servers. The cost might reside on the adoption of the product and the education of the features it has.

### Has a process, and automation

This can be the rarest of them all. but maybe they can save time by skipping the configuration of different tools. The cost of adoption must be minimum. .
