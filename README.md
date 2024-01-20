**This repository contains the Python analysis code used for "Ticket to Walk: How Jaywalking Enforcement Impacts Washingtonians," a research report that I authored for Transportation Choices Coalition.**

Please contact me at [ethanchenbell@gmail.com](mailto:ethanchenbell@gmail.com) if you have any questions regarding this code.

### Attribution:
This code is freely available for reuse as described in the MIT License included in this repository. If using this code in a publication, I encourage you to provide the following citations:
* **Report**: Campbell, E.C., "Ticket to walk: How jaywalking enforcement impacts Washingtonians," Transportation Choices Coalition (January 2024).
* **Code archive**: Campbell, E.C., "Analysis code for 'Ticket to walk: How jaywalking enforcement impacts Washingtonians,'" GitHub (January 19, 2024; accessed \[date]), [https://github.com/ethan-campbell/TCC_report](https://github.com/ethan-campbell/TCC_report).

### Description:
* The Jupyter notebook `Washington_jaywalking_enforcement_analyses.ipynb` carries out processing, analysis, and visualization of the police stop and citation data, as described in the report (see in particular the methodology in Appendix B).
* The Python script `public_records_download.py` was used to download batches of public records files served on GovQA public records portals by various municipalities, and contains enough documentation to hopefully be broadly useful to others.
* The Jupyter notebook `SNO911_CAD_log_parser.ipynb` was used to parse key data fields from computer-aided dispatch (CAD) logs provided in PDF format from SNO911.

### Note on underlying data:
As mentioned in the report's "Data and code availability" section, to protect the confidentiality of police stop subjects and to comply with Washington State Administrative Office of the Courts’ data dissemination agreement, we are not publicly releasing the records of pedestrian stops or citations referenced in the report. Many of these records, however, may be obtained by public records request to the relevant agency, and I would be happy to assist interested parties in formulating such a request.
