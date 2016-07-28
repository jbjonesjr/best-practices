# VA Software Source Control: What is the Strategy?


# The Issue
* VA needs a single, authoritative, industry-standard, open-source software source version control system for all VA software.
* The VA does not currently use any of the current industry-standard source control systems. 

# Background
* All VA software is reviewed and listed in the VA Technical Reference Model (TRM), VA's software and tools catalog.
* The [TRM Categorization Framework](http://www.va.gov/TRM/CategorizationHelpPage.asp) does not have any TRM category specific for software source control.
* Source code control is subsumed under the TRM Category [Software Change and Configuration Management Tools](http://www.va.gov/TRM/searchpage.asp?catId=46&catname=Software%20Change%20and%20Configuration%20Management%20Tools), which includes also Configuration Management  (Config),  Project Management  (PM), File Repository Management (Repo), and Development Environments (Dev). 
* The following lists only the TRM products specific to software source control.

TRM Name	|	FOSS	|	Purpose	|	Decision	|	TRM Link	|	Analysis
---	|	---	|	---	|	---	|	---	|	---	
Git	|	Yes	|	DVCS	|	U	|	[6396](http://www.va.gov/TRM/ToolPage.asp?tid=6396)	|	An enterprise license has already been acquired for a comparable technology
GitHub Desktop	|	Yes	|	DVCS	|	U	|	[9452](http://www.va.gov/TRM/ToolPage.asp?tid=9452)	|	An enterprise license has already been acquired for a comparable technology.
Github Enterprise	|	Yes	|	DVCS	|	U	|	[9533](http://www.va.gov/TRM/ToolPage.asp?tid=9533)	|	An enterprise license has already been acquired for a comparable technology.
GitLab	|	Yes	|	DVCS	|	U	|	[9580](http://www.va.gov/TRM/ToolPage.asp?tid=9580)	|	An enterprise license has already been acquired for a comparable technology.
GitLab Enterprise	|	Yes	|	DVCS	|	U	|	[9463](http://www.va.gov/TRM/ToolPage.asp?tid=9463)	|	An enterprise license has already been acquired for a comparable technology.
Subversion	|	Yes	|	SVCS	|	P	|	[6573](http://www.va.gov/TRM/ToolPage.asp?tid=6573)	|	An enterprise license has already been acquired for a comparable technology.
CVS	|	Yes	|	SVCS	|	P	|	[194](http://www.va.gov/TRM/ToolPage.asp?tid=194)	|	Does not support atomic commits of changes to versioned objects.
Perforce	|	No	|	RCS	|	P	|	[268](http://www.va.gov/TRM/ToolPage.asp?tid=268)	|	An enterprise license has already been acquired for a comparable technology.
Rational Team Concert|	No	|	Dev	|	AwC	|	[5085](http://www.va.gov/TRM/ToolPage.asp?tid=5085)	|	Proprietary  IBM Jazz software development/delivery environment



## Decisions

Decision	|	Description
---	|	---
A	|	Approved
AwC	|	Approved with Constraints
D	|	Divest
U	|	Unapproved
P	|	Prohibited


## Functionality

Purpose	|	Description
---	|	---
Dev	|	software development platform (proprietary)
RCS	|	revision control system
DVCS	|	distributed version control and source code management system
SVCS	|	software version control system
Git	|	open source distributed version control and source code management system



# References:
* Why Google Stores Billions of Lines of Code in a Single Repository:  http://cacm.acm.org/magazines/2016/7/204032-why-google-stores-billions-of-lines-of-code-in-a-single-repository/fulltext
* IBM is world's largest user of Github: https://www.blueboxcloud.com/insight/blog-article/github-ibm-com-running-on-blue-box
*  VA VIP: This policy requires legacy tools instead of Github:  https://www.osehra.org/sites/default/files/VIP_Guide_1_0_v14.pdf


# Issues
* VA needs a single, authoritative, industry-standard, open-source software source-control system for all software.
* The TRM does not currently list any of the current industry-standard source control systems as approved (all the git-based).
* See [Issue #1](https://github.com/va-projects/best-practices/issues/1): Update TRM to industry best-practices
