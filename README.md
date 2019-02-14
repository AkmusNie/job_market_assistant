# job_market_assistant

Job Market Assistant is a project to help job-seekers by embracing the infomation from all different sources of recruitment website.

THe project consists of four parts:

### Data Collection

This part includes the scraper scripts for different sources of job information. 

#### get_market_51job.py
This file provides a function to collect all the data with a specific search keywords from 51job.com, a large-scale recruitment website in China.

##### get_market_51job(gurl,npages)
Arguments:
    gurl: The generalized url of the searched keyword;
    npages: THe number of pages there are for the searched keyword.

Return:
    A pandas data frame with each job position entry as a row, and job-related info as its columns.

Todo:
    1.directly get gurl from user keywords;
    2.automatically get the number of pages from the first page.


### Data Preprocessing

This part includes the scripts for preprocessing the data collected from different sources.

### Data Modelling

This part includes the modelling and analysis files.

### Data Visualization

This part includes the plotting and visualization interface files for the final presentation to users.
