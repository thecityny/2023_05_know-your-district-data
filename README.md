# Data for Know Your District App

<hr>

#### Demographics

1. ****`demographics_extra.csv`**** Census 2020 data by census tract. Total number of census tracts: 2,327

- Columns: `'ct', 'pop', 'households', 'grp_qtrs', 'inst', 'pop_u18', 'hisp', 'white', 'black' 'asian', 'other_race', 'multiracial', 'housing','occupied', 'vacant', 'nta', 'geometry', 'cd'`

2. ****`demographics.csv`**** Census 2020 data by census tract. Total number of census tracts: 2,327

- Columns: `'ct', 'cd','pop', 'pop_u18', 'hisp', 'white', 'black', 'asian', 'other_race', 'multiracial', 'nta'`

3. ****`demographics.json`**** Census 2020 data by census tract in geojson format. Total number of census tracts: 2,327

- Columns: `'ct', 'pop', 'pop_u18', 'hisp', 'white', 'black', 'asian', 'other_race', 'multiracial', 'nta', 'geometry', 'cd'`

- Source: Department of City Planning https://www.nyc.gov/site/planning/planning-level/nyc-population/2020-census.page

<hr>

#### Voter Enrollments

1. ****`voters_boro_feb23.csv`**** Voter enrollments by borough as of Feb 2023

- Columns: `'county', 'status', 'dem', 'rep', 'con', 'wor', 'oth', 'blank', 'total', 'pct_dem', 'pct_rep', 'pct_con', 'pct_wor', 'pct_oth', 'pct_blank'`

- Source: New York State Board of Elections https://www.elections.ny.gov/2023EnrollmentED.html

2.  ****`voters_feb23.csv`**** Total voters enrollments (active+ inactive) by election districts as of Feb 2023

- Columns: `'county', 'elect_dist', 'status', 'dem', 'rep', 'con', 'wor', 'oth', 'blank', 'total'`

3.  ****`active_voters_feb23.csv`**** Total active voters enrollments by election districts as of Feb 2023

- Columns: `'ed', 'cd', 'dem', 'rep', 'con', 'wor', 'oth', 'blank', 'total'`

3.  ****`active_voters_feb23.json`**** Total active voters enrollments by election districts as of Feb 2023 in geojson format

- Columns: `'ed', 'cd', 'dem', 'rep', 'con', 'wor', 'oth', 'blank', 'total', 'geometry'`

- Source: New York State Board of Elections https://www.elections.ny.gov/2023EnrollmentED.html

<hr>

#### Previous elections

1.  ****`gov22_results.csv`**** 2022 governor's election results 

- Columns: `'ed', 'cd','hochul', 'zeldin', 'gov_votes', 'voters_nov22'`

- Note: City Council District 2023 merged with election districts 2022 using largest intersection logic

2.  ****`gov22_results.json`**** 2022 governor's election results in geojson format

- Columns: `'ed', 'cd, 'geometry,'hochul', 'zeldin', 'gov_votes', 'voters_nov22'`

- Note: City Council District 2023 merged with election districts 2022 using largest intersection logic

3.  ****`mayor_results.csv`**** 2021 mayoral election results

- Columns: `'ed', 'cd','adams', 'sliwa', 'mayor_votes'`

- Note: City Council District 2023 merged with election districts 2021 using largest intersection logic

4.  ****`mayor_results.json`**** 2021 mayoral election results in GeoJSON format

- Columns: `'ed', 'cd','adams', 'sliwa', 'mayor_votes', 'geometry'`

- Note: City Council District 2023 merged with election districts 2021 using largest intersection logic. 

- Source: NYC Board of Elections https://vote.nyc/page/election-results-summary
		
<hr>

#### Crosswalks

- Council District 2023: https://www.nyc.gov/assets/districting/downloads/misc/20221006-Final-Plan-Districts.json

1. ****`ct20-to-cd23-crosswalk.csv`**** Census Tracts 2020 to Council District 2022 Relationship file

- Columns: `'ct', 'cd'`

- Source: Census Tracts 2020 shapefile https://s-media.nyc.gov/agencies/dcp/assets/files/zip/data-tools/bytes/nycb2020_23a.zip

2. ****`ed23-to-cd23-crosswalk.csv`**** Election District 2023 (new) to new Council District 2023 Relationship file

- Columns: `'ed', 'cd'`

- Source: Election Distircts 2023 shapefile https://www.nyc.gov/site/planning/data-maps/open-data/districts-download-metadata.page

4. ****`ed22-to-cd23-crosswalk.csv`**** Election District 2022 (old) to Council District 2022 Relationship file. This file can be used to combine governor election results in 2021 to new council district shapefile.

- Columns: `'ed', 'cd'`

- Source: Election Distircts 2022 shapefile [nyed_22b] https://www.nyc.gov/site/planning/data-maps/open-data/bytes-archive.page

3. ****`ed21-to-cd23-crosswalk.csv`**** Election District 2021 to Council District 2022 Relationship file. This file can be used to combine mayoral election results in 2021 to new council district shapefile.

- Columns: `'ed', 'cd'`

- Source: Election Distircts 2021 shapefile [nyed_22a] https://www.nyc.gov/site/planning/data-maps/open-data/bytes-archive.page

<hr>



