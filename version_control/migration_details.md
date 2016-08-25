## Future VCS migration concerns

The version control system one uses today is not the VCS one will use in the future.  Therefore, the capability to import and export all code and metadata  from one's VCS system to the next generation VCS is of utmost importance in selecting a VCS to maximize access and re-usability of the code in the future. 

The following table lists the capability to transfer data from one VCS system to another VCS systems. (The columns represent source systems; the rows represent the destination systems.)

__As the table summarizes,  Github Enterprise is the VCS capabile of importing and expoting the data and code from the most number other VCS systems, making it the current best choice as VA's "Universal Code Repository".__


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
