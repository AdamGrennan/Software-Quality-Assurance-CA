# Continuous Integration and Continuous Deployment (CI/CD)

Continuous integration (CI) is a process that runs automated checks each time a developer commits their changes to a code repository. Developers will generally make small changes and commit more often when using CI. This way they get fast feedback that their change hasn’t unintentionally broken any key components. 

Continuous Deployment (CD) is the next step in the process after CI. Once the code successfully passes the automated checks, it’s automatically sent to production. 

In this section, we will outline key best practices that should be consistently applied within CI/CD workflows. These guidelines are intended to help your team implement CI/CD pipelines more effectively, ensuring faster delivery, reduced errors, and improved collaboration across the development lifecycle.

## Good Practices

### Automate Pipeline

- Utilise CI/CD tools to build, test, and deploy.
- Automating the pipeline leads to faster releases, better code quality, fast feedback, and less downtime.
- Faster feedback from customers allows for better quality of product.

### Use Trunk-Based Development with Feature Branches

- Use small, frequent commits directly to the main branch feature branches.
- Avoid long-running branches which delay integration and cause painful merge conflicts.
- Enforce pull requests with automated checks and team review.

### Builds with Most Recent Changes

- Commit at least once a day, commiting a weeks worth of work all at once cause risk of conflict.
- Commiting every day can lead to better identifications of issues, by focusing on specific parts of the system.
  
### Feature Flags

- Feature flags let you deploy incomplete features safely without exposing them to users.
- This allows for safer continuous deployment without waiting for a feature to be fully finished.

### Fast Reliable Testing
- Optimise test suites to give fast feedback.
- Run unit, integration, and regression tests automatically as part of the pipeline.

## Bad Practices

### Ignoring feedback from the pipeline

- Ignored warnings and failures lead to a lack of trust in the pipeline. If developers think the pipeline is “always broken,” they’ll bypass it, reintroducing manual errors.

### Overcomplicating pipelines

- Complexity leads to fragility—one small failure can derail the entire pipeline.
- New team members struggle to understand and contribute to the pipeline.

### Skipping security and compliance checks

- It leaves your software vulnerable to attacks.
- You risk failing compliance audits, which can have legal and financial consequences.

### Still Relying too much on Manual Steps

- Manual steps slow everything down.
- They introduce inconsistencies and increase the risk of errors.

### Lack of Proper Monitoring and Metrics

- You can’t identify bottlenecks or inefficiencies.
- It’s harder to debug when something goes wrong.

## Common Themes


<img src="images/CI-CD pipeline.drawio.png"/>

## Further Reading 

- *Learnings from the journey to continuous deployment* https://www.linkedin.com/blog/engineering/optimization/learnings-from-the-journey-to-continuous-deployment
  
- *Continuous Integration Best Practices: Vision and Reality* https://www.cloudbees.com/continuous-delivery/continuous-integration-best-practices

- *Top 10 Bad CI/CD Practices That Are Slowing You Down (And How to Fix Them)* https://appcircle.io/blog/bad-ci-cd-practices

- *An introduction to Continuous Integration (CI) and Continuous Delivery (CD) pipelines for software testers* https://www.linkedin.com/pulse/introduction-continuous-integration-ci-delivery-cd-1uhle/

- *Devs on teams that deploy anytime you want, what does your SDLC workflow look like?* https://www.reddit.com/r/ExperiencedDevs/comments/136oso0/devs_on_teams_that_deploy_anytime_you_want_what/