# Higher Education Institutions in the United States of America Dataset

This repository contains a dataset of higher education institutions in the United States of America.
This dataset was compiled in response to a cybersecurity research of American higher education institutions' websites [1]. The data is being made publicly available to promote open science principles [2].

## Data

The data includes the following fields for each institution:

- Id: A unique identifier assigned to each institution.
- Region: The federal state in which the institution is located.
- Name: The full name of the institution.
- Category: Indicates whether the institution is public or private.
- Url: The website of the institution.

## Methodology

The dataset was obtained from the Higher Education Integrated Data System (IPEDS) website [3], which is administered by the National Center for Education Statistics (NCES). NCES serves as the primary federal entity for collecting and analyzing education-related data in the United States. The data was collected on February 2, 2023.

The initial list of institutions was derived from the IPEDS database using the following criteria: (1) US institutions only, (2) degree-granting institutions, primarily bachelor's or higher, and (3) industry classification, which includes: public 4 - year or above, private not-for-profit 4 years or more, private for-profit 4 years or more, public 2 years, private not-for-profit 2 years, private for-profit 2 years, public less than 2 years, private not-for-profit for-profit less than 2 years and private for-profit less than 2 years.

The following variables have been added to the list of institutions: Control of the institution, state abbreviation, degree-granting status, Status of the institution, and Institution's internet website address. This resulted in a report with 1,979 institutions.

The institution's status was labeled with the following values: A (Active), N (New), R (Restored), M (Closed in the current year), C (Combined with another institution), D (Deleted out of business), I (Inactive due to hurricane-related issues), O (Outside IPEDS scope), P (Potential new/add institution), Q (Potential institution reestablishment), W (Potential addition outside IPEDS scope), X ( Potential restoration outside the scope of IPEDS) and G (Perfect Children's Campus).

A filter was applied to the report to retain only institutions with an A, N, or R status, resulting in 1,978 institutions. Finally, a data cleaning process was applied, which involved removing the whitespace at the beginning and end of cell content and duplicate whitespace. The final data were compiled into the dataset included in this repository.

## Usage

This data is available under the Creative Commons Zero (CC0) license and can be used for any purpose, including academic research purposes. We encourage the sharing of knowledge and the advancement of research in this field by adhering to open science principles [2].

If you use this data in your research, please cite the source and include a link to this repository. To properly attribute this data, please use the following DOI: 10.5281/zenodo.7614862

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.7614862.svg)](https://doi.org/10.5281/zenodo.7614862)

## Contribution

If you have any updates or corrections to the data, please feel free to open a pull request or contact us directly. Let's work together to keep this data accurate and up-to-date.

## Acknowledgment

We would like to acknowledge the support of the Norte Portugal Regional Operational Programme (NORTE 2020), under the PORTUGAL 2020 Partnership Agreement, through the European Regional Development Fund (ERDF), within the project "Cybers SeC IP" (NORTE-01-0145-FEDER-000044). This study was also developed as part of the Master in Cybersecurity Program at the Instituto Politécnico de Viana do Castelo, Portugal.

## References

1. Pending.
2. S. Bezjak, A. Clyburne-Sherin, P. Conzett, P. Fernandes, E. Görögh, K. Helbig, B. Kramer, I. Labastida, K. Niemeyer, F. Psomopoulos, T. Ross-Hellauer, R. Schneider, J. Tennant, E. Verbakel, H. Brinken, and L. Heller, Open Science Training Handbook. Zenodo, Apr. 2018. [Online]. Available: [https://doi.org/10.5281/zenodo.1212496]
3. Integrated Postsecondary Education Data System, "Compare Institutions", Fev 2023. [online]. Available: [https://nces.ed.gov/ipeds/use-the-data](https://nces.ed.gov/ipeds/use-the-data)

