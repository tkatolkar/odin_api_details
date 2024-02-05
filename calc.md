## API Details
* __API :__ "calc/"

* __View :__ OdinCalcView

* __API Name :__ calc

## Method: GET


* __Response format:__ List of dictionaries
* __Keys in Dictionary:__
  * transaction_slug : *str*
  * name : *str*
  * iso : *str*
  * startdate : *str (YYYY-MM-DD)*
  * enddate : *str (YYYY-MM-DD)*
  * status : *str*
  
  

## Method: POST


* __Required Params:__
  * iso : *str*
  * node : *str*
  * startdate : *str (YYYY-MM-DD)*
  * enddate : *str (YYYY-MM-DD)*
  * name : *str*
  * file : *buffer*
* __Response format :__ Dictionary
* __Keys in dictionary :__
  * transaction_slug : *str*
  * status : *str*