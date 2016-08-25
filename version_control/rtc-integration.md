## IBM Rational Team Concert Integrations to Version Control Systems

VA has standardized on IBM's Rational Team Concert (RTC) for project planning and reporting for the past several years. RTC is a suite of tools from IBM originally developed in the early 1990's. It includes project planning, bug tracking, build and deployments, and reporting. It also integrates other IBM-proprietary tools such as ClearCase to create a suite of tools for the software project management process.   

VA has not, however, defined any policy mandating source code version control for any of its enterprise software . As a result many mission critical systems (most notably VA's VISTA, comprised of over 2 million lines of code and over 35,000 files over the past 30+ years) is not under any source code version control at all.

Since the 2000's most software development has leveraged open source, web-based collaborative platforms such as Github to attract the largest and best developer talent. The largest software development organizations (includig Micosoft, Google, eBay, and Facebook) all publish and version control their source code on the web to reach the largest developer community inside and outside their organization. 

Therefore, to keep pace with these changes, and to keep the 20+ year-old RTC software relevant, IBM has opened up integration of RTC with the current best-of-breed open-source based collaborative tools such as Github.  This page describes some of these IBM RTC integrations.

__Of note, IBM is now the world's largest corporate user of Github,  with over 10,000 paid developer seats using Github Enterprise on a daily basis.  IBM's next-generation enterprise software management platform called BlueMix is also all Github Enterprise-based.__


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

