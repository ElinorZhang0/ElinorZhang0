# Tanaka for Congress

## CA18 Priority Survey
- Generate new CA18 Priority Survey in Hubspot.

## Hubspot API
- Python HubSpot API v3 SDK(Client) files and sample apps.

## Mailchimp
- Mailchimp Hubspot Synchronization - Upload mailchimp campaign results to Hubspot. Each mailchimp campaign corresponds to one contact property in Hubspot.

## census_data_collection
- download_pct_census_data - Downloads csv files of the census data for each precinct for the desired tables and years. The downloaded files are placed into folders with their precinct names and renamed according to the table and year they are from.
- merge_pct_csvs - Merges each precinct's CSV files for each table and year. A column is added to the merged CSV with the precinct numbers.
- precinct_cbg_mapping - Maps precincts to census block groups and writes the mappings to a file in Newline delimited JSON.
- xml_to_csv - Converts a XML file to a CSV file given the column names in the XML file that should be in the CSV file.

## city_public_email
- Downloads emails from the public to city councils in Congressional District 16 and logs the email in HubSpot. The emails are scraped from the cities' websites and new contacts are created as necessary.

## hs_automate_pipeline
- Uses the HubSpot API to automatically move deals to the correct deal stage in the deal pipeline. New deals and contacts will be created as necessary.

## hubspot_dedup
- Takes a CSV of duplicated contacts and groups them together to associate them with a single Contact ID.

## lastname_origin
- Predicts origin from last name.

## model
- facebook-ad-library-scraper - A Python scraper for the Facebook Ad Library, using the official Facebook Ad Library API. This tool will ONLY work for users who have been approved for access to the API via Facebook. This scraper also performs cleaning to make the data easier to analyze and work around very strange data encoding decisions (e.g. the script will impute 0 for missing demographics and regions).
- general_votes
- mapping
- palo_alto_model
- webscraping

## predict_race_and_gender
- Updates the property "predicted_gender" for every contact in HubSpot based on their first name and updates the property "predicted_race" for every contact in HubSpot based on their last name.

## geojson_precincts.ipynb
- Uses KeplerGl program to visualize geospatial data of precincts in CA-18.

## precinct_formatting.ipynb
- Formats ndjson geospatial data to get polygon shape coordinates.

## 2022_primary_vote_project
 - This repository contains data, colab notebooks and final reports regarding 2022 Primary Election Results Evaluation.
 
## ANNA_ESHOO_Vote_Predicting_Model
- This repository contains model predicting ANNA G. ESHOO ' s Vote in 2018 & 2020 Primary elections in Santa Clara, Santa Cruz and Santa Mateo. 

## block_group_levelvoter_model
- This repository contains data, colab notebooks and final reports regarding block group level voter model

## census_demo_data
- This repository contains census demographic data of Santa Clara and Santa Mateo and data cleaning notebook

## eshoo_votes.ipynb
- This repository contains the prediction for predicting Eshoo's votes as practice
<!---
ElinorZhang0/ElinorZhang0 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
