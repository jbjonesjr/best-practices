## VIP Version Control Criteria

The Veteran Affairs (VA) VIP program has standardized on a feature and bug tracking tool as well as a reporting tool in IBM Rational Team Concert. __However, it has not defined a Version Control System.__

This document attempts to layout the criteria (and justification) that VIP should factor when deciding on a Version Control System (VCS) of record.

### Ease of Use (including IDE-support)
The VCS shall make it easy for VIP users to interact with the tool of choice. This includes integration with all Modern Development Tools, as well as a web interface that can support viewing, editing, and commenting to make non-technical interaction simple.

### Ease of Adoption
The VCS shall make it easy for VIP users to become proficent with the tool. Extra consideration should be given to tools that have low training threshold and therefore a lower barrier to success. The tool should be optimized to create the best software product possible, as other tools, such as RTC for reporting, will be optimized for other purposes.

### Integration with other preferred tools, including RTC
The VCS shall make it easy for VIP to integrate it with other preferred tools (including RTC for CM and reporting), as well as other best of breed tools both present and future. Ensuring that VIP and the VA stay at the forefront of modern software development practices requires a framework that is able to keep pace with innovation to best leverage efficencies.

### Supports Inner Source workflows
The VCS shall allow VIP projects and staff to use the principles of [inner sourcing](http://www.oreilly.com/programming/free/getting-started-with-innersource.csp) to work on software. This means making software:
* easier to discover
* encourage the principles of reuse and collaboration
* clear and concise public discussion and documentation around design decisions and requirement strategy. 
 
The easiest effiencies for an organization to gain are by taking advantage of already developed (and approved) solutions to common problems via code and solution reuse.

### Minimize Vendor Lock-in
The VCS shall be chosen with an acknowledgement that the future will include new techniques and solutions to existing problems. As the system shall be able to keep pace with innovation, it should also use formats and proccesses that make it possible to own and manage a transition if so required at a later date.

### Uses Modern Deveopment Best Practices
The VCS shall support and encourage the modern software development lifecycle and associated tools and techniques that allows for the successful design, development, and maintenance of software. 

### Product Roadmap is strong and secure
The VCS shall be one that is considered healthy with a track record of innovation, maintenance, and system performance. While the VA can not know the health of a company in 3 months or 3 years, it can be aware of current trajectory when deciding what system to select for a multi-year tool.

### Interoperable with Federal CIO's [`Federal Source Code Policy`](sourcecode.cio.gov)
The VCS shall be on that can meet the requirements for code sharing as part of the Federal Source Code Policy. This means a system that can be accessible to the public, or operable directly with a preferred public solution (example: Internal Git Server, only accessible to VA-personnel, that can communicate with an external Git Server accessible to the public at large, such as GitHub.com)

### Support VA identity and authentication standards as defined by the Enterprise
The VCS shall be able to use existing identity, authentication, and authorization tools in use by the VA for the basis of its identity store. This ensures simplicity in user mangaement, as well as helping to reuse as many enterprise security controls as possible including two-factor authentication including smart cards and tokens.

### Support Enterprise requirements
The VCS shall be able to exist within the Enterprise, fulfilling typcical Enterprise requirements. This includes measurables such as performance and latency, infrastructure requirements such as high availability, disaster recovery, and monitoring compliance with the existing VA policies. The system should be able to demonstrate with reasonable effort the ability to receive an ATO and be approved by VA security. Support should be available to the system, both online and in person, to provide the VA with reasonable assurance their investment will be successful in acheiving their goals.

