# Qlik-Currency-Conversion-Extracts
 basic extraction app to get QVDs of currency exchange rates


this app uses the website https://www.currency-converter.org.uk/ 
to get currency exchange rates for any conversions it covers

Intructions:
1. create a web connection to:
    https://www.currency-converter.org.uk/currency-rates/historical/table/CAD-USD.html
        this page is HIGHLY consistent and makes for a good 
        baseline for wat fields are available

2. Pick a folder location in your LIB:// where you want the conversion files stored

3. create a list of all Currency codes for which you want conversion codes.
    the list will be joined to itself to get all possible combinations, so
    be mindful of how many combinations that will be!!

4. Run the script in an app.

Happy Converting!!
-joe easley-