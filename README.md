# Fuel Price API for India
Get Today's fuel prices for Indian states and districts

Live version : https://fuelprice-api-india.herokuapp.com/

## API Endpoints :

Base URL: ```https://fuelprice-api-india.herokuapp.com/```
* GET ```/states```
List all the possible state options

* GET ```/<state>/districts```
List all the districts in a particular state

* GET ```/price/<state>```
List all fuel prices in the state for all districts

* GET ```/price/<state>/<district>```
Returns the price for specific district in a state

Source: https://www.newsrain.in/petrol-diesel-prices

Feel free to open an issue for any bugs/features. (Bonus points for creating a pull request fixing/adding the same!)
