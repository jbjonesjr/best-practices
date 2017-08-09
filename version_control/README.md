# VA Code Version Control Systems

## Definition and justification
Version Control Systems (VCS) allow you to manage the changes over time for a file or set of files, and supports operations to manage that change over time. They will also let you revert to a previous version of the file from a specific point in time. It also manages metadata about the files and revisions, including who is making the changes and when. You can use VCS along with other tools to enforce business rules (formatting, file contents, collision detection) to ensure the quality of the content.

Using a modern version control tool can improve software quality and decrease risk.

## TRM Products with VCS capability
The VA Technical Reference Model (TRM) is a catalog of software products with associated recommendations.  These recommendations range include:
* approved (unrestricted use)
* approved with constraints (limited use)
* deprecated / divest (time-limited use)
* unapproved /  prohibited (no use permitted)

The following is a list of products in the TRM which have some sort of code version-control system  (VCS) capability. Source code version control may be a core feature (Perforce, CVS, or Github and all Git-related technologies) or may be a non-core, plug-in feature which is replaceable with any other core VCS system (i.e. the Microsoft and IBM's project management tools have replaceable, plug-in VCS).

| Manufacturer | Product | TRM Status |
|:------- |:------- |:------:|
| OSS | Git Server | [Divest](http://www.va.gov/TRM/ToolPage.asp?tid=6396) |
| GitHub | GitHub Enterprise | [Divest](http://www.va.gov/TRM/ToolPage.asp?tid=9533#) |
| GitLab | GitLab CE | [Unapproved](http://www.va.gov/TRM/ToolPage.asp?tid=9580) |
| GitLab | GitLab Enterprise | [Divest](http://www.va.gov/TRM/ToolPage.asp?tid=9463#) |
| Apache | Subversion | [Prohibited](http://www.va.gov/TRM/ToolPage.asp?tid=6573) |
| OSS | CVS | [Prohibited](http://www.va.gov/TRM/ToolPage.asp?tid=194) |
| Perforce | Helix versioning engine | [Prohibited](http://www.va.gov/TRM/ToolPage.asp?tid=268) |  
| IBM | Clear Case MultiSite | [Divest (Read-only)](http://www.va.gov/TRM/ToolPage.asp?tid=39#) |  
| IBM | Rational Team Concert (RTC) | [Approved](http://www.va.gov/TRM/ToolPage.asp?tid=5085#) |
| Serena | Dimensions CM | [Divest](http://www.va.gov/TRM/ToolPage.asp?tid=5136#) |
| Endevor | Software Change Manager (SCM) | [Approved](http://www.va.gov/TRM/ToolPage.asp?tid=9481#) |  
| Microsoft | Team Foundation Server (TFS) | [Approved](http://www.va.gov/TRM/ToolPage.asp?tid=5668#) |
| Microsoft | Visual Source Safe (VSS) | [Prohibited](http://www.va.gov/TRM/ToolPage.asp?tid=5669) |

## Comparing the various VCS
This repository documents the TRM-acknowledged VCS tools, and provides details on their use and design.

It summarizes this research into a [comparison](./comparison.md) document and a set of  [recommendations](./recommendations.md) for amending the TRM going forward.

These conclusions were based on defined [criteria](./criteria.md):
* reviewing [historical performance](./historical_context.md)
* developer tooling [support](./ide-support.md)
* [ease of migration](migration_details.md) (in support of future advancements)
* integration with the [Open Source Software](./oss-integration.md) community & the suite of [Rational Team Concert](./rtc-integration.md) tools
