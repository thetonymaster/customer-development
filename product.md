# Product Hypothesis

## Product Features

- Idempotent deployments across environments
- Continuous delivery
- Easy server configuration
- Unified configuration across environments
- Easy creation of environments
- Dashboard to monitor different services
- Collaboration between team members

## Product Benefits

- Less downtime due to human errors while manipulating servers
- Portability of infrastructure across multiple cloud providers
- Different modules can be used to upgrade the existing infrastructure without much hassle
- Easy integration between different environments to ship new features
- Integrations with CI’s services (?) to be sure the build wild run
- Configuration tailored on real use cases

## Intellectual property

Released code will be put under an OSS Licence (MIT mostly).

## Dependency Analysis

Our product heavily depends on the widespread adoption of VPS or computing in the cloud, also that these providers actually have a public API that can be used to consume and create new VPS.

This product will bring a big impact in the customer development process, to be a successful tool the customer must adopt a set of practices.

## Product Delivery Schedule

| Stage One       | Comment                                    | Release Date  |
| :-------------- | :----------------------------------------- | :-------------|
| Alpha 1         | Creation of the lo-fi MVP                  | 25-October-16 |
| Alpha 2         | First recipes based on real customers      | November      |


## Total Cost of Ownership/Adoption

A total cost is hard to define right now, but the principal variables to adopt, which are time and human capital, since this can suppose a total change of practices, the following can be the persons that can adopt our product.

### Anarchy in the UK

Has no defined process, makes all the the changes directly in production, this implies a total overhaul of practices, can require more time to fully adopt the product, this can lead to an increased usage of infrastructure, or unexpected errors while adopting a new workflow. This types of customers require more education on how and why to use different development environments and stages.

### Has a process, but no automation

Some client might have a process, but they have no automation, while they can have scripts written in bash or simply configuring the servers by hand, they have a defined process of how new features should be implemented in production, they could use disposable infrastructure or have long-running servers. The cost might reside on the adoption of the product and the education of the features it has.

### Has a process, and automation

This can be the rarest of them all. but maybe they can save time by skipping the configuration of different tools. The cost of adoption must be minimum. .
