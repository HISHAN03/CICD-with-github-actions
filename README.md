# What is CI/CD?
CI or Continuous Integration is the automatic integration of code changes from multiple developers into a single codebase. It is a software development practice where the developers commit their work frequently into the central code repository . Then there are automated tools that build the newly committed code and do a code review

The key goals of Continuous Integration are to find and address bugs quicker, make the process of integrating code across a team of developers easier, improve software quality and reduce the time it takes to release new feature updates. Some popular CI tools are Jenkins, TeamCity, and Bamboo
# Why CI?
## Scenario 1: No Continuous Integration (CI)
Imagine you have a group of developers working on a software project, but they work on their own without regularly sharing their work with others. They only combine their changes into the main project once they finish their work. This leads to a few problems:
- Combining everyone's work becomes really hard because it's all done at once, and it often results in conflicts, where different pieces of code don't fit together smoothly.
- Since nobody is checking the code frequently, bugs can hide in the code for a long time, making them harder to find and fix.
- it becomes difficult to deliver updates to customers quickly because a lot of time is spent dealing with merging and fixing problems.
## Scenario 2: Continuous Integration (CI)
Instead of working in isolation, developers regularly share their work with a common place (a shared repository) using tools like Git. This common place is like a big box where everyone puts their work. Whenever someone commits their code, a special computer program (CI pipeline) automatically checks their work. It does a few important things:
-It makes sure the code can be turned into a working program.
-t runs tests to make sure the code doesn't break anything that was working before.
-It can even use tools to give feedback on the quality of the code.
## In a nutshell 
Continuous Integration is a way for developers to work together smoothly, catch mistakes early, and deliver software updates faster and with fewer bugs. It's like having a robot assistant that helps ensure the code is always in good shape.
## pictorial representation of a CI pipeline
 ![CIFlow](https://github.com/HISHAN03/CICD-with-github-actions/assets/108483712/ca0d41cb-9376-48cc-8caa-785c7d36cbc7)

