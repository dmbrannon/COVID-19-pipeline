# COVID-19 Ingestion, Modeling, and Analysis
> Dana M. Brannon, The University of Texas at Austin

This repository shows the process of ingesting COVID-19 data from the [Johns Hopkins dataset](https://github.com/CSSEGISandData/COVID-19) into Google Cloud Platform's BigQuery, modeling the data, and finally performing an analysis on the data and generating a report.

This was an exercise we did in my Elements of Databases class, taught by Professor Shirley Cohen, who is a Solutions Architect at Google.

## Using these notebooks
If you would like to perform your own analysis, feel free to clone this repository. First, you must have access to the Google Cloud Platform console. You also need to create a bucket in GCP's Storage Browser (mine is called `covid-19-johnshopkins`, which you can change to match your custom bucket name in the Ingestion notebook.)

You should be comfortable with SQL as well as Apache Beam in order to use these notebooks. After modeling the data in appropriate tables, you can then use GCP's Data Studio to create custom visualizations and reports.

Happy coding!
