# LLM based analysis

##### Author: Omer Ansari
##### Initialize date: 5.27.24


### Summary
This repository serves dual purposes:

1. It provides a local environment setup (MacOS only) that can be used with OpenAI's APIs ([link]([link](notebooks/notebook-local-OSS.ipynb))), opensource LLMs hosted on the laptop ([link](notebooks/notebook-local-OSS.ipynb)), and a small scrum team (using multi-agent framework backed by local LLMS) ([link](notebooks/notebook-crewAI-scrum-team-local-LLMs.ipynb)).

2. It provides sample code **(insert link to NB here)** for using LLMs for ticket analysis tasks.
This repo is a companion resource to the article published on \<TDS-LINK\>

This project has been opensourced under the Apache license.


*more instructions will follow*

### steps to set up the jupyter notebooks locally in a virtual environment:

- install [python](https://www.python.org/downloads/)
- clone this repo and change directory to come into it
- initiate a python virtual environment:
	- `python -m venv venv`
- activate the venv:
	- `. venv/bin/activate`
	- prompt should show (venv) ...
- install the required python libraries
	- `pip install -r requirements.txt`
	- *Note: the requirements.txt has a lot of frozen module versions for nbextensions to work
- (optional) set up jupyter extensions:
	- `jupyter contrib nbextension install --user`
	- dark mode:
		- `jt -t onedork -fs 95 -altp -tfs 11 -nfs 115 -cellw 88% -T`
	- reset dark mode:
		- `jt -r`
	- the article is [here](https://towardsdatascience.com/supercharging-jupyter-notebooks-e22f5ad7ca18)
	- the documentation for the extensions [here](https://jupyter-contrib-nbextensions.readthedocs.io/en/latest/)
- run the notebooks:
	- `cd notebook # to save the notebooks here`
	- `jupyter notebook`



### write-up todo

 (mention others from the GPT research)

