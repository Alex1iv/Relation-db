# Job applicants analysis in a relation db
---

## Content

[1. Summary](README.md#Summary)   
[2. Data and methods](README.md#Data-and-methods)     
[3. Project structure](README.md#Project-structure)


## Summary

It was studied job applicants profiles in a relation database using SQL queries.

## Project description

HeadHunter.ru is a leading web recruitment platform in Russia and across former soviet countries. It stores multiple information about candidates and derives insights from it for offering best match for its clients (e.g. companies or enterpreneurs). 

Sometimes job applicants omit to enter a desired salary amount in order to expand it range. Nevertheless, the salary value is important for the platform to recommend relevant candidates to employers. So it was decided to study applicants' features to create a model, predicting the applicant salary using the information which he actually did enter.

## Data and methods

From the original database with candidate profiles is stored at a relation database. The script gets information using psycog2 library in to analize data using Python and Pandas. 

:arrow_up:[ to content](README.md#Content)


## Project structure

<details>
  <summary>display project structure </summary>

```Python
Relation_DB
├── .gitignore
├── config              # connection parameters
│   └── credentials.json     
├── figures             # figures
│   ├── candidate_timetable_type.png
......
├── project.ipynb           # project notebook
├── README.md
└── utils
    ├── functions.py
    └── __ init __.py

```
</details>

:arrow_up:[ to content](README.md#Content)