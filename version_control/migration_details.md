## Future VCS migration concerns

The version control system one uses today is not the VCS one will use in the future.  Therefore, the capability to import and export all code and data from the current VCS system to the next generation VCS is of utmost importance in selecting a VCS, and thus maximize access and re-usability of all code in the future. 

The following table lists the capability to export and import data from one VCS system to another VCS systems. The columns represent source systems {FROM}; the rows represent the destination systems {TO}.

There is one VCS that spans the entire row, meaning that it would accomodate all legacy code in all current VCS systems in VA. This will allow VA to manage *all* its code by *one single* enterprise VCS.   __No other VCS other than Github Enterprise fulfills this criteria as a "Universal Repository".__

In comparison, RTC VCS has considerable gaps in its capability to import code and data from five key VCS systems currently used in VA,  making it impossible to access this code in the future. 


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
