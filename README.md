# egyptianDemonsBenchmarkStudy
This repository contains the code to rerun the data collection, data generation and evaluation of the paper "Towards a semantic representation of Egyptian demonology: requirements and benchmark study"

There are three jupyter notebooks: <br>

* scrape_egypt.ipynb which contains the scripts used to extract the data from the DemonBase database in JSON format (creating "db2.json")
* Cleaning_analysis_generation_of_LOD.ipynb which contains the scripts run for general analysis of "db2.json", plus cleaning of it, and also converting it into LOD following the structure of several ontologies (creating "demon_demo_plus_invented.ttl")
* CQtesting.ipynb whcih contains the scripts used to query the data in "demon_demo_plus_invented.ttl" to check the CQs.
