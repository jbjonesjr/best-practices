## Future VCS migration concerns

The version control system (VCS) one uses today is not the version control system one uses in the future.  

Therefore the capability to import and export all data and code into and out of the maximum number of other VCS systems is of utmost importance in selecting a VCS to assure access and re-usability of the code, thus "future-proofing" the code.

Using the TRM-listed VCS, the following table lists the capability to transfer data from one VCS system to another VCS systems. (The columns represent source systems; the rows represent the destination systems.)

__Github Enterprise is the VCS capabile of importing all data and code from all other VCS systems__. No other VCS system has this universal import/export capability.


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
