# VA Software Version Control Systems (VCS):  Current and Recommended

The VA Technical Reference Model (TRM) is a catalog of software products assessed for use in VA (ranging from approved, approved with constraints, deprecated, divest, and prohibited).  

## TRM Products with VCS capability
The folllowing is a list of products which include source code VCS capability (either as a core feature, or a component of its functionality), and recommendation for VIP in order to meet compliance with the U.S. Federal software management directives.

| Manufacter | Product  | Current Status | VIP Recommendation |
|:------- |:------- |:------:|:-------:|
| OSS | Git Server | [Divest](http://www.va.gov/TRM/ToolPage.asp?tid=6396) | Yes |
| GitHub | GitHub Enterprise | [Divest](http://www.va.gov/TRM/ToolPage.asp?tid=9533#) | Yes |
| GitLab | GitLab CE | [Unapproved](http://www.va.gov/TRM/ToolPage.asp?tid=9580) | No |
| GitLab | GitLab EE | [Divest](http://www.va.gov/TRM/ToolPage.asp?tid=9463#) | No |
| Apache | Subversion | [Prohibited](http://www.va.gov/TRM/ToolPage.asp?tid=6573) | No |
| OSS | CVS | [Prohibited](http://www.va.gov/TRM/ToolPage.asp?tid=194) | No |
| Perforce | Helix versioning engine | [Prohibited](http://www.va.gov/TRM/ToolPage.asp?tid=268) | Divest | 
| IBM | Clear Case MultiSite | [Divest (Read-only)](http://www.va.gov/TRM/ToolPage.asp?tid=39#) | Same |
| IBM | Rational Team Concert (RTC) | [Approved](http://www.va.gov/TRM/ToolPage.asp?tid=5085#) | Approve with constraints: Use only for project planning and management; For VCS use Git |
| Serena | Dimensions CM | [Divest](http://www.va.gov/TRM/ToolPage.asp?tid=5136#) | No change |
| Endevor | Software Change Manager (SCM) | [Approved](http://www.va.gov/TRM/ToolPage.asp?tid=9481#) | Divest |
| Microsoft | Team Foundation Server (TFS) | [Approved](http://www.va.gov/TRM/ToolPage.asp?tid=5668#) | Divest | 
| Microsoft | Visual Source Safe (VSS) | [Prohibited](http://www.va.gov/TRM/ToolPage.asp?tid=5669) | Same |


__Mission-critical VIP Recommendations:__
* Currently none of VISTA's MUMPS code is maintained in any VCS system (over 2 million lines / 35 thousand files). All VISTA M-code and files should be migrated and version controlled on Git.
* Currently all CPRS code is maintained in the Perforce VCS system (20+ years; million of lines) . This should be migrated to Git to provide VA enterprise standard approach to VCS.






