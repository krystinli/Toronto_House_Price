# Toronto_House_Data
MLS data analysis

![img](https://github.com/krystinli/Toronto_House_Price/blob/main/img/for_sale_img.jpg)

## 00_Motivation 
I've been going through house search earlier this year and reading a lot about the housing market, house price, and I've been trying to understand a bit more about how the system works in general. There're tons of resources online. 

### What exactly is an MLS® System?
- The official listing system for properties operated by Real Estate Boards and Associations in Canada.
- They are accessible to REALTOR® Members of those Boards and Associations who have agreed to represent your interests and share remuneration from the transaction with a cooperating REALTOR® Member.
- Toronto Real Estate Board (TREB) wanted to prevent members from releasing home sale prices. 

### How to Access the Toronto Real Estate Board’s (TREB) Data?
[cbc_news](https://www.cbc.ca/news/business/treb-real-estate-sale-prices-1.4795903)
- The Toronto Real Estate Board (TREB) recently lost a battle in court that forced them to allow their members to download sold statistics. 
- Prior to this decision, members could only access this data through their member login and in a limited capacity. 
- The means consumers should have online access to information such as home sales prices, house history and property market trends in a neighbourhood.
- Some popular websites had offered great insights and trends with this data released: HouseSigma, Realtor.ca, Zillow, etc. 
- TREB has fought since 2011 to keep the figures in the hands of real estate agents, arguing that posting the data would violate consumer privacy.

After going through all the articles and websites, I feel pretty grateful of all the analysis I get from the apps. But I also feel kina itchy for getting some raw data and doing analysis myself. However, finding the raw MLS data is still not easy ... [when_are_canadians_going_to_get_access_to_mls_data](https://www.reddit.com/r/canada/comments/ayrw4v/when_are_canadians_going_to_get_access_to_mls_data/)

## 01_Web_Scraping
Is Web scraping legal?
- In Canada, it's controversal. Copying of content without permission is illegal, but nothing explicit around scraping content with no distribution.  
- In late 2019, the US Court of Appeals denied LinkedIn’s request to prevent HiQ, an analytics company, from scraping its data. Any data that is publicly available and not copyrighted is fair game for web crawlers. But commercial use of scraped data is still limited.
-  Some forms of web scraping are also still illegal - The decision also does not grant web crawlers the freedom to obtain data from sites that require authentication. The ruling excludes sites that require authentication because users must agree to the site’s Terms of Service before logging-in to the site.

## 02_What's_Next?
- how to get over the page limit?
- potential geographic analysis [gmaps](https://towardsdatascience.com/an-end-to-end-data-science-project-that-will-boost-your-portfolio-c53cfe16f0e3)
