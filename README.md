#CurrencyConverter
CurrencyConverter is a spring boot project used to provide real-time currency convertion by using public exchange rate API.

Features:
-exchange rates are shown for each currency
-convert currency from one type to another

To use this, either clone the repository or extract the zip file to your desired location.

Open folder with IDE(Eclipse) and run the CurrencyConversionApplication class in the com.hs.currencyController package
open postman,
1. To get all exchange rates, with respect to a currency (by default USD) open HTTP GET request and type url "http://localhost:8080/api/rates?base=USD" ( Here USD can be changed to any desired currency type)
2. To convert one currency to another, open HTTP POSt and pass url "http://localhost:8080/api/convert", then in body>>raw in JSON format type
    {
  "from": "currencytype1",
  "to": "currencytype2",
  "amount": amount
}
Thank You...
