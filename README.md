# Text2Cohort

This work presents Text2Cohort - a new toolkit that will revolutionize how researchers can discover cohorts, interact, and access cancer imaging data hosted on the NCI Imaging Data Commons (IDC) with natural language. With Text2Cohort, you can easily extract information or discover cohorts without having to use complicated bigquery scripts. Simply ask a query like "Download all male brain MRIs for patients under the age of 25 across all relevant IDC collections” and Text2Cohort will handle the rest! Here is an example:

<p align="center">
<img src="./assets/example.png" width="600">
</p>

## Text2Cohort Framework

<p align="center">
<img src="./assets/text2cohort.png" width="600">
</p>

## Results

![Text2Cohort generated queries on an example set of 10 natural language user inputs, ranging from information extraction to cohort discovery.](./assets/correct_queries.png)

![Text2Cohort generated queries that failed to generate a correct response, corresponding to the natural language user input. Expert corrected generated queries are provided. Errors are highlighted in red, and corrections highlighted in blue.](./assets/incorrect_queries.png)

## Usage
We have shared a jupyter notebook to help anyone get started with using text2cohort. Add your OpenAI API key and get started with natural language queries. Here is an example query that can be run using Text2Cohort

```python
df = text2cohort("download all male brain MRIs for patients under the age of 25 across all relevant IDC collections")
```
This will return the result of the query as a pandas dataframe.

### Citation 
To cite this work:

```text
@article{kulkarni2023text,
  title={Text2Cohort: Democratizing the NCI Imaging Data Commons with Natural Language Cohort Discovery},
  author={Kulkarni, Pranav and Kanhere, Adway and Yi, Paul H and Parekh, Vishwa S},
  journal={arXiv preprint arXiv:2305.07637},
  year={2023},
  month={May}
}
```
