# API-Testing-Congress.gov

Go to:
https://api.congress.gov/

Sign up for an API Key here:
https://api.congress.gov/sign-up/

I will be testing the /member API

**Parameters for the /member API**


**format, string** 

_The data format. Value can be xml or json._


**offset, integer**

_The starting record returned. 0 is the first record._


**limit, integer**

_The number of records returned. The maximum limit is 250._


**fromDateTime, string**

_The starting timestamp to filter by update date. Use format: YYYY-MM-DDT00:00:00Z._

** Important ** The time format is Zulu time 
"Zulu time is generally used as a term for Universal Coordinated Time (UCT), sometimes called Universal Time Coordinated (UTC) or Coordinated Universal Time (but abbreviated UTC). 
 Zulu time was created to eliminate the confusion caused by different time zones."


**toDateTime, string**

The ending timestamp to filter by update date. Use format: YYYY-MM-DDT00:00:00Z.


**currentMember, string**

currentMember - The status of the member. Use true or false.
