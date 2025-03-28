# Project Plan: Software Quality Handbook

## Purpose
This project aims to create a practical and easy-to-use Software Quality Handbook for a small startup of 20 engineers. It will address best practices for improving consistency, reducing defects, and delivering high-quality software.

The handbook will include the following key topics:
- **Task Estimation in Scrum**
- **Code Reviews**
- **Continuous Deployment & Integration** 

## Workflow
We will follow a **Trunk-Based Development** process:
- Work will be done in feature branches.
- Pull Requests will be reviewed by both team members.
- Code will be merged into the `main` branch after teamates approval.


| **Stage / Task**                        | **Adam** | **Alvares** | **Both** |
| --------------------------------------- | -------- | ----------- | -------- |
| Research Task Estimation (5 resources)  |          |             | ✅        |
| Research Code Reviews (5 resources)     |          |             | ✅        |
| Continuous Deployment (5 resources)     | ✅        |             |          |
| Write Task Estimation section           | ✅        |             |          |
| Write Code Reviews section              |          | ✅           |          |
| Write Continuous Deployment section     |          |             | ✅        |
| Diagrams for Task Estimation            | ✅        |             |          |
| Diagrams for Code Reviews               |          | ✅           |          |
| Peer Review for Task Estimation section |          | ✅           |          |
| Peer Review for Code Reviews section    | ✅        |             |          |
| Handbook Introduction                   |          | ✅           |          |
| Contributions Table                     |          |             | ✅        |
| Peer Reviews & Feedback (all sections)  |          |             | ✅        |
| Final Repo Polish & Pull Requests       |          |             | ✅        |
| Lessons Learned Section                 |          |             | ✅        |
---

## Summary

Given the tight deadline , we have decided to divide tasks based on clear individual ownership. Adam will focus on Task Estimation and contributions table, while Alvares will handle Code Reviews and the Handbook Introduction. We will both collaborate on Continuous Deployment, and peer reviews to ensure consistency and shared responsibility.

We chose Trunk-Based Development to encourage fast iterations and avoid bottlenecks in merging. Peer reviews are planned every second day to maintain alignment and quality.


## Notes
- Team call every second day
- Aim for 500 - 1000 words per topic
- Use bullet points & diagrams
- Use images 
- All sections must contain links to articles for further reading
- Highlight good and bad practices in sections

## Lessons Learned

- Lock down the project plan earlier. We found ourselves reopening the project plan several times to update task lists and contributions. It would be more efficient to finalise it earlier and treat it as a living doc only if absolutely necessary.

- We pushed some images for topics not related to the current branch we were working on. Next time it would be better to push images only related to that working branch.

- Some minor typo issues were only spotted during pull requests related to image sources and links. Allocating some extra time to Quality Assurance could have spotted these earlier.

- There were times when pull requests were approved or merged without thoroughly checking the changes, in raw markdown. In the future, we will take more time to review both rendered output and the actual code to catch issues earlier.
