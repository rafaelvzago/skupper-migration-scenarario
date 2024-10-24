# Skupper Migration Scenario

This scenario demonstrates how to migrate an existing application to a new environment using Skupper.

## Details

1. The application is a set of projects running on OpenShift. The projects are connected to each other using the backend service name.
2. There are 10 projects in total, each with a unique name.

## Objectives

1. Create the Projects in the existing environment and deploy the backend and frontend services in each project.
2 Replicate the existing environment in a new OpenShift cluster using Ansible.
3. Using skupper, migrate the application to a new environment, by connecting the projects using the backend service name into a new OpenShift cluster.


## Details

1. Frontend application: quay.io/skupper/hello-world-frontend
2. Backend application: quay.io/skupper/hello-world-backend
