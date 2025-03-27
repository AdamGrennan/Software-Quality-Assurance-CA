# Continuous Integration and Continuous Deployment (CI/CD)

## Good Practices

### Automate Pipeline

- Utilise CI/CD tools to build, test, and deploy.
- Automating the pipeline leads to faster releases, better code quality, fast feedback, and less downtime.
- Faster feedback form customers allows for better quality of product.

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

## Common Themes


<img src="images/CI-CD pipeline.drawio.png"/>

## Further Reading 

- *Learnings from the journey to continuous deployment* https://www.linkedin.com/blog/engineering/optimization/learnings-from-the-journey-to-continuous-deployment
  
- *Continuous Integration Best Practices: Vision and Reality* https://www.cloudbees.com/continuous-delivery/continuous-integration-best-practices

- *Top 10 Bad CI/CD Practices That Are Slowing You Down (And How to Fix Them)* https://appcircle.io/blog/bad-ci-cd-practices

- *An introduction to Continuous Integration (CI) and Continuous Delivery (CD) pipelines for software testers* https://www.linkedin.com/pulse/introduction-continuous-integration-ci-delivery-cd-1uhle/

- *Devs on teams that deploy anytime you want, what does your SDLC workflow look like?* https://www.reddit.com/r/ExperiencedDevs/comments/136oso0/devs_on_teams_that_deploy_anytime_you_want_what/