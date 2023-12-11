## Michigan Documents MARC Records Datasets

This folder contains the Michigan State Documents in MARC. It contains three different files.
1. michigan-documents-2023-12-06.mrk.gz : This zip file contains all Michigan Documents metadata in MARC format. This files can be open with the help of MARC editor.

2. michigan-documents-2023-12-06.dc.xml.gz : This zip file contains the harvested Michigan Documents metadata in xml file which is extracted from the above MARC file. We can easily extract these metadata into .csv format by using the script [dc_total.py](https://github.com/state-pubs-from-web-archives/oaipmh-tools/blob/main/tools/dc_total.py) script.

3. michigan-documents-2023-12-06.jsonl : This file contains the same Michigan Documents metadata but in JSONL format.

### Descriptive stats on the Michigan Documents dublin core metadata.

| Element Name | Records with Element Instances | Percentage of Records with Element Instances | Unique data values in Element Instances | Mean Instances per record | Mode Instances per record | Frequency of Mode Instances per record | Entropy | Gini_coefficient |
| :---:   | :---: | :---: | :---:   | :---: | :---: | :---: | :---: | :---: |
| title | 39313 | 100.0% | 34781 | 1 | 1 | 100.0% | 0.983 | 0.112 |
| creator | 38815 | 98.73% | 12201 | 1 | 1 | 56.7% | 0.779 | 0.749 |
| contributor | 0 | 0% | 0 | 0 | 0 | 0% | 0 | None |
| publisher | 38557 | 98.08% | 11208 | 1 | 1 | 98.08% | 0.835 | 0.662 |
| date | 32689 | 83.15% | 2160 | 1 | 1 | 83.11% | 0.774 | 0.839 |
| language | 39313 | 100.0% | 9 | 1 | 1 | 100.0% | 0.008 | 0.888 |
| description | 36236 | 92.17% | 33536 | 2 | 2 | 30.62% | 0.761 | 0.578 |
| subject | 37806 | 96.17% | 12004 | 2 | 2 | 37.83% | 0.805 | 0.770 |
| coverage | 0 | 0% | 0 | 0 | 0 | 0% | 0 | None |
| source | 0 | 0% | 0 | 0 | 0 | 0% | 0 | None |
| relation | 4366 | 11.11% | 4030 | 1 | 1 | 8.24% | 0.946 | 0.263 |
| rights | 3 | 0.01% | 3 | 1 | 1 | 0.01% | 1 | 0 |
| type | 39313 | 100.0% | 84 | 1 | 1 | 95.88% | 0.113 | 0.978 |
| format | 1 | 0.0% | 1 | 2 | 2 | 0.0% | 0 | 0 |
| identifier | 2381 | 6.06% | 2670 | 1 | 1 | 4.89% | 0.992 | 0.063 |
       
					Table  : 1 Basic Stats for Michigan Documents MARC Records



				Total_records 		: 	39313
				Deleted_records 	: 	0
				Available_records 	:	39313

