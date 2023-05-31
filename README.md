# misp2qradar
Pulls IoCs from MISP and adds them to reference sets in QRadar.

Based on Pyhton-Scripts provided by @syloktools and @derinsiderx which did not fully fit my needs. I needed a bit more flexiblity.

You can use misp2qradar.py as follows:
```
misp2qradar.py "[REFERENCE-SET] "[MISP-TYPE]" "[MISP-THREAT-LEVEL]" "[MISP-CATEGORY]"
```
* [REFERENCE-SET] - Name of the QRadar reference set
* [MISP-TYPE] - e.g. domain, url, sha256, ...
* [MISP-THREAT-LEVEL] - e.g. 1,2,3,4
* [MISP-CATEGORY] - e.g. "Network Activity"

For more details take a look at https://www.misp-project.org/openapi/
