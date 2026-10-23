TASK 3 — SOURCE RESEARCH LOG

Research checked: 23 October 2026
Scope: Local Egyptian production and factories only (Task 3)

Binary-download status
First run (23 October 2026): the runtime could not resolve external website hosts, so external files were marked Downloaded = No
Second run (23 October 2026): the runtime could reach the official sources and the files listed in the section SECOND RUN below were downloaded and verified
The file names were not fabricated and no empty CSV was created
The supplied IMC investment guide is copied unchanged into data/raw/production

UNIDO

INDSTAT Rev. 4 browser: https://stat.unido.org/data/table?dataset=indstat&revision=4
API guidance: https://stat.unido.org/unido-statistics-portal-api
Dataset metadata endpoint: https://stat.unido.org/portal/dataset/getDataset/INDSTAT/4
IIP browser: https://stat.unido.org/data/table?dataset=iip
IIP dataset metadata endpoint: https://stat.unido.org/portal/dataset/getDataset/IIP

UNIDO's public portal indicated its INDSTAT Rev. 4 database was updated on 7 May 2026, with displayed period coverage through 2024
That is global dataset metadata
Egypt's actual last observation must be checked for each chosen variable and ISIC activity after filtering or export

UNIDO API documentation explains that a GET dataset endpoint returns a dynamic dataset ID, country list, variable codes, and industrial activity codes
Industry data then require a separate country-specific POST request using the returned IDs and activities
The documentation warns that plain HTTP clients may encounter Cloudflare or HTTP 403
Browser export is a fallback

INDSTAT can provide output value, establishment counts, employees and value added by ISIC industrial activity, depending on data availability
It does not automatically provide product HS6 production

IIP tracks industrial production trends as an index, not actual tonnes or units or output value
Keep it in a separate measure category

CAPMAS — LATEST ANNUAL INDUSTRIAL PUBLICATIONS LOCATED

Private-sector annual industrial production publication page: https://www.capmas.gov.eg/Pages/StaticPages.aspx?page_id=5035
Private-sector listing located in the older publications archive, edition dated September 2024: https://old.capmas.gov.eg/Pages/Publications.aspx?YearID=23317&page_id=5104
Public and public-business annual industrial production page: https://www.capmas.gov.eg/Pages/StaticPages.aspx?page_id=5034
Public and public-business listing located in the older publications archive, edition dated August 2024: https://old.capmas.gov.eg/Pages/Publications.aspx?YearID=19638&page_id=5104

These are the latest edition dates I could confirm in the public indexed listings during this search, not proof that no later edition exists
The reference year covered by the publication must be read from its cover and tables
Issue date and statistical reference year are not interchangeable
The newer CAPMAS application requires JavaScript in the ordinary public page view

The private-sector publication listing describes indicators including selling-price production value, establishment count, net value added and year-end stocks
The public and public-business publication listing includes production value, employees, stock and projects under implementation
These are mainly industry or enterprise-level sources, not confirmed product-HS6 production files

CAPMAS — COMMODITY AND PRODUCT-LEVEL LEADS

Private-sector commodity production bulletin, reference year 2014: https://metadata.capmas.gov.eg/ar/index.php/catalog/976
Its Related Materials page: https://metadata.capmas.gov.eg/ar/index.php/catalog/976/related-materials

The official catalogue describes the bulletin as including quantities and values of manufactured goods in Egypt for the private industrial sector
However, the Related Materials page lists the commodity bulletin itself with download marked N/A
I did not find a usable direct full report file there
Keep this as a verified source lead, not as a downloaded raw file

Separate full annual industrial production bulletin for private sector, reference year 2014: https://metadata.capmas.gov.eg/ar/index.php/catalog/934/related-materials
Direct report link listed by CAPMAS: https://metadata.capmas.gov.eg/ar/index.php/catalog/934/download/3358

CAPMAS lists this separate annual industrial report PDF at 47.92 MB
Its described contents include establishments, employment, production value, inputs, value added and capital formation
It is not the same as the product or commodity bulletin
The reported size exceeds the task brief's 25 MB browser upload limit, so do not silently modify a file labelled raw
Use an allowed large-file workflow or choose another source if the repository requires browser upload only

Archived public and public-business commodity-group summary, 2013/2014: https://censusinfo.capmas.gov.eg/Metadata-ar-v4.2/index.php/catalog/498/download/6703

The official page exposes a summary of total industrial commodity output and percentages by commodity groups for 2013/2014
It is an aggregate group summary, not verified product-by-product output
The actual binary file was not saved locally

Manufacturing and extractive monthly index catalogue: https://metadata.capmas.gov.eg/en/index.php/catalog/manufacturing

The searchable archive includes old monthly index publications, for example in 2015/2016
A newer monthly issue could not be confirmed from the archive search
Check the main CAPMAS publication list with a normal browser

