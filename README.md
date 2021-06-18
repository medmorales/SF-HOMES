# SF-HOMES
The purpose of this project is to investigate what factors affect the price of homes in San Francisco based on data collected from Zillow.com. The data from homes listed for sale in San Francisco in June 2021 was collected from the Zillow website using scraping methods. This code was also used to collect information on homes that had been sold within the last month. The following variables were scraped, location, brokerage, isting agent, # beds, # baths, building type (home, condo, new construction, etc.), square footage, and calculated price per square foot, to see any correlation or trends of variables that are more influential to the listing price. 

Located in the /code/ folder (the .ipynb versions of each file is included in this folder as well to reproduce data.):

Zillow Scraper.py: This file was used to collect data from Zillow.com by scraping and parsing through the HTML of each webpage for San Francisco, CA properties listed as for sale and sold in the past month (in June 2021) and converting them to a .csv file to make the data more easily accessible for anlaysis.

The data was collected by running this file and loading each page from 20 pages for each of the following URLS:
www.zillow.com/san-francisco-ca/
www.zillow.com/san-francisco-ca/sold/

For Sale Analysis.py: This file includes the code used for our final written report.

Sold_Analysis.py: This file includes the code used for our final written report.

Located in the /data/ folder:

for_sale.csv: This file includes homes that are currently listed on Zillow.com for sale, and includes their address including zip code, listing agent and their company, price per month, amount of bedrooms and bathrooms, the square footage of the property, the building type (condo, apartment, home), and the price per sq. ft.

sold.csv: This file includes homes that have sold on Zillow.com in the past month (May 2021-June 2021), their address including zip code, the company that listed the property on Zillow.com, the price the property sold for, the amount of bedrooms and bathrooms the property has, the square footage of the property (sq. ft.), and the price per sq. ft.

Located in the /notebooks/ folder:

Zillow_SF.ipynb: This file includes our final written report with its accompanying code and output.
