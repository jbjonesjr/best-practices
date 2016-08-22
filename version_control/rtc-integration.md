## How Version Control Systems integrate with Rational Team Concert

Rational Team Concert (RTC) is a suite of productivity tools from IBM that includes collaborative planning, version control, build and deployments, and reporting. It integrates standalone IBM tools, including ClearCase, to create a integrated suite of tools for the software development process.

VA has standardized on RTC for reporting and planning within VIP, but not explicitly any other of it's use cases.

Over the past few years, IBM has received pushback from their complete suite, and has started to open up integration amongst external tools. This page attempts to describe some of those integrations.


| Manufacter | Product Name | RTC Support | 
|:------- |:------- |:------:|
| OSS | Git Server | You can use IBM® Rational® Team Concert™ and Git integration to manage process enforcement for Git source control operations and to associate work items with Git commits. The RTC for Jenkins plugin associates Git Builds with Work Objects as well. There is additional configuration (either connection server or server-side hooks) required to make this integration work. |
| GitHub | GitHub Enterprise | Same features as the Git integration described above, but with a simplified management process,via web configurations not server side scripts. Also includes the Jenkins/Build integration and optional support for the GitHub deployment API. |
| GitLab | GitLab CE | Similar to Git intergration via server side hooks. |
| GitLab | GitLab EE | Similar to Git intergration via server side hooks. |
| Apache | Subversion | If you install a Subversion client for Eclipse into the Eclipse instance that supports Rational Team Concert, you can link Subversion revisions to work items. |
| OSS | CVS | Can import, can't use alongside RTC. |
| Perforce | Helix versioning engine | Perforce had trigger integration years ago, but is no longer included in the help documents. Removed?  |
| IBM | RTC Clear Case MultiSite | Native |
| IBM | Rational Team Concert (RTC) | Native |
| Serena | Dimensions CM | Integration in RTC 4, not since. |
| Endevor | Software Change Manager (SCM) | IBM has a competing SLCM tool, no integration. |
| Microsoft | Team Foundation Server (TFS) | Limited integration via third-party tools (including MS-SCCI) |
| Microsoft | Visual Source Safe (VSS) | Limited integration via third-party tools (including MS-SCCI) |

