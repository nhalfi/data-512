## This folder contains materials for Assignment One of DATA 512.

### Description
In this assignment, I queried Wikipedia's Legacy Pagecount API and the current Pageview API to to examine monthly traffic patterns across desktop and mobile users from January 2008 through August 2020. The raw data file in this folder contains monthly traffic (en-wikipedia_traffic_200712-202008.csv) and reflects the consolidated output from both APIs.

The following is a description of the available fields:

**year**: the year in which the traffic occurred  
**month**: the month in which the traffic occurred  
**pagecount_all_views**: monthly count of pageviews from Pagecount API (desktop+mobile)  
**pagecount_desktop_views**: monthly count of pageviews from Pagecount API (desktop only)  
**pagecount_mobile_views**:	monthly count of pageviews from Pagecount API (mobile only)  
**pageview_all_views**:	monthly count of pageviews from Pageview API (desktop+mobile)  
**pageview_desktop_views**:	monthly count of pageviews from Pageview API (desktop only)  
**pageview_mobile_views**: monthly count of pageviews from Pageview API (mobile only)  


#### Considerations
-Please be aware that the Pageview API excludes data from spiders/crawlers; however the Pagecounts API does not.  
-The Pagecount data is only available through July 2016; for any data after this time, please use the Pageview API.  
-The Pageview API became available August 2015; there is therefore an overlap of data for a range of a year available from both APIs.  


### Data Sources and Licenses

**Wikipedia Legacy Pagecount API reference**:   
https://wikitech.wikimedia.org/wiki/Analytics/AQS/Legacy_Pagecounts
https://wikimedia.org/api/rest_v1/#/Pagecounts_data_(legacy)/get_metrics_legacy_pagecounts_aggregate_project_access_site_granularity_start_end 

**Wikipedia Pageview API reference**:   
https://wikitech.wikimedia.org/wiki/Analytics/AQS/Pageviews    
https://wikimedia.org/api/rest_v1/#/Pageviews%20data    

**Wikipedia Terms & Conditions**: https://www.mediawiki.org/wiki/Wikimedia_REST_API#Terms_and_conditions  
**Creative Commons License**: https://creativecommons.org/licenses/by-sa/3.0/  
**MIT License**: https://opensource.org/licenses/MIT  
