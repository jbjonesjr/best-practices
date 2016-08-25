# VA Software Version Control Systems:  Current and Recommended

The VA Technical Reference Model (TRM) is a catalog of software products with associated assessments.  These assessments range from: 
* approved (unrestricted use)
* approved with constraints (limited use)
* deprecated / divest (time-limited use) 
* unapproved /  prohibited (no use permitted)

## TRM Products with VCS capability
The folllowing is a list of products in the TRM which have code version-control system  (VCS) capability.

Source code version control may be a core feature (Perforce, CVS, or Git and all Git-related technologies) or may be a non-core, plug-in feature which is replaceable with any other VCS system (i.e. the Microsoft and IBM's project management tools have replaceable, plug-in VCS).

Recommendation for VIP to meet compliance with the U.S. Federal software management directives are also added. 

| Manufacter | Product  | Current Status | VIP Recommendation |
|:------- |:------- |:------:|:-------:|
| OSS | Git Server | [Divest](http://www.va.gov/TRM/ToolPage.asp?tid=6396) | Approve (Includes all Git-related technologies below) |
| GitHub | GitHub Enterprise | [Divest](http://www.va.gov/TRM/ToolPage.asp?tid=9533#) | Approve |
| GitLab | GitLab CE | [Unapproved](http://www.va.gov/TRM/ToolPage.asp?tid=9580) | Approve |
| GitLab | GitLab Enterprise | [Divest](http://www.va.gov/TRM/ToolPage.asp?tid=9463#) | Approve |
| Apache | Subversion | [Prohibited](http://www.va.gov/TRM/ToolPage.asp?tid=6573) | No change |
| OSS | CVS | [Prohibited](http://www.va.gov/TRM/ToolPage.asp?tid=194) | No change |
| Perforce | Helix versioning engine | [Prohibited](http://www.va.gov/TRM/ToolPage.asp?tid=268) | Divest | 
| IBM | Clear Case MultiSite | [Divest (Read-only)](http://www.va.gov/TRM/ToolPage.asp?tid=39#) | No change |
| IBM | Rational Team Concert (RTC) | [Approved](http://www.va.gov/TRM/ToolPage.asp?tid=5085#) | Approve with constraints: Use only for project management; for all code managment and VCS use Git |
| Serena | Dimensions CM | [Divest](http://www.va.gov/TRM/ToolPage.asp?tid=5136#) | No change |
| Endevor | Software Change Manager (SCM) | [Approved](http://www.va.gov/TRM/ToolPage.asp?tid=9481#) | Divest |
| Microsoft | Team Foundation Server (TFS) | [Approved](http://www.va.gov/TRM/ToolPage.asp?tid=5668#) | Divest | 
| Microsoft | Visual Source Safe (VSS) | [Prohibited](http://www.va.gov/TRM/ToolPage.asp?tid=5669) | No change |


__Mission-critical VIP  Recommendations:__
* Currently none of VA VISTA's code is maintained in any form of VCS system. This represents 35+ years of code spanning 180 applications, and includes over 2 million lines of code in over 35 thousand files. __All VISTA code and files must be immediately migrated and managed on Git.__
* Currently all CPRS code is maintained in the Perforce VCS system (20+ years; million of lines) . All CPRS code should be migrated to the same common standard as VISTA VCS, such that all development can be done with the same open VCS technology.