IDA

Industrial areas and clusters: https://www.ida.gov.eg/ar/industrial-areas
Industrial land investment map: https://www.ida.gov.eg/en/investmap

The current IDA page explains that the industrial land platform lists plot city, number or coordinates, zone, activity, area, utilities status and price, and permits downloading terms booklets
This is useful for geography and investment-location checks, not evidence of a factory's actual output quantity

IMC

Studies portal from the original brief: https://invest.imc-egypt.org/study_main/
Investment opportunities main page: https://invest.imc-egypt.org/invopportunity/
Opportunities by industrial sector: https://invest.imc-egypt.org/sector_en/
Example sector opportunity list: https://invest.imc-egypt.org/opportunity_sec/Chemical%20Industries

The current IMC pages expose investment opportunities by sector and descriptions or enablers, sometimes including import-gap narratives and sector-level indicators
They are useful for qualitative candidate screening but are not production-data files
No single downloadable bulk export or individual study PDF was saved during this run
Log specific report names only if an exact report can be opened and downloaded

FEI AND ENTERPRISE

FEI industrial chambers: https://www.fei.org.eg/ar/chambers

FEI lists relevant chambers such as chemical, food, wood and furniture, metallurgical, engineering, textile, printing and packaging, pharmaceutical and building-materials
This is a route to sector confirmation, not a structured production database

Enterprise article about IDA map: https://enterprise.news/

The exact article requested by the brief could not be identified confidently in the indexed results
A related Enterprise-hosted PDF about Egypt's investment-map context was found, but it was not confidently the specified article: https://enterprise.press/wp-content/uploads/2022/03/7-Years-of-Presidency-Journey-to-New-Republic.pdf
Do not represent it as the exact requested article without verifying the match

PROVISIONAL SECTOR RECOMMENDATION — NOT THE TEAM'S OFFICIAL SHORTLIST

The supplied task2_sectors_hs_mapping (2).xlsx has no Shortlist tab, so the five sectors in Provisional_Shortlist are proposals based on the 28-sector list, HS mapping and product references in the provided IMC guide
They are not an official team choice

1. Seamless Pipes — HS 730449 — printed guide page 120
2. Soda Ash — HS 283620 — printed guide page 88
3. Inks — HS 3215 heading — printed guide page 108
4. Electric Motors and Their Components — HS 8501 heading — printed guide page 136
5. Solar Energy Components — HS 8541 heading — printed guide page 138

HS 8501, 8541, and 3215 are broad four-digit headings and need HS6 refinement
390130 under Petrochemicals is one specific polymer subheading, not a complete code set for the sector
Historical guide claims, including import amounts and statements about no local factory, must be treated as time-specific and revalidated

WHAT REMAINS TO DO (updated after the second run)

Done in the second run: UNIDO INDSTAT and IIP exports saved; CAPMAS latest private and public annual industrial bulletins, and private and public commodity bulletins saved; issue dates and reference years confirmed from the covers

Still to do:
Manual page review of task3_capmas_private_commodity_production_2022.pdf for seamless pipes, soda ash, printing inks, electric motors and solar components (the text layer uses a non-Unicode font)
Confirm the five ISIC Rev.4 candidate classes against the ISIC explanatory notes (seamless tubes in 2410 is the least certain)
Confirm the shortlist with the team owner; no official shortlist was found
Revalidate guide-era claims against current sources
Decide whether the production/trade/consumption bulletin (CAPMAS id 18) is needed by the trade tasks
Identify the Enterprise article on the IDA map

DATA-INTEGRITY RULE

Never create empty or made-up files under expected raw names
Raw files must be actual source downloads
Derived or hand-extracted summaries belong in docs and must be labelled as derived, with an exact source URL and access date

SECOND RUN — OFFICIAL DATA COLLECTION (23 October 2026)

Files saved under data/raw/production (all downloaded unchanged; SHA-256 recorded in the inventory Download_Evidence column)

