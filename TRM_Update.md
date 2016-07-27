#### TRM Update Request
* http://trm.oit.va.gov/TRMRequestForm.asp
* Access requires VA Intranet (Citrix)
* May attach files (Word Excel PP  PDF) - max 7Mb


#### TRM Categorization Framework:
* http://www.va.gov/TRM/CategorizationHelpPage.asp
* Does not include Source Code Version Control as a category


# TRM Software Change and Configuration Management Tools

Link:   http://www.va.gov/TRM/searchpage.asp?catId=46&catname=Software%20Change%20and%20Configuration%20Management%20Tools

TRM Name	|	FOSS	|	Purpose	|	Decision	|	TRM TID	|	Analysis	|	TRM Link
---	|	---	|	---	|	---	|	---	|	---	|	---
Apache Subversion	|	Y	|	SVCS	|	P	|	6573	|	An enterprise license has already been acquired for a comparable technology.	|	http://www.va.gov/TRM/ToolPage.asp?tid=6573
Apache Zookeeper	|	Y	|	Config	|	AwC	|	9590	|		|	http://www.va.gov/TRM/ToolPage.asp?tid=9590
Archiva	|	Y	|	Repository	|	P	|	7727	|		|	http://www.va.gov/TRM/ToolPage.asp?tid=7727
CA Agile Central	|	?	|	PM	|	AwC	|	9201	|	Enterprise licenses have already been acquired for comparable technologies.	|	http://www.va.gov/TRM/ToolPage.asp?tid=9201
CVS	|	Y	|	SVCS	|	P	|	194	|	CVS does not support atomic commits of changes to versioned objects.	|	http://www.va.gov/TRM/ToolPage.asp?tid=194
Dimensions CM	|	N	|	??	|	U	|	5136	|	The technology is proprietary and may lead to vendor lock-in.	|	http://www.va.gov/TRM/ToolPage.asp?tid=5136
eGit	|	Y	|	DVCS	|	U	|	6395	|	plugin of the Git  for the Eclipse IDE	|	http://www.va.gov/TRM/ToolPage.asp?tid=6395
Endevor Quick Edit	|	N	|	??	|	AwC	|	9480	|	This technology is only compatible with the z/OS mainframe and is not portable.	|	http://www.va.gov/TRM/ToolPage.asp?tid=9480
Endevor Software Change Manager (SCM)	|	N	|	??	|	AwC	|	9481	|	This technology is only compatible with the z/OS mainframe and is not portable.	|	http://www.va.gov/TRM/ToolPage.asp?tid=9481
Fisheye	|	N	|	??	|	U	|	6541	|	enables developers to browse and search software source code	|	http://www.va.gov/TRM/ToolPage.asp?tid=6541
Git	|	Y	|	DVCS	|	U	|	6396	|	An enterprise license has already been acquired for a comparable technology.	|	http://www.va.gov/TRM/ToolPage.asp?tid=6396
GitHub Desktop	|	Y	|	DVCS	|	U	|	9452	|	An enterprise license has already been acquired for a comparable technology.	|	http://www.va.gov/TRM/ToolPage.asp?tid=9452
Github Enterprise	|	Y	|	DVCS	|	U	|	9533	|	An enterprise license has already been acquired for a comparable technology.	|	http://www.va.gov/TRM/ToolPage.asp?tid=9533
GitLab	|	Y	|	DVCS	|	U	|	9580	|	An enterprise license has already been acquired for a comparable technology.	|	http://www.va.gov/TRM/ToolPage.asp?tid=9580
GitLab Enterprise Edition (EE)	|	Y	|	DVCS	|	U	|	9463	|	An enterprise license has already been acquired for a comparable technology.	|	http://www.va.gov/TRM/ToolPage.asp?tid=9463
MetaHelper	|	N	|	Config	|	P	|	5120	|	manages the addition, subtraction, and merging of system configuration change-sets	|	http://www.va.gov/TRM/ToolPage.asp?tid=5120
Microsoft BitLocker Administration and Monitoring (MBAM)	|	N	|	security	|	AwC	|	8873	|	simplified administrative interface for BitLocker Drive Encryption	|	http://www.va.gov/TRM/ToolPage.asp?tid=8873
Nexus	|	Y	|	Repository	|	AwC	|	6411	|	An enterprise license has already been acquired for a comparable technology.	|	http://www.va.gov/TRM/ToolPage.asp?tid=6411
Perforce	|	N	|	RCS	|	P	|	268	|	Rational ClearCase with Multisite and Rational Team Concert are the approved technologies for software configuration management.	|	http://www.va.gov/TRM/ToolPage.asp?tid=268
Rational ClearCase with MultiSite	|	N	|	Config	|	AwC	|	39	|	Rational ClearCase is being deprecated in favor of Rational Team Concert	|	http://www.va.gov/TRM/ToolPage.asp?tid=39
Rational Publishing Engine	|	N	|	Doc Gen	|	A	|	6284	|	automates the generation of documents in different formats (PDF, HTML, Word)	|	http://www.va.gov/TRM/ToolPage.asp?tid=6284
Rational Team Concert (RTC)	|	N	|	Dev	|	AwC	|	5085	|	software development/delivery environment based on IBM Jazz platform	|	http://www.va.gov/TRM/ToolPage.asp?tid=5085
Salt	|	N	|	Config	|	U	|	9466	|	configuration management system, that maintains remote nodes in defined states	|	http://www.va.gov/TRM/ToolPage.asp?tid=9466
Supermicro Update Manager (SUM)	|	Y	|	OS Tool	|	AwC	|	9172	|	allows users to make local or remote edits to the BIOS and BMC/IPMI firmware	|	http://www.va.gov/TRM/ToolPage.asp?tid=9172
Team Foundation Server (TFS)	|	N	|	Dev	|	AwC	|	5668	|	Microsoft source control, data collection, reporting, and project tracking	|	http://www.va.gov/TRM/ToolPage.asp?tid=5668
Tortoise SVN	|	Y	|	RCS	|	AwC	|	6678	|	Apache Subversion (SVN) client, implemented as a Microsoft Windows shell extension	|	http://www.va.gov/TRM/ToolPage.asp?tid=6678
Visual SourceSafe (VSS)	|	N	|	RCS	|	P	|	5669	|	Microsoft  file-level version control	|	http://www.va.gov/TRM/ToolPage.asp?tid=5669


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
Dev	|	software development platform
RCS	|	revision control system
DVCS	|	distributed version control and source code management system
SVCS	|	software version control system
Config	|	configuration information manager
Repository	|	Non-source code control repository
PM	|	Project Management
z/OS	|	z/OS is a 64-bit operating system for IBM mainframe computers.
Git	|	open source distributed version control and source code management system
VIP policy	|	This product is no longer approved for information technology (IT) projects that are or will be mandated to follow standardized processes and tools governing IT activity critical to VA`s implementation of the Veteran-focused Integration Process (VIP). Projects to be governed by VIP are required to transition to the standardized tools by October 1, 2016. Please refer to the CIO memo dated January 4, 2016 that mandated specific criteria for being designated as VIP projects and the accompanying January 19, 2016 memo regarding OI&T project management and software/systems development standardized tools and repositories (see Reference tab).







### TRM Project Management Tools:
http://www.va.gov/TRM/SearchPage.asp?catid=123&catName=Project%20Management

### TRM Defect Tracking Tools:
http://www.va.gov/TRM/SearchPage.asp?catid=39&catName=Defect%20Tracking%20Tools


### References:
Why Google Stores Billions of Lines of Code in a Single Repository
http://cacm.acm.org/magazines/2016/7/204032-why-google-stores-billions-of-lines-of-code-in-a-single-repository/fulltext

IBM:
https://www.blueboxcloud.com/insight/blog-article/github-ibm-com-running-on-blue-box

VIP:  requires RTC
https://www.osehra.org/sites/default/files/VIP_Guide_1_0_v14.pdf





