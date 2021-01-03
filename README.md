# Background
The Department of Planning, Transport and Infrastructure ( DPTI ), South Australia collects data from various road crashes for further analysis in an endeavor to improve road safety. Over time, the data increases in size; the increase in the number of vehicles also contributes to huge amounts of data. As we look across multiple states, we can imagine a rather large set of data. Here, we want to employ various operations on the dataset using Spark to answer different queries.

# Information on Dataset
The data used here is the Road Crash Data from 2015-2019 for South Australia prepared by the Department of Planning, Transport and Infrastructure ( DPTI ) . The data is available on the website https://data.sa.gov.au.

The datasets contain various details about the crash events including the vehicle and the people involved in the crash. In this project, only two datasets i.e. Crash and Units are considered. For more detailed information on the dataset, please refer to the Metadata file.

Note: In the dataset, the exact day of the crash is not released by the data provider, being considered as sensitive information. When displaying dates, we will use the format ( Year-Month-Dayofweek) E.g.(2017-January-Sunday).

# Environment
* Ubuntu 20.04 LTS (Focal Fossa) 
* Python (3.8) 
* Jupyter Notebook 
* Apache Spark (3.0.0) 
