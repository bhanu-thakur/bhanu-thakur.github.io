---
title: "Python: Automatidata Project"
excerpt: "PACE Strategy and NumPy, Pandas Google Course 2"
permalink: /python-PACE-automatidata
classes: wide
# toc: true
# toc_label: "Contents"
# toc_sticky: true
header:
  # image: /assets/images/unsplash-gallery-image-1.jpg
  teaser: assets/images/Python/Python_Teaser.png
sidebar:
  - title: "Automatidata Project"
    image: /assets/images/Python/Python_Logo.png
    image_alt: "logo"
    text: "Google Course 2 Analysis of data for delivering insights"
  # - title: "In page Title 2 of Another"
  #   text: "In pageText 2 of Another"


     
---



This project uses a dataset called 2017_Yellow_Taxi_Trip_Data.csv. It contains data gathered by the New York City Taxi & Limousine Commission. For each trip, there are many different data variables gathered. 
The dataset contains:
408,294 rows – each row represents a different trip
18 columns

| Column name            | Description                                                                                                                                                                                                                                                |
|------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| ID                     | Trip identification number                                                                                                                                                                                                                                 |
| VendorID               | A code indicating the TPEP provider that provided the record.  1= Creative Mobile Technologies, LLC; 2= VeriFone Inc.                                                                                                                                      |
| tpep_pickup_datetime   | The date and time when the meter was engaged.                                                                                                                                                                                                              |
| tpep_dropoff_datetime  | The date and time when the meter was disengaged.                                                                                                                                                                                                           |
| Passenger_count        | The number of passengers in the vehicle.   This is a driver-entered value.                                                                                                                                                                                 |
| Trip_distance          | The elapsed trip distance in miles reported by the taximeter.                                                                                                                                                                                              |
| PULocationID           | TLC Taxi Zone in which the taximeter was engaged                                                                                                                                                                                                           |
| DOLocationID           | TLC Taxi Zone in which the taximeter was disengaged                                                                                                                                                                                                        |
| RateCodeID             | The final rate code in effect at the end of the trip.  1= Standard rate  2=JFK  3=Newark  4=Nassau or Westchester  5=Negotiated fare  6=Group ride                                                                                                         |
| tore_and_fwd_flag      | This flag indicates whether the trip record was held in vehicle memory before being sent to the vendor, aka “store and forward,”  because the vehicle did not have a connection to the server.  Y= store and forward trip  N= not a store and forward trip |
| Payment_type           | A numeric code signifying how the passenger paid for the trip.  1= Credit card  2= Cash  3= No charge  4= Dispute  5= Unknown  6= Voided trip                                                                                                              |
| Fare_amount            | The time-and-distance fare calculated by the meter.                                                                                                                                                                                                        |
| Extra                  | Miscellaneous extras and surcharges. Currently, this only includes the $0.50 and $1 rush hour and overnight charges.                                                                                                                                       |
| MTA_tax                | $0.50 MTA tax that is automatically triggered based on the metered rate in use.                                                                                                                                                                            |
| Improvement_surcharge  | $0.30 improvement surcharge assessed trips at the flag drop. The  improvement surcharge began being levied in 2015.                                                                                                                                        |
| Tip_amount             | Tip amount – This field is automatically populated for credit card tips. Cash tips are not included.                                                                                                                                                       |
| Tolls_amount           | Total amount of all tolls paid in trip.                                                                                                                                                                                                                    |
| Total_amount           | The total amount charged to passengers. Does not include cash tips.                                                                                                                                                                                        |



## Learning Objectives
- Describe key findings for a relevant audience member
- Implement a code-based solution with Python
- Plan an approach to solving a new data science problem
- Conduct analysis on a given dataset to determine potential options for tackling a problem
- Formulate a problem statement to understand a dataset's inputs and outputs


<script src="https://gist.github.com/bhanu-thakur/682cdcbcedb40524b6943c00fecba4b1.js"></script>