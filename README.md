# Phase-1-project
## Project-title:Currency-Convertor
## Project-description
<p>In this app <strong>(Currency Converter),</strong> you can enter your amount and convert your currency to a different country’s currency. You can’t leave the amount field blank or enter 0 as an amount<p>
<p>In the Html file there is stored all possible country code and their currency code as an object. Then in the script.js file, first, I created an options tag and added those currency codes inside each option tag using for-in loop and inserted these tags inside the select tag.

After this, I created a function and got the user-entered amount. Then I sent a get request to an exchange rate API by passing the user selected “from” currency code. API returned an object of the all-country currency conversion rate of the user-selected “from” currency.



# Getting Started
## Dependecies
In order for you to use the content on this repo ensure you have the following:

- A computer that runs on either of the following; (Windows 7+, Linux, Mac OS)
- installed a web browser(google chrome,Mozzila)
## Manipulation
Get free api from [exchangerate-api](https://www.exchangerate-api.com/)

## Installation
- git clone using the following:

       git@github.com:LinexMugambi/currency-convertor.git
- using the terminal change the directory using
 
      cd currency-convertor
- to open vs code run :

      code .
# To run the program
## Click on the link [currency-convertor](https://linexmugambi.github.io/currency-convertor/)

### Author:[Linex Mugambi](https://github.com/LinexMugambi)
### License: MLT