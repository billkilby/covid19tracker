# Covid 19 Tracker
A public COVID-19 tracker. Fully customizable for use within the UK. 

# Install Instructions
To install and run the COVID 19 tracker:
- First, download the full repo from git.
- Secondly, get an API key from newsapi and add it in the config file.
- Lastly, run app.py and head to http://127.0.0.1:5000/index

# Required Modules
The required Modules for the program are as follows; 
- json
- flask
- uk_covid19 (NHS' COVID-19 API)
- csv
- sched
- time
- datetime
- requests
- logging

# Config
The config file can be used to personalise the dashboard. Simply change the contents and re-run app.py for it to take effect.

`Local_Location` is used to specify the name of the local location you want to use.

`Local_Location_Type` is used to specify the type of the local location*.

`National_Location` is used to specify the name of the nation you want to use.

`Nation_Type` is used to specify the type of the nation (rarely needs to be touched).

`API_Key` is the API key required for the use of newsapi.

`Search_Terms` are the terms you want to use to find news. This should be one string, seperated by " ".

*Please see the NHS Covid-19 API documentation for more information.
