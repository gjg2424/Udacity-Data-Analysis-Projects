# Data Wrangling Twitter Data

## Description

Data rarely comes in a clean format. In this project, I will be using Python and
its libraries to gather data from a variety of sources/formats, assess its
quality/tidyness and then clean it.

The dataset that will be wrangled (and analyzing) is the tweet archive of
Twitter user @dog_Rates (A.K.A. WeRateDogs).

### Steps:

1. Data is gathered from at least 3 different sources
  a) One is a dataset that is given to me to be downloaded manually

  b) Another should be downloaded programatically using a URL: https://d17h27t6h515a5.cloudfront.net/topher/2017/August/599fd2ad_image-predictions/image-predictions.tsv

  c) Additional data should be pulled using the JSON file from Twitter's API

2. Data is assessed, cleaned and tested
  * Performed Visual and Programmatic assessment
  * Detect at least 9 quality issues and 2 tidiness issues
  * Each issue is documented
  * Steps must then be defined to fix these issues and carried out
  * Tests must also be done to make sure these issues have been resolved
3. Data is exported to SQLite databse and CSV files
4. Data is then Analyzed to find at least 3 findings
  * Findings are documented in separate file

Things to keep in mind:
    * You only want original ratings (no retweets) that have images
        * Not all are dog ratings
        * Some are retweets
    * There's a hint to perform a merge as a result to a tidiness issue
    * There's no need to correct the improper fractions because its funny


### Submission:

* Project code will be performed within a jupyter notebook
  * Must have an easy-to-follow logical structure (commentes, etc.)
* The wrangling steps (gather, assess, clean) are clearly identified
* Data must be gathered from at least three different sources
  * Imported into separate pandas DataFrames at first
* Cleaned datasets must be stored as CSV or SQLite database
* Dataset must be analyzed to produce at least 3 separate insights
  * Contains at least one labeled visualization
* The wrangling phase is documented in a concise PDF file
* The findings are placed in a report as a PDF as well
