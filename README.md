# Agromate.org
Agromate is an open source hardware/software project to aid small farms with automation.

Project management page is here: https://github.com/orgs/agromate-iot/projects/1

State of the union:
This is a fledgling project.  Current thinking is to publish Arduino powered sensors and actuators, talking wifi to a container deployed on a local compute.  A UI dashboard, to be deployed on the same local computer, will be provided to view device details.  To aid power demands, as well as simplicity, all communication will be unencrypted http.  Devices will have the following common capabilities:
1. Ardiuno components and case details for ordering in README.md
1. Solar powered, with an eye towards power consumption in all designs
1. Ability to write to local media for caching purposes, to support low-connectivity environments
1. Designs should be rugged, and engineered to be serviced in the field by a tech-aware farmer

![High Level Design](https://github.com/agromate-iot/agromate-docs/blob/main/img/hldPhase0.png)

# To Install agromatic-server
1. Install Oracle Virtual Box. I used 6.1.16, but you can probably get away with the latest: https://www.oracle.com/virtualization/technologies/vm/downloads/virtualbox-downloads.html
1. Create a new local directory.  E.g., C:\agromate-server
1. Open Virtual Box > New
--1. Name: agromate-server
--1. Location: The directory you created above
--1. Type: Ubuntu
--1. Next
--1. RAM: 1024mb should be plenty, Next
--1. Create a virtual hard disk now, Next
--1. VDI, Next
--1. Fixed Size, Next
--1. 20GB should be plenty, Next
--1. Virtual Machine should now be creating, git it a couple minutes
1. Start agromate-server by pressing 'Start' button
