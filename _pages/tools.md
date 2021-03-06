---
layout: page
title: Tools
permalink: /tools/
toc: true
---

## Software and Tools

Many open source and proprietary tools integrate MISP support (MISP format or API) in order to extend their tools
or MISP itself. A series of additional software are supported and handled by the [MISP project](https://www.github.com/MISP).
The additional software supported by the MISP project allow the community to rely on additional tools to support their day-to-day operations. The objective
is also to explore new ideas, concepts or functionality which can be integrated in MISP core software later on.

### Software within the MISP project


* [misp-modules](https://github.com/MISP/misp-modules) - Modules for expansion services in MISP
     * Passive Total - [doc](http://blog.passivetotal.org/misp-sharing-done-differently/).
     * CIRCL Passive DNS - a hover and expansion module to expand hostname and IP addresses with passive DNS information.
     * CIRCL Passive SSL - a hover and expansion module to expand IP addresses with the X.509 certificate seen.
     * EUPI API Support (Phishing Initiative project).
     * IPASN - a hover and expansion to get the BGP ASN of an IP address.
     * ASN History - a hover and expansion module to expand an AS number with the ASN description and its history.
     * CVE a hover module to give more information about a vulnerability (CVE).
* [misp-workbench](https://github.com/MISP/misp-workbench) - Tools to export data out of the MISP MySQL database and use and abuse them outside of this platform.
* [MISpego](https://github.com/MISP/MISPego) - Maltego Transform to put entities into MISP events.
* [MISP-maltego](https://github.com/MISP/MISP-maltego) - Set of Maltego transforms to inferface with a MISP instance.
* [PyMISP](https://github.com/CIRCL/PyMISP) - Python library using the MISP Rest API.
* [MISP-STIX-Converter](https://github.com/MISP/MISP-STIX-Converter) -  An utility repo to assist with converting between MISP and STIX formats.

For the additional software created by the MISP project, check our [MISP project organization](https://github.com/MISP/).

### Software or Services with MISP support

* [Viper](http://www.viper.li/) - is a binary management and analysis framework dedicated to malware and exploit researchers including a MISP module.
* [cve-search](https://github.com/cve-search) - a tool to perform local searches for known vulnerabilities include a [MISP plug-in](https://github.com/cve-search/Plugins/tree/master/plugins/plugins/MISP).
* [Cuckoo modified](https://github.com/spender-sandbox/cuckoo-modified) - heavily modified version of Cuckoo Sandbox including a [MISP reporting module](https://github.com/spender-sandbox/cuckoo-modified/blob/master/modules/reporting/misp.py) to put the information into a MISP instance.
* [Hybrid analysis](https://www.hybrid-analysis.com/) exports in MISP format.
* [Joe Sanbox](https://www.joesecurity.org/) outputs analysis in MISP format.
* [Loki - Simple IOC Scanner](https://github.com/Neo23x0/Loki) includes a MISP receiver.
* [MISP-Extractor](https://github.com/PidgeyL/MISP-Extractor) extracts information from MISP via the API and automate some tasks.
* [IntelMQ](https://github.com/certtools/intelmq) support MISP to retrieve events and update tags.
* [misp-to-autofocus](https://github.com/PaloAltoNetworks/misp-to-autofocus) - script for pulling events from a MISP database and converting them to Autofocus queries.
* [otx_misp](https://github.com/gcrahay/otx_misp/) imports Alienvault OTX pulses to a MISP instance.
* [FireMISP](https://github.com/deralexxx/FireMISP) FireEye Alert json files to MISP Malware information sharing platform (Alpha).
* [cti-toolkit](https://github.com/certau/cti-toolkit)  CERT Australia Cyber Threat Intelligence (CTI) Toolkit includes a transform to MISP from STIX.
* [MISP-IOC-Validator](https://github.com/tom8941/MISP-IOC-Validator/) validates the format of the different IOC from MISP and to remove false positive by comparing these IOC to existing known false positive.
* [TheHive](https://thehive-project.org/) A 3-in-1 Security Incident Response Platform has an extensive MISP support.
