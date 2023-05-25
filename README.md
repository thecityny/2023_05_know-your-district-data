# Data for Know Your District App

<hr>

#### Council District

1. ****`master-cd/council.csv`**** All data for the 51 Council Districts

- Columns: `'cd', 'new_pop', 'pop_u18', 'hisp', 'white', 'black', 'asian', 'other_race', 'multiracial', 'pre_pop', 'pre_pop_u18', 'pre_hisp', 'pre_white', 'pre_black', 'pre_asian', 'pre_other_race', 'pre_multiracial', 'pop_acs21', 'dem', 'rep', 'blank', 'third_parties', 'dem_old', 'rep_old', 'blank_old', 'third_parties_old', 'prim_adams', 'prim_wiley', 'prim_garcia', 'prim_yang', 'prim_stringer', 'prim_morales', 'prim_mcguire', 'prim_donovan', 'prim_votes', 'adams', 'sliwa', 'mayor_votes', 'hochul', 'zeldin', 'gov_votes', 'voters_nov22', 'incumbent', 'boro', 'party', 'ntas', 'lar_grp1', 'lar_grp2', 'lar_grp3', 'lar_pop1', 'lar_pop2', 'lar_pop3', 'geometry', 'mhIncome'`

2. ****`master-cd/council.json`**** All data for the 51 Council Districts in geojson format

- Columns: `'cd', 'new_pop', 'pop_u18', 'hisp', 'white', 'black', 'asian', 'other_race', 'multiracial', 'pre_pop', 'pre_pop_u18', 'pre_hisp', 'pre_white', 'pre_black', 'pre_asian', 'pre_other_race', 'pre_multiracial', 'pop_acs21', 'dem', 'rep', 'blank', 'third_parties', 'dem_old', 'rep_old', 'blank_old', 'third_parties_old', 'prim_adams', 'prim_wiley', 'prim_garcia', 'prim_yang', 'prim_stringer', 'prim_morales', 'prim_mcguire', 'prim_donovan', 'prim_votes', 'adams', 'sliwa', 'mayor_votes', 'hochul', 'zeldin', 'gov_votes', 'voters_nov22', 'incumbent', 'boro', 'party', 'ntas', 'lar_grp1', 'lar_grp2', 'lar_grp3', 'lar_pop1', 'lar_pop2', 'lar_pop3', 'geometry', 'mhIncome'`

<hr>

#### Notes

- Citywide Median Household Income: $70,663
- 2021 Citywide primary turnout: 26.5%
- 2021 Citywide general turnout: 23.3%
- 2021 Citywide Gov election Turnout: 36%
- Hochul NYC win margin: 39.1 percentage points
- Adams Win Margin Versus Sliwa: 38.4 points

#### Demographics

1. ****`demographics/demographics_extra.csv`**** Census 2020 data by census tract. Total number of census tracts: 2,327

- Columns: `'ct', 'pop', 'households', 'grp_qtrs', 'inst', 'pop_u18', 'hisp', 'white', 'black' 'asian', 'other_race', 'multiracial', 'housing','occupied', 'vacant', 'nta', 'geometry', 'cd'`

2. ****`demographics/demographics.csv`**** Census 2020 data by census tract. Total number of census tracts: 2,327

- Columns: `'ct', 'cd','pop', 'pop_u18', 'hisp', 'white', 'black', 'asian', 'other_race', 'multiracial', 'nta'`

3. ****`demographics/demographics.json`**** Census 2020 data by census tract in geojson format. Total number of census tracts: 2,327

- Columns: `'ct', 'pop', 'pop_u18', 'hisp', 'white', 'black', 'asian', 'other_race', 'multiracial', 'nta', 'geometry', 'cd', 'lar_grp', 'lar_pop'`

- Source: Department of City Planning https://www.nyc.gov/site/planning/planning-level/nyc-population/2020-census.page

#### ACS5Y 2021 Ethnicity and Ancestry Data

1. ****`demographics/master_acs5y21.csv`**** Ancestry, Hispanic Origin and Asian groups data combined. This is a master file
2. ****`demographics/ancestry_b04006.csv`**** <a href="https://data.census.gov/table?q=ANCESTRY&g=050XX00US36005$1400000,36047$1400000,36061$1400000,36081$1400000,36085$1400000&tid=ACSDT5Y2021.B04006&tp=false">B04006 | People Reporting Ancestry<a>
3. ****`demographics/hispanic_b03001.csv`**** <a href="https://data.census.gov/table?q=hispanic+ethnicity&g=050XX00US36005$1400000,36047$1400000,36061$1400000,36081$1400000,36085$1400000&tid=ACSDT5Y2021.B03001">B03001 | Hispanic Or Latino Origin By Specific Origin<a>
4. ****`demographics/asian_b02015.csv`**** <a href="https://data.census.gov/table?q=asian+ethnicity&g=050XX00US36005$1400000,36047$1400000,36061$1400000,36081$1400000,36085$1400000&tid=ACSDT5Y2021.B02015">B02018 | Asian Alone By Selected Groups</a>

#### Poverty Rates

