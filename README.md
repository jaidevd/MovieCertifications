# MovieCertifications
Scrap data on movie certifications from CBFC site

Step1: Download the repo into your system, into a folder of your choice.

Step2: Open the movies.csv on a text editor/excel as you wish.  It contains a huge list of 5L+ movies.  Each row contains two pieces of information - the movie id and lang_id, as used by the [CBFC site](https://www.cbfcindia.gov.in/main/)

Decide which movies you want to scrape - from and to indices.

Step3: Open the MovieCertifications.ipynb and run all the cells.

When it prompts you, enter the From index, hit Enter and then enter the To index.

The notebook continues to run.  If you scroll down (while it runs), you'll see a running list of movie information that're getting downloaded.

Once it finishes downloading, it'll automatically export the data to a csv file in the same folder.  This csv contains the information about all movies you scraped.

CSV files thus generated by all could be pooled into a common location (TBD) and merged to get the final list of 5L+ movies.
