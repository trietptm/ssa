# SSA - Security System Analyzer 2.0 #

SSA (Security System Analyzer) is free non-intrusive OVAL, FDCC, XCCDF and SCAP scanner. It provides security testers, auditors with an advanced overview of the security policy level applied.

## Features ##

  * Version of products installed using CPE enumeration (see http://cpe.mitre.org).
  * Identify vulnerabilities and discrepancies using the power of OVAL interpreter and his huge database of definitions (see http://oval.mitre.org).
  * Perform Compliance and Security Checks using the XCCDF - The eXtensible Configuration Checklist Description Format (see http://scap.nist.gov/specifications/xccdf/)
  * Qualifying the vulnerabilities using CVSS v2.0 scoring system (see http://www.first.org/cvss).
  * And many new features.

## Screenshots ##

![![](http://lh6.ggpht.com/_bJgatfqy1SQ/TPo1Fnfd3xI/AAAAAAAABCo/yLoi2HAytA0/s128/ssa1.png)](http://lh6.ggpht.com/_bJgatfqy1SQ/TPo1Fnfd3xI/AAAAAAAABCo/yLoi2HAytA0/s640/ssa1.png)![![](http://lh5.ggpht.com/_bJgatfqy1SQ/TPo1F3v3hCI/AAAAAAAABCs/Me7TlReW8vc/s128/ssa2.png)](http://lh5.ggpht.com/_bJgatfqy1SQ/TPo1F3v3hCI/AAAAAAAABCs/Me7TlReW8vc/s640/ssa2.png)![![](http://lh6.ggpht.com/_bJgatfqy1SQ/TPo1F01MLTI/AAAAAAAABCw/7hR4aJJHRas/s128/ssa3.png)](http://lh6.ggpht.com/_bJgatfqy1SQ/TPo1F01MLTI/AAAAAAAABCw/7hR4aJJHRas/s640/ssa3.png)



## News ##
### New Coming version ###

A new coming release will be in the wild very soon (after the Blackhat US Vegas). I decided to update the engine with the support of the latest OVAL, SCAP and XCCDF. Moreover, SSA is now working on OS X. Great news, i finally added PCI v2.0 Security Checks for Apple :)
Many other enhancements to be expected.
Stay Tuned.


### December 2010 : Release of Beta 002 ###

  * Added the support of XCCDF 1.1.4 (http://scap.nist.gov/specifications/xccdf/)
  * Display Pass / Fail testcase
  * Associate Testcase to CCE reference
  * Added the following Policies and Baselines
    1. FDCC/SCAP FISMA NIST 800-53 with 5 baselines ( IE7, WinXP, WinVista, Vista Firewall, XP Firewall)
    1. STIG/SCAP DISA with 2 baselines (Windows XP Security Checklist v6 [r1](https://code.google.com/p/ssa/source/detail?r=1).19 and Windows Vista Security Checkist v6 [r1](https://code.google.com/p/ssa/source/detail?r=1).19)
    1. USGCB/SCAP USGCB with 2 baselines (IE8 and Windows 7 X86)
  * Added export to CSV
  * Added new directory for logs
  * Added the ability to maximize Windows
  * Added a new community page http://teambox.com/public/ssa-v2-beta
  * Fixed many bugs

### November 2010 : Release of Beta 001 ###

  * New UI
  * New Correlation engine
  * Integrated XML parser
  * Integrated HTML viewer
  * Compliant to OVAL interpreter 5.8.2
  * Load,verify and consume OVAL Compliance, Vulnerability and Inventory definitions
  * Enumerate findings (True states)
  * Support of CVE and CPE (http://cve.mitre.org and http://cpe.mitre.org)
  * List Results Stats (Global scanned definitions & True reported definitions)
  * View OVAL HTML results into UI

SSA is developed and maintained by Nabil OUCHN (http://fr.linkedin.com/in/ouchn)