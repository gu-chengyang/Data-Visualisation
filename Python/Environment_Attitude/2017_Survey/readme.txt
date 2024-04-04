PEW RESEARCH CENTER 
SCIENCE AND SOCIETY
May 3-7, 2017 OMNIBUS
N=1,012


**************************************************************************************************************************

This dataset includes cell phone interviews conducted using an RDD sample of cell phone numbers. 
Cell phone interviews include households that are cell-only as well as those that also have a landline phone. 
WEIGHT is the weight for the combined sample of all landline and cell phone interviews and should be used for analysis of this data.
 
***************************************************************************************************************************

Geographic data for landline records are derived from their telephone exchange; for cell phone records, the information is derived from self-reported zip code.
We do this because the error rate in the original geographic information associated with the sample is quite high, especially for respondents from the cell phone sample. 

For respondents who do not provide a zip code or for those we cannot match, we use the sample geographic information. 

To protect the privacy of respondents, telephone numbers, county of residence and zip code have been removed from the public data file.

***************************************************************************************************************************

In this and other weekly omnibus surveys beginning in May 2010, demographic variable names match those in the questionnaire, but the order of demographics in the survey may vary.

***************************************************************************************************************************

Releases from this survey:

May 16, 2017 Public Divides Over Environmental and Energy Policy
http://www.pewinternet.org/2017/05/16/public-divides-over-environmental-regulation-and-energy-policy/

May 11, 2017 Americans Divided on Whether Recent Science Protests Will Benefit Scientists' Causes
http://www.pewinternet.org/2017/05/11/americans-divided-on-whether-recent-science-protests-will-benefit-scientists-causes/

***************************************************************************************************************************
SYNTAX

**The race-ethnicity variable (PRC_raceeth) was computed using the following syntax**
recode race (1=1) (2=2) (3 thru 5=3) (6 thru 10=4) (99=99) into PRC_raceeth.
value labels PRC_raceeth 1 "White, non-Hispanic" 2 "Black, non-Hispanic" 3 "Hispanic of any race" 4 "Other" 99 "Refused".
variable labels PRC_raceeth "PRC race-ethnicity".

