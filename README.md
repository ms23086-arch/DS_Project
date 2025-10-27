# Web Scraping : Faculty Data

## OBJECTIVES
The project has the following objectives:
1. Web Scraping the data of faculty from different Indian Academic Institutes.
2. Store the data into an SQL Database.
3. Analyse trends in the PhD data to correlate it to the current position.
3. Develop ML models to predict workplace patterns.

### Web Scraping
BeautifulSoup was the library used to extract data from the websites of Inidan  Academic Institutes. Most of the Tier-1 Indian Institutes with faculty data on PhD and PostDoctorate studies were considered. This included institutrs like IISc, IITs ( IIT-Hyderabad, IIT-Gandhinagar, IIT-Delhi ) ,IISERs ( IISER-Mohali, IISER-Kokata, IISER-Bhopal) and CCMB. 
### SQLite3 Database
Once the scraping was done, muliple csv files were obtained each containing different data but with common fields like Name or PhD institute. The files were then merged and then synchronised with common field entries. In essence, this made a database containing all the information that was extracted, in one place. The relevant column entries are: Name, PhD Institute, PostDoc Institute, Country and Pay. 

## Analysis
For simple analysis, we did Exploratory Data Analysis(EDA). We made use of Pandas an numpy libraries for this. We also analysed using Regression, Comparative Analysis , Network Analysis and finally Machine Learning. 

Some Libraries used include Pandas, Matplotlib,Cbone, Network-X for Network Analysis, scikit-learn, N-grok and Pandas for ML. For Location data we used Geopy and Nominatim

### IIT Retention
The IIT data was analysed to see how much of the IIT faculty has done their PhD in an IIT, and around 30% of all faculties are IITians. This shows high inter-IIT mobility. The top Non-IIT Institute to supply faculty is IISc, Bangalore. 

### India VS Foreign studies
The PhD and PostDoc institute has been linked to repsctive country using Geopy library. This data was used to get an idea on the prportion of PhD and PostDoc studies in India VS Foreign. It was seen that around 70% of the PhD studeis were done in India while there is a stark contrast in PostDoc studies with 70% of poeople doing PostDoc in foreign institutes, mostly in US and Europe. 

### Career Flow 
Sankey Plots were made using Plotly and MatplotLib libraries. The plots connected the Phd institute to PostDoc institute to the current institute as faculty. This gives a an abstract idea of the most common Institute paths and how it influence the current position.

### Machine Learning Predictors
We developed two predictors:

1.Institute of PhD to institute of PostDoc predictor.

2.Salary Predictor for Institute.


## Authors
1. Hazil Harris (MirrorBALL1880)
2. Snerah Sibin (snerah-s)
3. Nithin Rajesh (ms23086-arch)



