# M Style Guide

This project is about collecting examples of useful, practical, best practicees in M programming to build a foundation for a M Style Guide for VA VISTA programmers.   This collection will be incorporated into a living, community-driven  M Style Guide.

### To get started

1. Review the references below on M if needed.

2. Review some examples of [M Coding Standards - Do's and Don'ts](http://tinco.pair.com/bhaskar/gtm/doc/books/pg/UNIX_manual//apas01.html) from the GTm Programmer's Guide.  These would need be adapted to VA VISTA coding style.

3. Click on the [Issues tab](https://github.com/va-projects/M-StyleGuide/issues)  on the right to see a list of current list of  examples of 'good' and 'poor'  M coding style, the problems these create, and how they are avoided by best pratices in M coding style.

4. **Do you have any examples of good, poor, or questionable M coding style?**  Add it to the [Issues](https://github.com/va-projects/M-StyleGuide/issues)!



***
#### M[UMPS] References

**M Intro**
* [Overview of M Language](http://www.cs.uni.edu/~okane/source/MUMPS-MDH/MumpsTutorial.pdf). Kevin O'Kane, 2014.
* [M by Example](http://71.174.62.16/MDC/example/index.htm).  Ed de Moel, 2005.


**M Guides**
* [GT.M Programmers Guide](http://tinco.pair.com/bhaskar/gtm/doc/books/pg/UNIX_manual//index.html). Fidelity Information Systems, 2015.

**M Standards and Conventions**
* [VA SAC (PDF)](http://www.va.gov/TRM/files/SACC_2008.pdf). PDF version. Updated 2012.
* [VA SAC (web)](http://wiki.osehra.org/pages/viewpage.action?pageId=5866106). Web version. Updated 2011.
* [VA SAC (TRM)](http://www.va.gov/TRM/VAStandardPage.asp?tid=7404#). Link to VA TRM-approval of the SAC.
* [The Annotated M Standards](http://71.174.62.16/Demo/AnnoStd).Ed de Moel, 2005.
* [Discussion on M Programming Standards](https://groups.google.com/forum/#!topic/hardhats/XJSx5OuKMLE). Hardhats. 

**M Books**
* [M Programming Language](http://www.amazon.com/Mumps-Programming-Language-Kevin-OKane/dp/1438243383/ref=asap_bc?ie=UTF8), Kevin OKane, 2014 Edition. (128 pages).

**M Forums**
* [MUMPSTER](http://www.mumpster.org/)
* [Hardhats Forum](https://groups.google.com/forum/#!forum/hardhats)

***
**M Implementations**
* [GT.M](http://www.fisglobal.com/products-technologyplatforms-gtm) - Fidelity
* [Cache](http://www.intersystems.com/our-products/cache/cache-overview/) - Intersystems
* [GPL MUMPS](http://www.cs.uni.edu/~okane/) - Kevin OKane


***
**M History**

Beginning in 1966, the Mumps programming language (also referred to as M), was developed by Neil Pappalardo and others in Dr. Octo Barnett's lab at the Massachusetts General Hospital on a PDP-7. It was later ported to a number of machines including the PDP-11 and VAX.

Over the years, a number of implementations were developed. Many of these are now extinct or have evolved considerably from their original base. As the early implementations began to differ linguistically from on another, an effort to standardize Mumps began. This culminated in the 1977 ANSI standard for Mumps (X11.1-1977).

The standards effort continued until 1995 when the last standard was published (see: American National Standard for Information Systems - Programming Languages - M ANSI/MDC X11.1-1995). Since then, the standards writing Mumps Development Committee has disbanded and there have been no new standards developed. 

At present, the 1995 standard has lapsed in the United States but remains in effect as ISO (ISO/IEC 11756:1999). Also, as of 1995, there were related standards either published or in development for Mumps system interconnections (X11.2), a graphical kernel definition (X11.3), X-window binding (X11.4), TCP-IP binding (X11.5) and a windowing API (X11.6). These have also lapsed in the United Sates but some are still in effect at ISO.

***
**M Intro**

Mumps is a general purpose programming language that supports a novel, native, hierarchical database facility. The acronym stands for the Massachusetts General Hospital Utility Multi-programming System. It is widely used in financial and clinical applications and remains to this day the basis of the U.S. Veterans Administration's computerized medical record system VistA (Veterans Health Information Systems and Technology Architecture), the largest of its kind in the world.

As originally conceived, Mumps differs from other computer languages by providing a:

1. Hierarchical database facility. Mumps data sets are not only organized along traditional sequential and direct access methods, but also as trees whose data nodes can addressed as path descriptions in a manner which is easy for a novice programmer to master in a relatively short time;
2. Flexible and powerful string manipulation facilities. Mumps built-in string manipulation operators and functions provide programmers with access to efficient means to accomplish complex string manipulation and pattern matching operations.


Syntactically, Mumps is based on an earlier language named JOSS and has an appearance similar to early versions of BASIC which was also based on JOSS. Another feature of Mumps which distinguished it from other language environments at the time was its ability to run multiple applications and serve multiple users concurrently on very primitive computers.