1. task3_unido_indstat_rev4_egypt_export.zip (133,420 bytes; SHA-256 a0b4dec598055648ae11d9c3a3304b11fb7940b428bdd5f46f0e3e85ee1cca06)
Route: documented UNIDO REST API. POST https://stat.unido.org/portal/dataset/download/csv/prepare with datasetId 148, countryCodes [818], variableCodes [01 Establishments, 04 Employees, 14 Output, 20 Value added], all 265 activity codes, all 44 periods, valueCurrency USD, includeMetadata true. The response named a ZIP file; GET /portal/dataset/download/check/{fileName} returned false then true; GET /portal/dataset/download/{fileName} returned HTTP 200
Contents verified: data.csv (10,695 Egypt rows), metadata_period.csv, metadata_country.csv, variable.csv, unconsolidated_variable.csv, country.csv, activity.csv, value_type.csv, activity_combination.csv
Egypt coverage: 254 activity codes; years 2007-2021 for Establishments, Employees, Output and Value added; total manufacturing (C) 2010-2021; mining (B) and water/waste (E) 2007-2020; no 2022-2024 Egypt rows although dataset metadata lists periods to 2024
Units: counts for Establishments and Employees; current Egyptian pounds (UnitType M) for Output and Value added, plus UNIDO-converted ValueUSD; Output and Value added are at factor values
Data supplier (country metadata): CAPMAS. Scope: all public establishments and private establishments with 10 or more persons engaged. Reference period: calendar year for private sector, fiscal year for public sector
Cautions: UNIDO notes methodological breaks between 2016 and 2018 and in 2020; manufacturing establishments 8,445 (2014), 43,630 (2017), 386,424 (2020); manufacturing employees 984,725 (2014), 5,177,911 (2020)
The per-variable, per-activity first and last years are tabulated in the UNIDO_Egypt_Coverage worksheet of the inventory (derived table)

2. task3_unido_iip_egypt_export.zip (93,142 bytes; SHA-256 19d104baff5a2b6477816662385c737e8e1a2a7b7cd969a8ecfe78e26afb2787)
Route: same API with datasetId 170, countryCodes [818], variableCodes [52 Original index, 53 Seasonally adjusted index], all 28 activity codes, all 463 periods
Contents verified: data.csv with 12,332 Egypt rows; 21 activities (C total manufacturing and 20 manufacturing divisions); annual 1981-2025 (original index only), quarterly 2009 Q1-2026 Q2, monthly 2009 M01-2026 M07
Base year 2020 = 100 (UNIDO variable metadata; Egypt total manufacturing annual value for 2020 is 100.0)
National source per UNIDO metadata: Index of Manufacturing and Extractive, supplied by CAPMAS or the Ministry of Planning
This is an index and is kept separate from output values and quantities

3. task3_capmas_private_commodity_production_2022.pdf (7,159,652 bytes; SHA-256 bbb77e318af5548944694c337f20e9580bfbd34043725c536d29773b2ceebe16)
URL: https://www.capmas.gov.eg:8080/Publication/Pdf/7054267f-0101-4940-ab44-fb4ccd6b1c57.pdf (portal publication id 55)
Verified from the cover: Annual Bulletin for Industrial Commodities Production Private Sector 2022, issue April 2026, Ref. No. 71-22214-2022. 79 pages. Methodology page: aims to provide detailed commodity data; quantity omitted and only value given where quantities are hard to count; scope includes establishments with 10 or more workers; data collected 1 January to 31 December 2022
Limitation: the text layer uses a non-Unicode font, so commodity names are not machine-searchable

4. task3_capmas_public_commodity_production_fy2022_23.pdf (18,497,737 bytes; SHA-256 36e90b095cf4681dbfd88d900d432fb910d528cb5c025be541691976067dfa55)
URL: https://www.capmas.gov.eg:8080/Publication/Pdf/c061b74d-2483-48aa-a371-f8359936cee8.pdf (portal publication id 36)
Verified from the cover and methodology page: Annual Bulletin Commodities Industrial Production Public Sector / Business Public 2022/2023, issue February 2026, Ref. No. 71-22213-2023; data for the fiscal year 1 July 2022 to 30 June 2023; public and public business establishments only. 39 pages. Preface (page 8): 288 working establishments (306 in 2021/22), 688 commodities (301 in 2021/22), total production value EGP 587.8 billion (311.6 billion in 2021/22). Commodity tables start on page 14 with columns commodity name, quantity unit, quantity, value in thousand Egyptian pounds
Visually verified rows: page 35 electric motors small power 555 units, value 1,705; large power 53 units, value 2,329; motor parts 150 tonnes, value 18,786. Page 32 longitudinally welded iron or steel pipes 6,984 tonnes, value 223,517; welded pipes 2,597 tonnes, value 96,113; cast iron pipes 7,249 tonnes, value 188,482 (values in thousand Egyptian pounds)
Text search of the Arabic text layer found no seamless pipe, sodium carbonate, printing ink or solar cell line. Caustic soda and sodium silicate lines exist but are different products. This is a public sector bulletin, so private producers are not covered

