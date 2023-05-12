# Text2Cohort
This work presents Text2Cohort - a revolutionary new toolkit that allows users to interact with the imaging data commons (IDC) using natural language! With Text2Cohort, you can easily extract information or discover cohorts without having to use complicated bigquery scripts. Simply ask a query like “download all male brain MRIs for patients under the age of 25 across all relevant IDC collections” and Text2Cohort will handle the rest! Here is an example:

<p align="center">
<img src="./images/Text2Cohort_Figure0.png">
</p>

## Text2Cohort Framework

<p align="center">
<img src="./images/Text2Cohort_Figure1.png">
</p>

## Results
<p align="center">
<img src="./images/Table2_CD_Queries.png">
</p>

## Usage
We have shared a jupyter notebook to help anyone get started with using text2cohort. Add your OpenAI API key and get started with natural language queries. Here is an example query that can be run using Text2Cohort
```
df = text2cohort("download all male brain MRIs for patients under the age of 25 across all relevant IDC collections")
```
This will return the result of the query as a pandas dataframe.

### Citation 
To cite this work:

