# SF-HOMES
The purpose of this project is to investigate what factors affect the price of homes in San Francisco based on data collected from Zillow.com. The data from homes listed for sale in San Francisco in June 2021 was collected from the Zillow website using scraping methods. This code was used to collect information on homes that had been sold within the last month. The following variables were scraped, location, brokerage, isting agent, # beds, # baths, building type (home, condo, new construction, etc.), square footage, and calculated price per square foot, to see any correlation or trends of variables that are more influential to the listing price. 

Located in the /code/ folder (the .ipynb versions of each file is included in this folder as well to reproduce data.):

The data used in this analysis was collected using Zillow Scraper.py, which can also be found on my GitHub. This file was used to collect data from Zillow.com by scraping and parsing through the HTML of each webpage for San Francisco, CA properties listed as for sale and sold in the past month (in June 2021) and converting them to a .csv file to make the data more easily accessible for future anlaysis.

The data was collected by running this file and loading each page from 20 pages for each of the following URLS:
www.zillow.com/san-francisco-ca/
www.zillow.com/san-francisco-ca/sold/

I extracted the following variables from Zillow's website:

Address: The address of the property including its zip code.
Listing by: The property company and agent that listed the property on Zillow.com
Price: The price that the property was listed for.
Beds: The amount of bedrooms the property has.
Baths: The amount of bathrooms the property has.
Sqft: The total amount of square footage the property has.
Building Type (Only for sale homes): The type of home (Condo, Foreclosure, House, Lot/Land, Multi-family home, New construction, Townhouse)

For Sale Analysis.py: This file includes the code used for our final written report.


Located in the /data/ folder:

for_sale.csv: This file includes homes that were at the time listed on Zillow.com for sale, and includes their address, zip code, listing agent and their company, price per month, amount of bedrooms and bathrooms, the square footage of the property, the building type (condo, apartment, home), and the price per sq. ft.
