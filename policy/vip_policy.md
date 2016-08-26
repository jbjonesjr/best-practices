## VA VIP Software Policy

The below policy is recommended for inclusion in the VIP Policy as a whole to define a version control and software solution to compliment the existing Configuration Management and Reporting definition of IBM's Rational Team Concert (RTC). This is written after careful investigation into version control systems and their support of the requirements of VIP ([discussed here](../version_control/README.md)).

### VIP Policy
[VIP Guide 1.0 v14](https://github.com/DaveEide/VA-VIP-GitHub-Policy/files/248677/VIP_Guide_1_0_v14.pdf) published December 2015

#### 3.4 GitHub Enterprise

Certain projects or programs will include custom-developed source code (software). This includes developing a solution from scratch, or developing a solution to customize an existing Federal or COTS product. When developing or acquiring custom code, the use of the VA provided GitHub Enterprise (GHE) is required.  

##### 3.4.1 Project Repositories

All code (software) produced shall be developed, version-controlled, and delivered in source code form with associated documentation in a GHE Project Repository, such that real-time third-party review and validation of all code in progress is possible. All source code, dependent code, libraries, or third-party code shall be in portable, industry standard, nonproprietary languages.  

All code must have corresponding documentation, version-controlled in markdown in the same
repository as the source code, and contain at minimum an Installation Guide and a User Guide
for the final delivered source code such that a third party may download, install and make full
functional use of the delivered code as specified and intended. The Installation Guide must list
all required third-party code, libraries or other dependencies.

The GHE Project Repository shall contain the one and only authoritative version of all artifacts produced under a contract.  At the conclusion of a contract the government shall maintain sole ownership of the GHE Project Repository and all contents assuring future availability of all artifacts, future development, and continuity management.

##### 3.4.2 Code Inventories and Discovery

Code inventories are a means of discovering information such as the functionality and location of potentially reusable custom code repositories. The enterprise code inventory is not intended to house the custom code itself; rather, it is intended to serve as a tool for discovering custom code that may be available for reuse. The inventory will indicate whether the code is available for reuse or cannot be made available due to a specific exception.

The VA will provide a central location on GHE as well as an inventory schema that will be used for each project. 
