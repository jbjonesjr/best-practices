## Future VCS migration concerns
The version control system of today might not be the version control system of the future. Being aware of how easy it is to transfer data out (and in) to a different system is definetly something to be concerned with.

Using the TRM-mentioned VCS, I've constructed a table describing the ability to transfer data {FROM} one system {TO} another. The rows represent the destination system, while the columns represent sources.

| Note |
|:------:|
| When reviewing tools and techniques, I only used tools that were officially supported by the VCS or had a long history of working successfully. |

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