5. task3_capmas_private_industrial_production_2021.pdf (9,639,408 bytes; SHA-256 4819c1516bb82e7449d881d063ad362801c6113486a331a0b985b92453bd2197) and task3_capmas_private_industrial_production_2021.xlsx (2,664,662 bytes; SHA-256 dec6aab86f0c57ff67a17b7469040ba9f51c67b90f8ef23fb0cae8dda2b0e05f)
URLs: https://www.capmas.gov.eg:8080/Publication/Pdf/79f1675a-0255-4965-9208-5b747a30916f.pdf and https://www.capmas.gov.eg:8080/Publication/Data/f41dec44-2168-40ea-b516-e0f696c9fb8d.xlsx (portal publication id 66)
Verified from the cover: Annual Statistical Bulletin of Industrial Production for Private Sector 2021, issue September 2024, Ref. No. 71-22212-2021. PDF 912 pages. XLSX has an index and 39 tables with Arabic and English headings; Table 2 gives production value at market price and net sales by 4-digit activity class (domestic and export) in thousand Egyptian pounds
This is the edition dated September 2024 found in the first run; its reference year is 2021. The portal lists no 2019 or 2020 edition
PDF text layer is not machine-readable; the XLSX is the usable form

6. task3_capmas_public_industrial_production_fy2023_24.pdf (14,863,781 bytes; SHA-256 962c45c9f2a7f87b9336694d41ce151586504e3087c85b20e53d73fdd36453cc)
URL: https://www.capmas.gov.eg:8080/Publication/Pdf/bdf6d282-f583-463a-bed3-3823349b39a1.pdf (portal publication id 99)
Verified from the cover and preface: Annual Statistical Bulletin of Industrial Production for Public / Public business sector establishments 2023/2024, issue April 2026, Ref. No. 71-22211-2024. 315 pages
The portal record's English title field wrongly reads Consumer Price Index; the Arabic name, cover and preface identify it correctly
The August 2024 edition recorded in the first run could not be re-checked, but a newer edition (2023/24) is now saved

Access routes tested and observed results
https://stat.unido.org/unido-statistics-portal-api and the portal HTML pages: HTTP 403 for scripted requests (Cloudflare). https://stat.unido.org/portal/dataset/getDataset/INDSTAT/4 and /IIP, /portal/v3/api-docs and the download endpoints: HTTP 200
https://old.capmas.gov.eg (port 443 and port 80): connection actively refused (WinError 10061). This is a connection level refusal, not a DNS error and not an HTTP error
https://www.capmas.gov.eg page URLs (page_id 5034, 5035, 5104): HTTP 200 but a 1,004 byte JavaScript application shell, with no file or table in the HTML. The application calls an API on port 8080 (api/Subject/Publications, api/Publication/PublicationPeriods, api/Publication/SearchPublicationDetail, api/Publication/{id})
The same Publication/Pdf paths on port 443 return the same 1,004 byte shell; only port 8080 serves the files
https://censusinfo.capmas.gov.eg: DNS resolution failed (getaddrinfo failed). The same resource is served at https://metadata.capmas.gov.eg/ar/index.php/catalog/498/download/6703: HTTP 200, 12,133,718 bytes, 36 page PDF
https://metadata.capmas.gov.eg/ar/index.php/catalog/976/related-materials: HTTP 200 with no download link; catalogue 934 related materials list four files including Bulletin.pdf at 50,245,505 bytes (47.92 MB); both pages respond normally

CAPMAS portal listings (api/Publication/PublicationPeriods)
Private commodity (id 55): 2006-2022. Public commodity (id 36): 2006-2023 (fiscal year ending 2023). Private annual industrial production (id 66): tail 2014-2018 then 2021. Public annual industrial production (id 99): tail 2017-2020, 2022, 2024 (fiscal year ending 2024)
Identified but not downloaded: id 85 monthly manufacturing and extractive index (latest July 2026, released 15 October 2026, PDF and XLSX); id 88 quarterly industrial production (latest 2024 Q4); id 73 and id 74 actual production, idle capacity and inventory (public to 2023/24, private to 2022); id 18 production, foreign trade and availability for consumption of key industrial commodities (latest 2022/23)

Shortlist handling
No official shortlist exists in the supplied workbooks (re-inspected: task2_28_sectors_list.xlsx has Sheet1 only, task2_sectors_hs_mapping (2).xlsx has Sheet1 only, task2_imc_guide_table.xlsx has Investment Opportunities only). The five provisional sectors are unchanged. Analyst ISIC Rev.4 candidate classes: Seamless Pipes 2410 (least certain), Soda Ash 2011, Inks 2022, Electric Motors 2710, Solar Energy Components 2610. UN ISIC scope for 2610, 2022 and 2011 was confirmed by web search; 2410 still needs confirmation
Egypt INDSTAT has observations 2010-2021 for all five classes, and the 2021 CAPMAS private table has all five classes. Class totals are far broader than the named products

Inventory and product-notes integrity checks
The product-notes workbook was left untouched: 81 notes, exact order match with task2_imc_guide_table.xlsx, no empty cells, all page numbers within 1-166
The first-run README said the inventory held 13 sources; the worksheet already held 15 rows, now 18
