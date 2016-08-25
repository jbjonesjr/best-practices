## Version Control Systems interaction with Open Source Software & community

Not every version control is embraced, used by and integrated into the Open Source world the same. Open Source programs offer many advantages over their closed source counterparts, and this relationship needs to be a factor in any version control system decisions.

### Version Control Open Source interaction
This section identifies how products participate and support the Open Source community.

| Manufacter | Product Name | Notes | 
|:------- |:------- |:------:|
| OSS | Git Server | Open Source Software, underpinning of modern OSS workflows. |
| GitHub | GitHub Enterprise | Closed source product. Many of its components are released Open Source. GitHub is the largest host of Open Source projets on the Internet. GitHub supports the open source community by sponsoring numerous projects, including `Google Summer of Code`, `Rails Girls`, and `Debian`. |
| GitLab | GitLab CE | Open Source Software. |
| GitLab | GitLab EE | Closed Source Software, based on GitLab CE |
| Apache | Subversion | Open Source Software. Powers many open source projects hosted by the Apache Foundation. Prior to Git, Subversion was the OSS version control of choice. |
| OSS | CVS | Open Source but deprecated. Not used for OSS currently (legacy). |
| Perforce | Helix versioning engine | Closed Source. Licensing is prohibitive to open source work. |
| IBM | RTC Clear Case MultiSite | Closed Source. Licensing is prohibitive to open source work.|
| IBM | Rational Team Concert (RTC) | Closed Source. Licensing is prohibitive to open source work. |
| Serena | Dimensions CM |  Closed Source. Licensing is prohibitive to open source work. |
| Endevor | Software Change Manager (SCM) | N/A |
| Microsoft | Team Foundation Server (TFS) | Closed Source Software that includes includes open source components. Has some available pieces that aid the Microsoft Open Source Community. Actively Open Source their code where possible. Starting to "make open by default" |
| Microsoft | Visual Source Safe (VSS) |  Closed Source. Not used for OSS currently (legacy). |

### Version Control Open Source workflows and enablement

| Manufacter | Product Name | Notes | 
|:------- |:------- |:------:|
| OSS | Git Server | Most common VCS for OSS. Ease of patching, merging, branching, and remote distribution. |
| GitHub | GitHub Enterprise | Premier hosting platform for Git code. Based on GitHub.com, the SAAS open source hosting platform which holds the majority of the world's open source code (over 38 million projects, 15 million users). Created Pull Requests as a way to discuss changes (neccessary for large and distributed teams) and maintain an integration ecosystem with best of breed toolings. |
| GitLab | GitLab CE | Similar features to GitHub, but attempt to bundle key tools instead of focusing on a best-of-breed approach. |
| GitLab | GitLab EE | Same as GitLab CE. |
| Apache | Subversion | Baseline featureset for VCS. No longer used prominently, replaced by Git. Recent updates have tried to make it competitive again. |
| OSS | CVS | Not used. |
| Perforce | Helix versioning engine | Provides no-cost license to open source projects. |
| IBM | RTC Clear Case MultiSite | No OSS connection. [Ref.](https://www.safaribooksonline.com/library/view/ibm-rational-clearcase/9781849680127/apas03.html) |
| IBM | Rational Team Concert (RTC) | RTC suite is used by some coperate OSS projects, but typically not the version control aspects (just issue tracking, etc) |
| Serena | Dimensions CM | No OSS Connecction. |
| Endevor | Software Change Manager (SCM) | No OSS Conenction, Mainframe.  |
| Microsoft | Team Foundation Server (TFS) | Microsoft's Open Source (which there is plenty) is released on GitHub, not TFS Online. |
| Microsoft | Visual Source Safe (VSS) | No OSS Connection. |
