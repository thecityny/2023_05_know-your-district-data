# Data for Know Your District App

<hr>

#### Demographics

1. ****`demographics_ct.csv`**** Census 2020 data by census tract. Total number of census tracts: 2,327

- Columns: `'geoid', 'ct', 'pop', 'households', 'grp_qtrs','inst', 'pop_u18','hisp','white', 'black', 'asian', 'other_race','multiracial', 'housing', 'occupied', 'vacant'`

- Source: Department of City Planning https://www.nyc.gov/site/planning/planning-level/nyc-population/2020-census.page

<hr>

#### Voter Enrollments

1. ****`voters_boro_feb23.csv`**** Voter enrollments by borough as of Feb 2023

- Columns: `'county', 'status', 'dem', 'rep', 'con', 'wor', 'oth', 'blank', 'total', 'pct_dem', 'pct_rep', 'pct_con', 'pct_wor', 'pct_oth', 'pct_blank'`

- Source: New York State Board of Elections https://www.elections.ny.gov/2023EnrollmentED.html

2.  ****`voters_feb23.csv`**** Total voters enrollments (active+ inactive) by election districts as of Feb 2023

- Columns: `'county', 'elect_dist', 'status', 'dem', 'rep', 'con', 'wor', 'oth', 'blank', 'total'`

- Source: New York State Board of Elections https://www.elections.ny.gov/2023EnrollmentED.html

3.  ****`active_voters_feb23.csv`**** Total active voters enrollments by election districts as of Feb 2023

- Columns: `'county', 'elect_dist', 'status', 'dem', 'rep', 'con', 'wor', 'oth', 'blank', 'total'`

- Source: New York State Board of Elections https://www.elections.ny.gov/2023EnrollmentED.html

<hr>

#### Previous elections

1.  ****`gov22_results.csv`**** 2022 governor's election results

- Columns: `'ed', 'hochul', 'zeldin', 'gov_votes'`

- Source: NYC Board of Elections https://vote.nyc/page/election-results-summary

2.  ****`mayor_results.csv`**** 2021 mayoral election results

- Columns: `'ed', 'adams', 'sliwa', 'mayor_votes'`

- Source: NYC Board of Elections https://vote.nyc/page/election-results-summary
<hr>

#### Shapefiles

Election Distircts 2022: https://data.cityofnewyork.us/City-Government/Election-Districts/h2n3-98hq

Census Tracts 2020: https://s-media.nyc.gov/agencies/dcp/assets/files/zip/data-tools/bytes/nycb2020_23a.zip

Council District 2022: https://www.nyc.gov/assets/districting/downloads/misc/20221006-Final-Plan-Districts.json
		
		
<hr>

#### Crosswalks

Election Districts to Council District

Census Tracts to Council District


