# VA Enterprise Systems Source Code Control: What is the Strategy?


## The Issue
* VA's core enterprise system - VISTA - is open-source and large. It is in the millions lines of lines of code and tens of thousands of files. However, VISTA is NOT under source code control.  
* Software development and updates to VISTA therefore relies on on manual processes and legacy MUMPS-specific tools, making evolution challenging, slow, error prone, and technically incompatible with VA's development partners outside VA.
* VA urgently needs an authoritative, industry-standard, open-source source code control system for VISTA to allow for its evolution.
* 
## An imperative to collaborate
* VA has migrated from innersourcing development of VISTA within VA, to relying on contractors developing VISTA outside VA.
* VA's VISTA source code must therefore be accessible on common, open-source, industry-standard source control to allow for its evolution with VA's partners outside VA which are also using this same source control technology.
* Currently the industry-standard source control system used by most U.S. Government agencies to collaborate with their industry partners is Github.

## Background
* All VA software tools are reviewed and listed in the VA Technical Reference Model (TRM), VA's software and tools catalog.
* The [TRM Categorization Framework](http://www.va.gov/TRM/CategorizationHelpPage.asp) does not have any category specific for source code version control.
* Source code version control is subsumed under the broader [Software Change and Configuration Management Tools](http://www.va.gov/TRM/searchpage.asp?catId=46&catname=Software%20Change%20and%20Configuration%20Management%20Tools) category. This includes Configuration Management, Project Management, File Repositories, and proprietary development environments.
* The subset of TRM Software Change and Configuration Management tools specific to source code version control are the following:


## VA TRM: Source Code Version Control

TRM Name	|	OSS	|	Purpose	|	Decision	|	TRM Link	|	Analysis
---	|	---	|	---	|	---	|	---	|	---	
Git	|	YES	|	DVCS	|	Unapproved	|	[6396](http://www.va.gov/TRM/ToolPage.asp?tid=6396)	|	An enterprise license has already been acquired for a comparable technology (?RTC)
GitHub Desktop	|	YES	|	DVCS	|	Unapproved	|	[9452](http://www.va.gov/TRM/ToolPage.asp?tid=9452)	|	An enterprise license has already been acquired for a comparable technology. (?RTC)
Github Enterprise	|	YES	|	DVCS	|	Unapproved	|	[9533](http://www.va.gov/TRM/ToolPage.asp?tid=9533)	|	An enterprise license has already been acquired for a comparable technology.(?RTC)
GitLab	|	YES	|	DVCS	|	Unapproved	|	[9580](http://www.va.gov/TRM/ToolPage.asp?tid=9580)	|	An enterprise license has already been acquired for a comparable technology.(?RTC)
GitLab Enterprise	|	YES	|	DVCS	|	Unapproved	|	[9463](http://www.va.gov/TRM/ToolPage.asp?tid=9463)	|	An enterprise license has already been acquired for a comparable technology.(?RTC)
Subversion	|	YES	|	SVCS	|	Prohibited	|	[6573](http://www.va.gov/TRM/ToolPage.asp?tid=6573)	|	An enterprise license has already been acquired for a comparable technology.(?RTC)
CVS	|	YES	|	SVCS	|	Prohibited	|	[194](http://www.va.gov/TRM/ToolPage.asp?tid=194)	|	Does not support atomic commits of changes to versioned objects.
Perforce	|	NO	|	RCS	|	Prohibited	|	[268](http://www.va.gov/TRM/ToolPage.asp?tid=268)	|	An enterprise license has already been acquired for a comparable technology.(?RTC)
Rational Team Concert (RTC) |	NO	|	Dev	|	Approved with Constraints	|	[5085](http://www.va.gov/TRM/ToolPage.asp?tid=5085)	|	IBM Jazz development/delivery environment. Note: While IBM still supports RTC for its external customers, it does not use RTC internally for code management. IBM has migrated all their source code to Github Enterprise. IBM's new cloud-based software platform called IBM Bluemix is also all Github-based.


## References:
* Why Google Stores Billions of Lines of Code in a Single Repository:  http://cacm.acm.org/magazines/2016/7/204032-why-google-stores-billions-of-lines-of-code-in-a-single-repository/fulltext
* IBM is world's largest user of Github: https://www.blueboxcloud.com/insight/blog-article/github-ibm-com-running-on-blue-box
* VA ProPath and VIP: Recommend use of legacy tools instead of Github?:  https://www.osehra.org/sites/default/files/VIP_Guide_1_0_v14.pdf


## Abbreviations
Abbreviation	|	Description
---	|	---
OSS | Open-source software
Dev	|	software development platform (proprietary)
RCS	|	revision control system
DVCS	|	distributed version control and source code management system
SVCS	|	software version control system
Git	|	open source distributed version control and source code management system


## Issues
* VA needs a single, authoritative, industry-standard, open-source software source-control system for all software.
* The TRM does not currently list any of the current industry-standard source control systems as approved (all the git-based).
* See [Issue #1](https://github.com/va-projects/best-practices/issues/1): Update TRM to industry best-practices
