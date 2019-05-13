# Cloudera Data Flow Demos

## Project Goal
This project was created in order to make demonstrating capabilties of the Cloudera Data Flow Platform more consumable and reproducable. There have been several really awesome demos over the years but they have not been captured in a means that allows for people to spin them up and try for themselves. This project aims to make people more creative; be curious! Get in here and build something fun and then share it with the world!

## Pre-Requisites
At the time of writing Ansible is the only dependencies for using this project. The aim is for all the demos to be built using Ansible and therefore a common consumption pattern. Ansible 2.7 was used at the time of writing. Ansible is a simple and clean Python application written and maintained by RedHat. Installation is particularly easy of OS X and can be accomplished by simply running ```brew install ansible```.

## Running

## Demos
| Demo        | Running           | Description  |
| :-------------: |:-------------:| :-----:|
| weblogs-demo | ansible-playbook -i host weblogs-demo.yml | Demonstrates tailing NGinx info and error logs with MiNiFi C++ agents and streaming those logs to NiFi |