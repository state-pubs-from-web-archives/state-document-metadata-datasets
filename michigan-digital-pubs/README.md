## Michigan Documents MARC Records Dataset
This folder contains the Metadata datasets extracted from the [Michigan State OAI-PMH](https://cdm16110.contentdm.oclc.org/oai/oai.php). It contains two different files.
1. michigan_new.dc.xml.gz : This file contains all the harvested dublin core metadata in XML format. We can easily extract these metadata into .csv format by using the script [dc_total.py script](https://github.com/state-pubs-from-web-archives/oaipmh-tools/blob/main/tools/dc_total.py)
2. michigan.jsonl.gz : This file also contains the harvested metadata but in jsonl format.

### Descriptive stats on the Michigan dublin core metadata.


| Element Name | Records with Element Instances | Percentage of Records with Element Instances | Unique data values in Element Instances | Mean Instances per record | Mode Instances per record | Frequency of Mode Instances per record | Entropy | Gini_coefficient |
| :---:   | :---: | :---: | :---:   | :---: | :---: | :---: | :---: | :---: |
| title | 4993 | 100.0% | 2286 | 1 | 1 | 88.98% | 0.825 | 0.584 |
| creator | 806 | 16.14% | 207 | 1 | 1 | 16.14% | 0.758 | 0.659 |
| contributor | 0 | 0% | 0 | 0 | 0 | 0% | 0 | None |
| publisher | 1561 | 31.26% | 425 | 1 | 1 | 31.26% | 0.725 | 0.673 |
| date | 3133 | 62.75% | 1322 | 2 | 3 | 49.67% | 0.773 | 0.767 |
| language | 1 | 0.02% | 1 | 1 | 1 | 0.02% | 0 | 0 |
| description | 4944 | 99.02% | 4291 | 1 | 1 | 92.37% | 0.937 | 0.180 |
| subject | 2821 | 56.5% | 373 | 3 | 4 | 47.43% | 0.462 | 0.915 |
| coverage | 2229 | 44.64% | 210 | 1 | 1 | 37.81% | 0.644 | 0.828 |
| source | 572 | 11.46% | 3 | 1 | 1 | 11.46% | 0.788 | 0.354 |
| relation | 0 | 0% | 0 | 0 | 0 | 0% | 0 | None |
| rights | 3035 | 60.79% | 33 | 1 | 1 | 48.23% | 0.593 | 0.811 |
| type | 2361 | 47.29% | 7 | 1 | 1 | 47.29% | 0.722 | 0.509 |
| format | 2368 | 47.43% | 5 | 1 | 1 | 47.43% | 0.401 | 0.666 |
| identifier | 4993 | 100.0% | 7421 | 2 | 3 | 47.37% | 0.988 | 0.210 |

	Table  : 1 Basic Stats for Michigan State Collection



				Total_records 		: 	5446
				Deleted_records 	: 	453
				Available_records 	:	4993

