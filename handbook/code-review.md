# Code Reviews

Code reviews, which is also known as peer reviews, is a systematic software quality assurance technique for developers in which the code is reviewed to find and fix errors, improve code quality, and enforce coding standards. In this section, we will be discussing the best practices that must always be completed when taking part in a code review. The aim is to provide a practical guide that helps your team navigate code reviews in a more efficient manner while also enforcing the companies coding standards.

## Good Practices

### Create a code review checklist

- *Readability:* Is the code redundant?

- *Security:* Does the code expose the system to a cyber attack?

- *Test coverage:* Is there a need for more test cases?

- *Reusability:* Does the code use reusable components, functions, and services?

### Introduce code review metrics

- *Inspection rate:* The speed at which your team reviews a specific amount of code. If it takes a long time to review the code, there may be readability issues that need to be addressed.

- *Defect rate:* The frequency with which you identify a defect. This metric helps determine the effectiveness of your testing procedures; for example, if your developers are slow to find defects, you may need better testing tools.

- *Defect density:* Defect density helps identify which components are more prone to defects than others, allowing you to allocate more resources toward the vulnerable components. 

- When reviewing code, don’t simply suggest what needs to be fixed or improved upon – explain why the developer should make that change.

### Don’t review more than 200-400 lines of code at a time

- Reviewing more than 400 lines of code (LoC) can have an adverse impact on your ability to find bugs, most bugs are found in the first 200 lines. 

## Bad Practices

### Overly large pull requests

- A large pull request can introduce review fatigue, leading to shallow reviews or ignored sections of code.

### Not leaving actionable feedback

- Comments like "This looks wrong" or "I don't like this" offer no clear direction for improvement. Constructive, actionable feedback is essential to help the other party improve the code effectively.

### Rushing the review process

-  Rushed reviews often happen when deadlines are tight or when the reviewer is managing multiple tasks at once, this can lead to missed bugs, security issues, or poor-quality code slipping through. Thoroughly reviewing the code is crucial to avoid mistakes later on.

## Common Themes

*Clarity & Readability*
- Can someone else understand what this code is doing?
- Does it follow logical structure and naming conventions?

*Functionality*
- Does the code do what it claims to do?
- Are edge cases and requirements handled correctly?

*Code Simplicity*
- Is the solution as simple as possible?
- Are there areas that are unnecessarily complex or could be refactored?

*Consistency with Project Standards*
- Is the code consistent with existing style guides and architecture?
- Are patterns reused rather than reinvented?

*Test Coverage*
- Are there adequate tests for the changes?
- Do tests cover both success and failure scenarios?