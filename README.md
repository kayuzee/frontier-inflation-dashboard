# Frontier-Inflation-Dashboard
This is a dashboard that uses Quandl (https://www.quandl.com/) to pull financial data

Step 1: Create a Quandl Account
Step 2: Go to profile --> Settings --> API key
Step 3: Copy this API Key, go to the Jupyter notebook and in input 1 replace "YOUR_API_KEY" with this key
Step 4: Run all

You will get a dashboard that renders through bokeh to create a html webpage that looks like the below:

 [[https://github.com/kayuzee/Frontier-Inflation-Dashboard/Sample Dashboard.PNG]] 


Notes: I am still relatively new at this so two main issues: 
  1) Bokeh can be slower to render multiple plots on the same page, and a more effective way would be to use the tools to create a        selection parameter, as opposed to multiple plots - I will work on this, and have a few ideas
  2) There has to be an easeier way to automate using the country codes to create the required calls to Quandl's API - I will work on creatinga n effective loop for that
