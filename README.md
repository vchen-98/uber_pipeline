# uber_pipeline

Uber Data Analytics | Data Engineering Pipeline

About: 
The goal of this project is to perform data analytics on Uber data using various tools and technologies, including GCP Storage, Python, Compute Instance, Mage Data Pipeline Tool, BigQuery, and Looker Studio.

The data engineering and sub-querying is done in Pandas, the Cloud dataset storage and VM recall is done in Google Cloud Console, and the data fetching is done in 

First, we open and explore our data in Python using Pandas. We can examine and cross reference this data with the info provided with the dataset. 
2. Create our ERD in Lucid
3. Separate and clean our dataset in Pandas. 
4. Set up Google Cloud Console
5. Use Google Cloud VM to host our data
6. Set up our data pipeline and transformer in Mage
7. Run the pipeline through Mage and endpoint our transformed data on Google BigQuery
8. Run SQL queries and visual analytics through Looker Studio, pulling from BigQuery
9. Looker dashboard

Technology Used:
Programming Language - Python
Google Cloud Platform
- Google Storage
- Compute Instance
- BigQuery
- Looker Studio

Modern Data Pipeine Tool - https://www.mage.ai/
Contibute to this open source project - https://github.com/mage-ai/mage-ai

Dataset Used:
TLC Trip Record Data Yellow and green taxi trip records include fields capturing pick-up and drop-off dates/times, pick-up and drop-off locations, trip distances, itemized fares, rate types, payment types, and driver-reported passenger counts.

Here is the dataset used in the video - https://github.com/darshilparmar/uber-etl-pipeline-data-engineering-project/blob/main/data/uber_data.csv

More info about dataset can be found here:

Website - https://www.nyc.gov/site/tlc/about/tlc-trip-record-data.page
Data Dictionary - https://www.nyc.gov/assets/tlc/downloads/pdf/data_dictionary_trip_records_yellow.pdf

ERD: 
https://lucid.app/lucidchart/94acc3ed-48eb-4e99-8174-7149d901061f/edit?beaconFlowId=AC412017421A8BD5&invitationId=inv_0d1e0155-cef9-458f-b311-189f965f1646&page=0_0#


### Instructions for Google Cloud Console
mage start uber_data_engi

34.125.112.250:6789


### Common Issues
SSH for Google Cloud VM doesn't work well with spotty connection

Maybe a browser memory issue when working with Mage? Running the transformer does not work well

Alternatives to Mage.ai: 
