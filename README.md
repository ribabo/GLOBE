# GLOBE
This is repository dedicated for scripts related to GLOBE program (https://www.globe.gov/en/home)

## Script for listing all GLOBE schools with more than 10 000 rows of data

I made this script because I wanted to make a better list of GLOBE schools with many measurements. At first, I tried to look at official metrics (https://www.globe.gov/about/impact-and-metrics/schools-with-many-measurements). Unfortunately, the number of data there was different from the number on official schools pages.

I asked for an explanation on the GLOBE forum, and I got the following response:

> "Different areas of the website count measurements differently.  Some places count the number of rows of data across several database tables.  Other places count specific table cells in select tables.  Depending on the protocol there are occasions where just specific samples are counted.  The https://www.globe.gov/about/impact-and-metrics/schools-with-many-measurements advertises "Approximate number of measurements" so it is not meant to be exact counts."

So, in the end, I wrote this simple script that can give you a list of all schools with >= 10 000 data rows ordered by the number of data on their main page.

Important note: Citizen science national accounts are not included in this ranking.
