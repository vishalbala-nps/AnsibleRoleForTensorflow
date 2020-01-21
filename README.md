# AnsibleRoleForTensorflow
An Ansible Role to install Tensorflow
## Overview

This is an Ansible role for automating the installation of Tensorflow.

## Requirements

-   You need to have a user on the remote server configured with passwordless sudo.
-   The remote server should also have ssh configured based on Ansible's requirements

## How to Use

-   Begin by first cloning the repository with the command:  `git clone https://github.com/vishalbala-nps/AnsibleRoleForTensorflow`
-   Change the IP Address of the remote server in the inventory file and change the remote server username in the test.yml file
-   Run the role by typing the command  `ansible-playbook -i inventory test.yml`
- 
## What is Tensorflow?

Tensorflow is an open-source, machine learning platform. The libraries are available for Python, JS, iOT and mobile devices. The libraries provide facilities to load and preprocess the data, build and train the models and deploy them.

This Role installs the Python module for Tensorflow.
