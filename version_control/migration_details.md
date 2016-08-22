## Future VCS migration concerns
The version control system of today might not be the version control system of the future. Being aware of how easy it is to transfer data out (and in) to a different system is definetly something to be concerned with.

Using the TRM-mentioned VCS, I've constructed a table describing the ability to transfer data {FROM} one system {TO} another. The rows represent the source system, while the columns represent destinations.


| | Git | GHE | GL CE | GL EE | SVN | CVS | Perforce | CC-Multi | RTC | Dim. | SCM | TFS | VSS |
|:------- |:------- |:------:|:-------:|:-------:|:------:|:-------:|:------:|:------:|:-------:|:-------:|:------:|:-------:|:-------:|:------:|
| Git | - | **X** | **X** | **X** | **X** | | **X** |  |  |   |  | **X** | **X**v|
| GitHub Enterprise | **X** | - | **X** | **X** | **X** | **X** | **X** | **X** | **X** | **X** | | **X** | **X** |
| GitLab CE | **X** | **X** | - | **X** | **X** | **X** | **X** |  |  | **X** | | 
| GitLab EE  | **X** | **X** | **X** | - | **X** | **X** | **X** |  |  | **X** | | 
| Subversion |  | | |  | - | **X** |
| CVS |   | | | |  | - |
| Perforce |  | | | | |  | - |
| RTC Clear Case MultiSite |  | |  | | | |  | - |
| Rational Team Concert (RTC) |  | | |  | | | |  | - |
| Dimensions CM | | | | |  | | | |  | - |
| Software Change Manager (SCM) |  | | | | |  | | | |  | - |
| Team Foundation Server (TFS) | | | | | | |  | | | |  | - |
| Visual Source Safe (VSS) |  | | | | | | |  | | | |  | - |
