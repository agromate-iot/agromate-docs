# Agromate.org
Agromate is an open source hardware/software project to aid small farms with automation.

Project management page is here: https://github.com/orgs/agromate-iot/projects/1

State of the union:
This is a fledgling project.  Current thinking is to publish Arduino powered sensors and actuators, talking wifi to a container deployed on a local Linux server.  A UI dashboard, to be deployed on the same local Linus server, will be provided to view device details.  To aid power demands, as well as simplicity, all communication will be unencrypted http.  Devices will have the following common capabilities:
1. Ardiuno components and case details for ordering in README.md
1. Solar powered, with an eye towards power consumption in all designs
1. Ability to write to local media for caching purposes, to support low-connectivity environments
1. Designs should be rugged, and engineered to be serviced in the field by a tech-aware farmer
