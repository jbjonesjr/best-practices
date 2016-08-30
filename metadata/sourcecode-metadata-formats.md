# Metadata-driven source code discovery

Many different schemes and API generators exist for software (source code) cataloging and discovery:


## Key Options
* JSON-LD +  Hydra:  http://www.markus-lanthaler.com/hydra/
* About.yml:  https://github.com/18F/about_yml



## Metadata
* https://en.wikipedia.org/wiki/Metadata



### Metadata Schemes for Government Software

EUROPE:  ADMS.SW is a scheme used for integrating and cataloging government software across European nations. ADMS.SW builds on related schemas including DOAP, SPDX, ISO 19770-2, ADMS, and the Trove software map.
* ADMS.SW: https://joinup.ec.europa.eu/asset/adms_foss/description
* DOAP: https://github.com/edumbill/doap/wiki
* SPDX: http://spdx.org
* ISO-19770: http://www.iso.org/iso/catalogue_detail.htm?csnumber=53670
* ADMS: https://joinup.ec.europa.eu/asset/adms/description


* https://www.w3.org/TR/vocab-dcat/
* http://codeforamerica.org/api/#project-properties








(JSON-LD) Metadata for software discovery
* https://github.com/mozillascience/code-research-object/issues/15

NIH Software Discovery and Indexing
* http://www.softwarediscoveryindex.org/




https://github.com/WhiteHouse/source-code-policy/issues/117

https://github.com/codemeta/codemeta



### Minimal Information about Software

A common set of metadata fields are critical for useful indexing. If this effort only provides refined free-text searching capabilities, it will not be a major improvement over currently-available resources. It is necessary, therefore, to define a key set of minimal fields can that provide maximum value. At the workshop, the following fields were described as candidates for inclusion in this list:

* Persistent identifier (URL)
* Software title
* Software version
* Software license
* Links to code repository (URL)
* Human-readable synopsis
* Author names and affiliations
* Terms to describe software objectives or functions, and/or the following two bullets (controlled by an appropriate ontology)
* Formats for data inputs and outputs
* Platform, environment, and dependencies
* Associated funding and publications

### Use cases
* Developer: A developer registers their software, she is able to track and quantify all use of their software in scientific publications, through comprehensive and accurate citation of the index-associated identifier. With the ability to find similar types of software packages (e.g., other assembly programs), she would also identify benchmarking data sets, and other related software development efforts.
* User: An NIH funded researcher is seeking software for analysis. They are able to identify the most appropriate software relevant for their study on their data on their computer systems and objectives, and be provided with all information necessary to locate, obtain, and deploy the software.
* Publisher: A publisher can associate software with their publications during & for peer review and upon publication for citation. They can also pull & display metrics related to all the research objects surrounding the article, including software based on the software identifier.

### Metrics and milestones

It is critical to define metrics for this effort. These metrics should be evaluated both in absolute terms and in relative terms, monitoring the growth with time. These metrics are particularly significant because this is not the first effort to make biomedical software more accessible to researchers. This effort will face many of the same challenges faced by previous efforts and it is critical to closely monitor whether it is accomplishing its purpose. Specific metrics proposed for the initial effort included:

* Number of developers contributing software
* Number of software records created
* Software identifiers appearing in and extracted from publications
* Links from publications to software records
* Links between indexed software and other resources, people, and data
* Annotation of existing collections of software packages (e.g., Bioconductor)
* The number of interoperating resources, including repositories, aggregation resources, and user forums
* The use of the APIs to re-package the data for specific use cases
* The proportion of NIH-supported software tracked by the software discovery index



### Python Package metadata
http://legacy.python.org/dev/peps/pep-0301/#distutils-trove-classification

""
setup(
    name = "roundup",
    version = __version__,
    classifiers = [
        'Development Status :: 4 - Beta',
        'Environment :: Console',
        'Environment :: Web Environment',
        'Intended Audience :: End Users/Desktop',
        'Intended Audience :: Developers',
        'Intended Audience :: System Administrators',
        'License :: OSI Approved :: Python Software Foundation License',
        'Operating System :: MacOS :: MacOS X',
        'Operating System :: Microsoft :: Windows',
        'Operating System :: POSIX',
        'Programming Language :: Python',
        'Topic :: Communications :: Email',
        'Topic :: Office/Business',
        'Topic :: Software Development :: Bug Tracking',
    ],
    url = 'http://sourceforge.net/projects/roundup/',
    ...
)
""

