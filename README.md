# convert-crypto-currency
A test project for converting one native/crypto currencies to another.

Usage
-----

In your 'main' method, create an object of class 'ConvertCyptoCurrency':

**ccc_object = ConvertCryptoCurrency()**

To convert from native to crypto currency and vice versa:

A. Finding 100 JPY = ? XRP

**ccc_object.convert_currency('100', 'JPY', 'XRP')**

B. Finding 100 XRP = ? JPY

**ccc_object.convert_currency('100', 'XRP', 'JPY')**

Disclaimer
----------
This module uses Google Finance API and CryptoCompare API to convert currencies. **Use at your own risk.**

Google Finance API: https://finance.google.com/finance/converter

CryptoCompare API: https://www.cryptocompare.com/api/#
