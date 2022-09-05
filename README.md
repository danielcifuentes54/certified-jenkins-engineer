<img src="icons/jenkins.png" />

# Certified Jenkins Engineer

Information about the topics that are required in the Jenkins Engineer certification.

[How to contribute to Jenkins](https://www.jenkins.io/participate/).

___

## Continuous integration, delivery, and deployment

### Continuous Integration (CI) 
Is the frequent, automatic integration of code. All new and modified code is automatically tested with the master code.

###  Continuous Delivery (CD) 
Is the natural extension of CI. It ensures that the code is always ready to be deployed, although manual approval is required to actually deploy the software to production.

### Continuous Deployment automatically 
Deploys all validated changes to production. Frequent feedback enables issues to be found and fixed quickly.

___

## Source code management systems (SCMs)

Source code management systems (SCMs), also known as version control systems (VCSs), are software systems that record all changes for a set of files over time. This allows you to share those changes and provide merging and tracking history of the recorded changes.

Track every change. SCM is considered the Single Source of Truth.

___

## Software testing

Testing is a critical component of the software development cycle. Include a good set of tests as part of your pipeline so your team can:

- Validate that the software meets its goals.
- Search for defects that can be fixed to improve software quality.
- Facilitate refactoring and upgrades by validating that everything is still working after the changes are applied.

Good testing involves many different types of tests:

- Unit testing, integration testing, smoke testing
- Functional testing
- Non-regression testing
- Acceptance testing
- Code quality and static analysis
- Performance and security testing

>Manual testing should be performed rarely, and only on software that has passed all automated tests. It is appropriate when the test result is subjective, such as user experience testing, and when the cost of automation is excessive.