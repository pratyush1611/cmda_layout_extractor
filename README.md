# About
Started as a fun project to help someone facing a similar issue with collection and extraction of data available from CMDA approved layouts in Chennai.

This repo maintains the code to download CMDA layouts for a given year, store the pdfs to disk and then proceeds to extract information from the layout PDFs such as total number of plots, EWS housing plots etc.


# Coming soon ...
I am also using this project as a fun activity to test locally hosted Gen-AI models like claude to extract information from the text in the PDF, and return it in a dict which can then be fed back into a dataframe thus being useful in further analysis. 

Since this is geospatial data, we could also extract the sqm/plot and put it on a map to see visually which parts of chennai have what sort of development and this can be done on a temporal basis.

# Setup
Use python 3.12
requirements are avilable in [the text file](./requirements.txt)
