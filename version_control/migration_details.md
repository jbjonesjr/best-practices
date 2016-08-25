## Future VCS migration concerns
The version control system (VCS) of today might not be the version control system of the future. Being aware of how easy it is to transfer data into and out of different VCS systems is therefore of utmost importance in assuring the future access and re-usability of the code.

Using the TRM-listed VCS, the following table lists the capability to transfer data from one VCS system to another VCS system. 
The columns represent source systems {FROM}; the rows represent the destination systems {TO}.

__Of note is that all VCS systems listed are  capable of exporting all their code and data to Github Enterprise.__ No other VCS system has this universal import/exprt capability.  

In comparison, RTC

| Note |
|:------:|
| When reviewing tools and techniques, we used tools officially supported by the VCS or had a long history of working successfully. |

| | Git | GHE | GL CE | GL EE | SVN | CVS | Perforce | CC-Multi | RTC | Dim. | SCM | TFS | VSS |
|:------- |:------- |:------:|:-------:|:-------:|:------:|:-------:|:------:|:------:|:-------:|:-------:|:------:|:-------:|:-------:|:------:|
| Git | - | **X** | **X** | **X** | **X** | | **X** |  |  |   |  | | |
| GitHub Enterprise | **X** | - | **X** | **X** | **X** | **X** | **X** | **X** | **X** | **X** | | **X** | **X** |
| GitLab CE | **X** | **X** | - | **X** | **X** | **X** | **X** |  |  | **X** | | 
| GitLab EE  | **X** | **X** | **X** | - | **X** | **X** | **X** |  |  | **X** | | 
| Subversion |  **X**| **X** | **X** | **X** | - | **X** | | | | | | | |
| CVS | | | | |  | - |
| Perforce | **X** | **X** | **X** | **X** | **X** |  | - | **X** | **X** |
| CC-Multi | | |  | | | **X** |  | - |
| RTC | **X** | **X** | **X** | **X** | **X** | | | **X** | - | | | **X** | **X** |
| Dimensions CM | | | | |  | | | |  | - |
| Software Change Manager (SCM) |  | | | | |  | | | |  | - |
| Team Foundation Server (TFS) | **X** | **X** | **X** | **X** | **X** | **X** | **X** | **X** | **X** | | | - | **X** |
| Visual Source Safe (VSS) |  | | | | | **X** | |  | | | |  | - |
