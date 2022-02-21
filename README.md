# DevOps interview test #1

This is a basic repository with Django 2.2 tutorial polls application (taken straight from the Django project's official website) with some simple tasks to the offline DevOps technical interview and it have been cloned from a real interview process from a company some years ago, but it is still more valuable now after all this years.

## DevOps Candidates

This app will be used as a base for work for your next test (#2) and we'll discuss and evaluate both tests during your online technical interview. Now, we have a few different tasks for you based on this diagram:

1. Fork this repository.
1. Improve the Dockerfile to create a image of **Django pool application**.
1. Write an example set of manifests to deploy this app with 03 replicas, a postgresql database and a nginx frontend to Kubernetes 1.20.x.
1. The deployment should automatizate tasks like creation and populating the database.
1. Write some brief documentation on how we might launch this app in KIND or Minikube using your manifests.
1. Find and fix at least one thing in code does not conform to the [12-factor app model](https://12factor.net/)
1. Create a list of any questions that you would have for the engineering team

## Goals

Our goals in reviewing this exercise with you are as follows:

1. Evaluate your ability to ask questions and propose changes.
1. Evaluate your ability to documentate and work with git (branches, pull requests, merges and others).
1. Evaluate your ability to find and solve problems.
1. Evaluate your ability to improve deployments (considering the actual diagram environment).
1. Evaluate your ability to understand and help build a good developer experience.
1. Evaluate your ability to understand and write basic application code.
1. Show an understanding of Kubernetes resources and declarative infrastructure.
1. Show knowledge about security and performance issues.
1. Show knowledge of both development and production concerns surrounding microservices and containerized applications.
1. Show knowledge of what questions and concerns to raise to a product development team or your own teammates in developing and releasing a service.

## What to expect

While working on this challenge, you are welcome to email us for any clarification or requirement questions you have. Our recruiter will let you know who to talk to during this process if you have any questions.

During the online technical interview we will review your work on both tests, go through the PR as we would any code review, and discuss the decisions you made and fixes you chose to implement, as well as any additional concerns you have. Be prepared to also discuss CI/CD for the app, though we do not expect you to build anything for this.

> ***We only expect you to spend a few hours on this.*** You're welcome to do as much as you'd like to do, but it's not our intention to take up days of your time. If there are things you don't have the time to fix or improve, feel free to only work on the required to have the system working and  please be prepared to talk us through them at the interview.
