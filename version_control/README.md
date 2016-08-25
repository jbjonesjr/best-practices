# VA Code Version Control Systems (VCS):  Recommendations

The VA Technical Reference Model (TRM) is a catalog of software products with associated recommendations.  These recommendations range from: 
* approved (unrestricted use)
* approved with constraints (limited use)
* deprecated / divest (time-limited use) 
* unapproved /  prohibited (no use permitted)

## TRM Products with VCS capability
The folllowing is a list of products in the TRM which have code version-control system  (VCS) capability.

Source code version control may be a core feature (Perforce, CVS, or Github and all Git-related technologies) or may be a non-core, plug-in feature which is replaceable with any other core VCS system (i.e. the Microsoft and IBM's project management tools have replaceable, plug-in VCS).

Recommendation for VIP to meet compliance with the U.S. Federal software repository / version control directives are included.

| Manufacter | Product  | Current Status |Recommended<br>Status |
|:------- |:------- |:------:|:-------:|
| OSS | Git Server | [Divest](http://www.va.gov/TRM/ToolPage.asp?tid=6396) | Approve |
| GitHub | GitHub Enterprise | [Divest](http://www.va.gov/TRM/ToolPage.asp?tid=9533#) | Approve |
| GitLab | GitLab CE | [Unapproved](http://www.va.gov/TRM/ToolPage.asp?tid=9580) | __Approve with constraints__ <br> (must integrate with Github Enterprise) |
| GitLab | GitLab Enterprise | [Divest](http://www.va.gov/TRM/ToolPage.asp?tid=9463#) | __Approve with constraints__ <br> (must integrate with Github Enterprise) |
| Apache | Subversion | [Prohibited](http://www.va.gov/TRM/ToolPage.asp?tid=6573) | No change |
| OSS | CVS | [Prohibited](http://www.va.gov/TRM/ToolPage.asp?tid=194) | No change |
| Perforce | Helix versioning engine | [Prohibited](http://www.va.gov/TRM/ToolPage.asp?tid=268) | No change <br>(Migrate all existing  code in Perforce to Github Enterprise) | 
| IBM | Clear Case MultiSite | [Divest (Read-only)](http://www.va.gov/TRM/ToolPage.asp?tid=39#) | No change <br>(Migrate all existing  code in Clear Case to Github Enterprise) | 
| IBM | Rational Team Concert (RTC) | [Approved](http://www.va.gov/TRM/ToolPage.asp?tid=5085#) | __Approve with constraints__ <br>(Use only for project management; <br>for all code use Github Enterprise) <br> OR <br> __Migrate to IBM BlueMix__ <br>(Web-based DevOps with integrated Github Enterprise) |
| Serena | Dimensions CM | [Divest](http://www.va.gov/TRM/ToolPage.asp?tid=5136#) | No change |
| Endevor | Software Change Manager (SCM) | [Approved](http://www.va.gov/TRM/ToolPage.asp?tid=9481#) |  No change |
| Microsoft | Team Foundation Server (TFS) | [Approved](http://www.va.gov/TRM/ToolPage.asp?tid=5668#) | Divest |
| Microsoft | Visual Source Safe (VSS) | [Prohibited](http://www.va.gov/TRM/ToolPage.asp?tid=5669) | No change |

Note: for all "Divest"

### IBM BlueMix: The Next-Gen Cloud-based DevOps with fully integrated Github Enterprise
* [IBM BlueMix - Github Entertprise Service](https://developer.ibm.com/bluemix/2016/02/22/github-enterprise-service)
* [IBM BlueMix - Github Enterprise Integration](https://developer.ibm.com/bluemix/2016/06/16/github-enterprise-hosted-service-on-bluemix)
* [IBM BlueMix](https://github.com/IBM-Bluemix)
* [Github Enterprise is coming to IBM BlueMix](http://www.infoworld.com/article/3036123/application-development/github-enterprise-is-coming-to-ibms-bluemix.html)
* [IBM BlueMix - Github](https://hub.jazz.net/docs/git)
* [IBM BlueMix-Github features](https://hub.jazz.net/features)


## Mission-critical Software
* Currently none of VA VISTA's code is maintained in any form of VCS system. This represents 35+ years of code spanning 180 applications, and includes over 2 million lines of code in over 35 thousand files. __All VISTA code and files must be immediately migrated and managed on Github.__
* Currently all CPRS code is maintained in the Perforce VCS system (20+ years; million of lines) . All CPRS code should be migrated to Github.
* This will allow all future development of VISTA and CPRS to be done in parallel with the same code repository and VCS tool.



