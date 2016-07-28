# VA Enterprise Source Code Control: What is the Strategy?


## The Issue
* VA's enterprise systems are open-source and comprised of millions of lines of code, which are not currently under source control.
* The VA does not currently approve or use any of the current industry-standard source control systems to support these large open-source sytsems. 
* VA needs a single, authoritative, industry-standard, open-source source code control system for all VA open-source software.

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
*  VA VIP: Promotes use of legacy tools instead of Github:  https://www.osehra.org/sites/default/files/VIP_Guide_1_0_v14.pdf


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
