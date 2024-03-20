### INTRODUCTION

This python project is aimed at showcasing some characteristics of cloud-native
web applications - redundancy, resilience and least-privileged. There is no
actual cloud resources associated with the exercise as this is just a simulation.
Look into the k8s project for a real-life example of interacting with live
environment. Followed is the explanation of the terms.

- Redundancy: Kill an instance (VM or Container) of the App while it's running
, and check if the App continues to work & provide service
- Resiliency: Kill an instance (VM or Container) of the App while it's running
, and check if the instance (VM or Container) restarts/recovers with no
human intervention, and continues to provide service
- Least-Privilege: Check if the App is not using admin or root level access

### DEPENDENCIES AND REQUIREMENTS

You will need to have python2.7 or python3 installed on your machine in order to
run this task.
