## How Version Control Systems integrate with Rational Team Concert

Rational Team Concert (RTC) is a suite of tools from IBM that includes project planning, bug tracking, build and deployments, and reporting. It integrates standalone IBM tools such as ClearCase to create a suite of tools for the software development process.

VA has standardized on RTC for project planning and reporting for VIP. VA has not, however, defined any policy regarding source code version control specifically. 

Over the past few years, IBM has received pushback from its closed, proprietary suite, and has started to open up integration with open, best-of-breed tools.  This page describes some of these IBM RTC integrations.

__Note that currently IBM is the world's largest user of Github,  with over 10,000 paid developer seats on Github Enterprise.  IBM's next-generation enterprise software management platform called BlueMix is also all Github Enterprise-based.__



| Manufacter | Product Name | RTC Support | 
|:------- |:------- |:------:|
| OSS | Git Server | You can use IBM® Rational® Team Concert™ and Git integration to manage process enforcement for Git source control operations and to associate work items with Git commits. The RTC for Jenkins plugin associates Git Builds with Work Objects as well. There is additional configuration (either connection server or server-side hooks) required to make this integration work. |
| GitHub | GitHub Enterprise | Same features as the Git integration described above, but with a simplified management process,via web configurations not server side scripts. Also includes the Jenkins/Build integration and optional support for the GitHub deployment API. |
| GitLab | GitLab CE | Similar to Git intergration via server side hooks. |
| GitLab | GitLab EE | Similar to Git intergration via server side hooks. |
| Apache | Subversion | If you install a Subversion client for Eclipse into the Eclipse instance that supports Rational Team Concert, you can link Subversion revisions to work items. |
| OSS | CVS | Can import, can't use alongside RTC. |
| Perforce | Helix versioning engine | Perforce had trigger integration years ago, but is no longer included in the help documents. Removed?  |
| IBM | RTC Clear Case MultiSite | Integration via Jazz Connectors to translate ClearCase objects to RTC objects. |
| IBM | Rational Team Concert (RTC) | Native |
| Serena | Dimensions CM | Integration in RTC 4, not since. |
| Endevor | Software Change Manager (SCM) | IBM has a competing SLCM tool, no integration. |
| Microsoft | Team Foundation Server (TFS) | Limited integration via third-party tools (including MS-SCCI) |
| Microsoft | Visual Source Safe (VSS) | Limited integration via third-party tools (including MS-SCCI) |

