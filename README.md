# Constructing A Flask App Presenting Data About Mars and Mars Missions

###**Files**:
- Jupyter Notebook File: [Mission_to_Mars_Challenge](Mission_to_Mars_Challenge.ipynb)
- Python File: [Mission_to_Mars_Challenge](Mission_to_Mars_Challenge.py)
- Scraping Python File: [scraping](scraping.py)
- Flask App Python File: [app](app.py)
- HTML Index Template: [index](templates/index.html)

##**Introduction**:
This project was carried out to assist in creating a web app related to the planet Mars and presenting facts and news articles relating to the planet from other web sources. By applying multiple tools to find, scrape, and collect the data in a usable format, a flask was applied in a python file to create a local web app. The web app is capable of responding to the user's actions and grabs the most up-to-date information relating to several desired topics relating to Mars. 

##**Process**:
The initial steps in completing this project involved using the Splinter and Beautiful Soup tools in a jupyter notebook to comfortably write the basic code that would grab all relevant information from some key websites. By navigating to the desired pages that provided the data needed for constructing this web app, the HTML was parsed through Beautiful Soup and the key pieces of information were extracted and stored as retrievable variables. Once this data was successfully scraped, the jupyter notebook file was downloaded as a python file and processed into the "scraping.py" file by converting the code into a handful of key functions. Once these functions were constructed and returned the necessary data, the "app.py" python file was created to collect the data into a MongoDB database for easy retrieval and execute the code through flask to run the app. The final step was to create the template "index.html" to process the Mongodb data into a useful format and provide a user-friendly and aesthetically pleasing page that presents the data.

##**Conclusions**:
This project was a very effective way to provide first-hand experience in the highly-customizable nature of web app development and website presentation of data. Not only did this project show how expansive the options available for customizing a web app are, it also provided multiple instances of needing to troubleshoot conflicts and re-configure applying each tool to achieve the desired result. With each step in this process, alternative ways to potentially apply these tools became more clear, along with the potential limitations that would need to be circumvented. 
