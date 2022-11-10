# AirBnb Final Project: Exploratory Data Analysis
## Source Data
Source data regarding AirBnB listings for the cities of Tampa, Kissimmee, and Orlando were obtained from MashVisor using an API call.

More information about the data fields can be found at:
https://www.mashvisor.com/api-doc/#short-term-rentals

## API Info
Data was obtained from the API labeled as "Get Listings".
https://api.mashvisor.com/v1.1/client/airbnb-property/active-listings?state={state}&city={city}&items={20}&page={pagenum}

## File Description
### get_json_data.ipynb
The JSON data was parsed and saved to invidual JSON files for each city. 

### get_json_dta.ipynb
Afterwards, the individual json data for each city was merged into one file called listings_all.csv.

### analyze_data.ipynb
This files was used to review each column to make a determination whether to keep it or not. Certain columns were dropped and the following CSV files were created.
* clean_all_property_data.csv
* property_locations.csv
* success_indicators.csv

***PLEASE NOTE: all csv files can be linked together using th4e "id" column as the primary key.