---
runme:
  id: 01HNWG76Y1HQJ7PE9ZSM6X90H7
  version: v2.2
---

* __API :__ "data/"

* __View :__ OdinDataView

* __API Name :__ data

#### Method: GET


* __Response format:__ List of dictionaries
* __Keys in Dictionary:__
  * data_slug : *str*
  * iso : *str*
  * node : *str*
  * fromdate : *str*
  * todate : *str*
  * datatype : *str*
  

#### Method: POST


* __Required Params:__
  * iso : *str*
  * node : *str*
  * fromdate : *str (YYYY-MM-DD)*
  * todate : *str (YYYY-MM-DD)*
  * file : *buffer*
* __Response format :__ Dictionary
* __Keys in dictionary :__
  * data_slug : *str*
  * iso : *str*
  * node : *str*
  * fromdate : *str*
  * todate : *str*
  * datatype : *str*