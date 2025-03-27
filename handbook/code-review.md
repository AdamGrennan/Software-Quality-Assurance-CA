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

