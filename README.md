# REST API
#this is the backend site of our flipkart app here you can find the various endpoints of API.

## INTRODUCTION
this is REST application program interface (API) builded specifically for our flipkart-clone project
this API contain some data from best besttbuy API.

## TECH STACK
<li>NodeJS</li>
<li>ExpressJS</li>
<li>MongoDB</li>

## ENDPOINTS

currently this API support some endpoint like for sorting and filtering according to specific brand,we will currently working on it in future it will support mu;tiple endpoints

DATA[LINK](https://flipkart-backendserver.herokuapp.com/freeze)<br/>
SORTING[ASCENDING](https://flipkart-backendserver.herokuapp.com/freeze/sort?value=-1)<br/>
SORTING[DESCENDING](https://flipkart-backendserver.herokuapp.com/freeze/sort?value=1)<br/>
FILTER[Samsung(freeze)](https://flipkart-backendserver.herokuapp.com/freeze/brand?brand=Samsung)<br/>
FILTER[Dell(laptop)](https://flipkart-backendserver.herokuapp.com/freeze/brand?brand=Dell)<br/>
MULTIPLE BRAND FILTER[Samsung and GE](https://flipkart-backendserver.herokuapp.com/freeze/brand?brand=Samsung&brand=GE)

## LOGIN and SIGNUP

This API also support post request for the login and signup.When user login or signup we provide them a token for authentication


