## Texas Documents MARC Records Dataset
This folder contains the Metadata datasets extracted from the [Texas State OAI-PMH](https://texashistory.unt.edu/explore/collections/TXPUB/oai/). It contains two different files.
1. txpub-2023-06-05.dc.xml.gz : This file contains all the harvested dublin core metadata in XML format. We can easily extract these metadata into .csv format by using the script [dc_total.py script](https://github.com/state-pubs-from-web-archives/oaipmh-tools/blob/main/tools/dc_total.py)
2. txpub-2023-06-05.jsonl.gz : This file also contains the harvested metadata but in jsonl format.

### Descriptive stats of the Texas dublin core metadata.


| Element Name | Records with Element Instances | Percentage of Records with Element Instances | Unique data values in Element Instances | Mean Instances per record | Mode Instances per record | Frequency of Mode Instances per record | Entropy | Gini_coefficient |
| :---:   | :---: | :---: | :---:   | :---: | :---: | :---: | :---: | :---: |
| title | 19373 | 100.0% | 26388 | 2 | 2 | 34.27% | 0.860 | 0.483 |
| creator | 19333 | 99.79% | 4928 | 1 | 1 | 68.41% | 0.793 | 0.759 |
| contributor | 7685 | 39.67% | 8087 | 3 | 1 | 19.02% | 0.861 | 0.651 |
| publisher | 19011 | 98.13% | 912 | 1 | 1 | 97.81% | 0.728 | 0.841 |
| date | 19316 | 99.71% | 4514 | 1 | 1 | 99.71% | 0.863 | 0.676 |
| language | 19373 | 100.0% | 6 | 1 | 1 | 98.89% | 0.067 | 0.825 |
| description | 19351 | 99.89% | 10875 | 1 | 1 | 99.89% | 0.863 | 0.432 |
| subject | 19373 | 100.0% | 17568 | 6 | 5 | 18.03% | 0.701 | 0.830 |
| coverage | 19373 | 100.0% | 4148 | 3 | 3 | 48.61% | 0.431 | 0.906 |
| source | 54 | 0.28% | 53 | 1 | 1 | 0.28% | 0.998 | 0.018 |
| relation | 972 | 5.02% | 915 | 1 | 1 | 3.86% | 0.867 | 0.475 |
| rights | 3116 | 16.08% | 143 | 1 | 2 | 13.51% | 0.502 | 0.908 |
| type | 19373 | 100.0% | 21 | 1 | 1 | 100.0% | 0.507 | 0.827 |
| format | 19373 | 100.0% | 4285 | 1 | 2 | 99.97% | 0.480 | 0.868 |
| identifier | 19373 | 100.0% | 49620 | 3 | 4 | 24.59% | 0.896 | 0.354 |

					Table  : 1 Basic Stats for Texas State Collection



				Total_records 		: 	19373
				Deleted_records 	: 	0
				Available_records 	:	19373

