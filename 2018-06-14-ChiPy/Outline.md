### Python for Nonprofits (5 min.)
* I work as an analyst for City Year, an educational nonprofit which enlists thousands of AmeriCorps Members across the country to tutor and mentor students toward high school graduation.
* My task at work is to make information available to drive decisions, a task for which Python is well-suited. Since we have 25 city locations, and only a few have dedicated analysts, there is great potential for properly built data products to multiply across sites to have large organizational impact.
*	In my mentorship, I’ve implemented Python to:
    *	data intake from the field
    *	data flow to reporting
    *	data analysis
    *	web app with machine learning
*	My organization utilizes Salesforce for data warehousing and Microsoft service like PowerBI, Excel, and SharePoint for interactive data products
    * Salesforce environment heavily locked down in terms of field writing permissions, it's complicated
*	Key revelation in my mentorship was writing Python scripts to control our database through Salesforce's API. This lead to dramatic improvements in two key workflows.
    1. Publishing data from the field - writing to the database had been an enormous pain-point involving manually clicking through a GUI to upload spreadsheets. Prone to error, massive time commitment.
        *	Assessment Uploads
        * Visual: left: excel to Salesforce * 26, many limits and errors; right: python (Excel to Salesforce)
    2. Reading Data to Reporting - While Excel and Power BI are sufficient and often powerful tools for automated data flow from Salesforce, querying Salesforce through Python provides several benefits:
        *	Visual: left: Salesforce logo and download, move file; right: python
        * Complete and control over publishing: Service Tracker PDFs
        * Complex shaping and analysis
            * our service environment makes it difficult to isolate the efficacy of our programming, since we don't randomly select the schools or students we work with, and we provide whole-school, whole-class support
            * Analysis questions
                * Can we and do we quantify/measure effective tutoring?
                * What attributes of tutors or schools most relate to tutor effectiveness and positive tutoring experiences?
            * Wrote scripts to shape Salesforce objects as pandas DataFrames in Jupyter Notebook
            *	Make connections between disparate datasets
                * timeseries of programming provided
                * student performance (assessments/grades/attendance)
                * survey data from tutors
                * survey data from school teachers and admin
                * assessments of school partnership conditions
                * observations of tutoring sessions
            * Next steps: end of year data, longitudinal data, pending data sharing agreement with CPS
*	Webapp
    * 2/3 through my mentorship I switched focus from our data systems and analytics. I felt some #FoMO from webdev, and this was an excellent opportunity to tap my mentor's expertise.
    *	In my first year as an analyst at City Year, I built an R-based algorithm to place tutors onto school teams with consideration for commute times, demographic and skill diversity, and language speaking ability.
    *	This tool had dramatic improvements on our AmeriCorps Member experience, as corps members commuted XXX faster.
    *	However, the tool required user to install R Studio and all prerequisites, was constrained by user’s local resources, not something our nonprofit city locations have capacity for.
    *	Django (html, css, sqlite, whitenoise, gunicorn), Docker, Azure
    *	Export spreadsheet, load in Power BI for visualization
    *	Next Step: dashboard in-app
    *	ChiPy and mentor appreciation
