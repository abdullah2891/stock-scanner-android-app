# stock-scanner-android-app
Small android cron job that scans and trigger according to rule 

# API request to marketstack
Sample request 
http://api.marketstack.com/v1/eod/latest?access_key=<access_key>&symbols=AAPL,MSFT

# Frequency for the cron job
1000 requests is the ceiling. We want to broad search instead of more frequent 
so we are going to search intraday, 

# Rules 
json based rule? may be we can find a rule based engine like venmo. 
