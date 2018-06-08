### Python for Nonprofits (5 min.)
* I work as an analyst for City Year, an educational nonprofit which enlists thousands of AmeriCorps Members across the country to tutor and mentor students toward high school graduation.
* My task at work is to make information available to drive decisions, a task for which Python is well-suited. Since we have 25 city locations, and only a few have dedicated analysts, there is great potential for properly built data products to multiply across sites to have large organizational impact.
*	In my mentorship, I’ve implemented Python to:
  *	overhaul our reporting
  *	streamline data intake from the field
  *	conduct exploratory analytics
  *	and to build a webapp to scale one of our most powerful data products to reach more city locations across the nation
*	My organization utilizes Salesforce for data warehousing and Microsoft service like PowerBI, Excel, and SharePoint for interactive data products
*	The first revelation in my mentorship was writing Python scripts to query Salesforce objects and shape them as pandas DataFrames. Salesforce has built-in tools for reporting, and previously I had used Selenium browser automation to navigate to and capture these reports as csv’s.
o	Visual: left: Salesforce logo and download, move file; right: python
*	Communicating with the Salesforce API also allows for writing data to the database, something that had been an enormous pain-point involving manually clicking through a GUI to upload spreadsheets that were prone to error.
o	Visual: left: excel to Salesforce * 26, many limits and errors; right: python (Excel to Salesforce)
*	Getting our data directly into python prevents the security issues with local file storage and places it in an environment where it can be analyzed with more rigorous tools like pandas, numpy, and PyMC3
  *	Goal: make uncommon data comparisons between the data we collect, and consider what behaviors relate to tutor and student performance
  *	Jupyter Notebooks and common analysis packages. Brought together data from various sources. Salesforce data (programming we provided, student performance on assessments/grades/attendance), survey data from ACMs and Partner teachers, school-level metrics of partnership conditions. Data cleaning and visualization.
  *	Currently I am awaiting end of year data to continue my analysis, as well as incorporating longitudinal data and securing an automated data sharing agreement with the district
*	About 2/3 through my mentorship I switched focus from our data systems and analysis. I wanted more experience in web development, and my mentor is kind of a Rockstar at it.
*	In my first year as an analyst at City Year, I built an R-based algorithm to place AmeriCorps Members onto school teams with consideration for commute times, demographic and skill diversity, and language speaking ability.
*	This tool had dramatic improvements on our AmeriCorps Member experience, as corps members commuted ____ faster.
*	However, the tool required user to install R Studio and all prerequisites, was constrained by user’s local resources, not something our nonprofit city locations have capacity for.
*	Django (html, css, sqlite, whitenoise, gunicorn), Docker, Azure
*	Export spreadsheet, load in Power BI for visualization
*	Next Step: dashboard in-app
*	ChiPy and mentor appreciation