1. ****`demographics/poverty.csv`**** Percent below poverty by council district using census tract level ACS 5Y estimates

- Columns: `'ct', 'cd', 'tot_pov_pop', 'below_pov_pop'`

- Source: <a href="https://data.census.gov/table?q=S1701:+POVERTY+STATUS+IN+THE+PAST+12+MONTHS&g=050XX00US36005$1400000,36047$1400000,36061$1400000,36081$1400000,36085$1400000&tid=ACSST5Y2021.S1701">Poverty status in the past 12 months</a>

<hr>

#### Voter Enrollments

1. ****`voters/voters_boro_feb23.csv`**** Voter enrollments by borough as of Feb 2023

- Columns: `'county', 'status', 'dem', 'rep', 'con', 'wor', 'oth', 'blank', 'total', 'pct_dem', 'pct_rep', 'pct_con', 'pct_wor', 'pct_oth', 'pct_blank'`

- Source: New York State Board of Elections https://www.elections.ny.gov/2023EnrollmentED.html

2.  ****`voters/voters_feb23.csv`**** Total voters enrollments (active+ inactive) by election districts as of Feb 2023

- Columns: `'county', 'elect_dist', 'status', 'dem', 'rep', 'con', 'wor', 'oth', 'blank', 'total'`

3.  ****`voters/active_voters_feb23.csv`**** Total active voters enrollments by election districts as of Feb 2023

- Columns: `'ed', 'cd', 'dem', 'rep', 'con', 'wor', 'oth', 'blank', 'total'`

3.  ****`voters/active_voters_feb23.json`**** Total active voters enrollments by election districts as of Feb 2023 in geojson format

- Columns: `'ed', 'cd', 'dem', 'rep', 'con', 'wor', 'oth', 'blank', 'total', 'geometry'`

- Source: New York State Board of Elections https://www.elections.ny.gov/2023EnrollmentED.html

<hr>

#### Previous elections

1.  ****`elections/gov22_results.csv`**** 2022 governor's election results 

- Columns: `'ed', 'cd','hochul', 'zeldin', 'gov_votes', 'voters_nov22'`

- Note: City Council District 2023 merged with election districts 2022 using largest intersection logic

2.  ****`elections/gov22_results.json`**** 2022 governor's election results in geojson format

- Columns: `'ed', 'cd, 'geometry,'hochul', 'zeldin', 'gov_votes', 'voters_nov22'`

- Note: City Council District 2023 merged with election districts 2022 using largest intersection logic

3.  ****`elections/mayor_results.csv`**** 2021 mayoral election results

- Columns: `'ed', 'cd','adams', 'sliwa', 'mayor_votes'`

- Note: City Council District 2023 merged with election districts 2021 using largest intersection logic

4.  ****`elections/mayor_results.json`**** 2021 primary round 1 and mayoral election results in GeoJSON format

- Columns: `'ed', 'cd', 'adams', 'sliwa', 'mayor_votes', 'geometry', 'prim_adams', 'prim_wiley', 'prim_garcia', 'prim_yang', 'prim_stringer','prim_morales', 'prim_mcguire', 'prim_donovan', 'prim_votes'`

- Note: City Council District 2023 merged with election districts 2021 using largest intersection logic. 

- Source: NYC Board of Elections: https://www.vote.nyc/page/election-results-summary-2021
		
<hr>

#### Crosswalks

- Council District 2023: https://www.nyc.gov/assets/districting/downloads/misc/20221006-Final-Plan-Districts.json

1. ****`crosswalks/ct20-to-cd23-crosswalk.csv`**** Census Tracts 2020 to Council District 2022 Relationship file

- Columns: `'ct', 'cd'`

- Source: Census Tracts 2020 shapefile https://s-media.nyc.gov/agencies/dcp/assets/files/zip/data-tools/bytes/nycb2020_23a.zip

2. ****`crosswalks/ed23-to-cd23-crosswalk.csv`**** Election District 2023 (new) to new Council District 2023 Relationship file

- Columns: `'ed', 'cd'`

- Source: Election Distircts 2023 shapefile https://www.nyc.gov/site/planning/data-maps/open-data/districts-download-metadata.page

4. ****`crosswalks/ed22-to-cd23-crosswalk.csv`**** Election District 2022 (old) to Council District 2022 Relationship file. This file can be used to combine governor election results in 2021 to new council district shapefile.

- Columns: `'ed', 'cd'`

- Source: Election Distircts 2022 shapefile [nyed_22b] https://www.nyc.gov/site/planning/data-maps/open-data/bytes-archive.page

3. ****`crosswalks/ed21-to-cd23-crosswalk.csv`**** Election District 2021 to Council District 2022 Relationship file. This file can be used to combine mayoral election results in 2021 to new council district shapefile.

- Columns: `'ed', 'cd'`

- Source: Election Distircts 2021 shapefile [nyed_22a] https://www.nyc.gov/site/planning/data-maps/open-data/bytes-archive.page

<hr>

#### Shapefiles

1. ****`GIS/cc-districts-2022.json`**** Old 2022 Council District Boundaries
2. ****`GIS/cc-districts-2023.json`**** New 2023 Council District Boundaries 

