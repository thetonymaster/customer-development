# Customer and their problem

## Types of customers

The types of customers identified so far:

**Developer (end user)**: while the product might or might not be bought by end users, this will be the ones that will interact more with the platform.

**QA (end user)**: while in minor degree, they will interact with the environments created for testing.

**Decision Maker**: Has not been identified who this exactly is, but has come up several times that the end user is not the one that decides to buy a new product.

**Economic Buyer**: again, not identified who this exactly is, but agencies. have a person who manage the money and if it can be expended.

## Customer problems

1. I have problems to scale my infrastructure because it can be very complex.
2. I have problems to deploy my code because of the difference between package versions and environments.
3. I have problems to integrate a new team member into the development team because of the packages needed to install to have a complete development environment.
4. I have trouble to test my code because I don't have a test environment.
5. I have problems learning about infrastructure because the learning curve is to steep.
6. I have trouble learning about configuration managers because the learning curve is to steep.
7. I have trouble retaining clients that use configuration managers because I don't know to use them.  
8. I have trouble maintaining my servers secured because I don't know about hardening best practices.
9. I have trouble controlling attacks because I don't know the best security practices.
10. I have trouble replicating my infrastructure due to the dependencies and configurations in development.
11. I have trouble migrating my infrastructure to another provider because I cannot replicate easily my server configuration.
12. I have problems managing the infrastructure's hardware because I have no way to monitor easily my servers.
13. I have trouble managing my clients because I don't have an specialist in infrastructure.
14. I have high infrastructure costs because I prefer to pay rather than my servers to fail.
15. I have high infrastructure costs because only AWS offers the flexibility I need.
16. I have trouble testing because I don't have the necessary infrastructure.
17. I have trouble adding new features to my solutions because I need to add the infrastructure guy if we can deploy code to production.

## A day in the life of your customers

A daily life in an agency the flow of development is the following:

1. If a new developer is integrated to a team, the developer either installs all 
    the needed dependencies in his own computer based on what the team is using
    or use a file that specifies versions (like bundler, mix or npm).
2. Developers code and runs the unit testing locally, after this it may execute it 
    and test if it really works. It is pushed to a repository which may have continuous
    integration.
3. This is an optional step, since not every agency actually does this. The application
    is shipped to QA to provide some Quality Assurance
4. Features are then shipped to operations, which may start a new server instance 
    or have one already running (this instance could have started ages ago, which 
    can be prone to errors due to obscure configurations).
5. During outages there is not a simple way to replicate a previous provisioned environment
    and they do not have a defined process to follow to analyze it.

## Organizational map and customer influence map

## ROI (return on investment) justification

## Minimum feature set

- Unified configuration
- Easy deployment
- Easy creation of environments
