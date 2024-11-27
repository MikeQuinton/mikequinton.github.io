---
title: "Creating a CI/CD pipeline with Github Actions"
date: 2024-11-27T15:06:37+01:00
Description: ""
Tags:
  - Github Actions
  - CI/CD
Categories: ["CI/CD"]
DisableComments: false
---
What is CI/CD?
Continuous Integration (CI):
This is the practice of frequently merging code changes into a shared repository. Back in the day, teams or individuals used to work on their own branches for months, merging infrequently. This made it painful to resolve conflicts and fix bugs. With CI, developers integrate their work often, so errors are caught and resolved early.

Continuous Delivery (CD):
CD ensures your application is always in a deployable state. The idea is to create a deployment pipeline that validates changes through automated testing, moves those changes through testing environments, and ultimately deploys them to production seamlessly.

CI/CD Combined:
Together, CI/CD means developers merge their code regularly, validate it through automated tests, and generate a release candidate multiple times a day. Those release candidates are automatically deployable into production if everything checks out.

ELI5 Example:
Picture a car factory:
    Raw materials (code) enter the assembly line.
    Machines (tests and build tools) assemble parts, inspect for defects, and paint the car.
    At the end of the line, the finished car (release candidate) rolls off, ready for the customer.
Without this automation, workers would need to handle each car manually, slowing things down and making errors more likely. CI/CD creates that "assembly line" for your code

