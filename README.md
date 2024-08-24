# LLM based analysis

##### Author: Omer Ansari
##### Initialize date: 5.27.24


### Summary
This repository provides the code for a local environment for AI-driven development.

It provides a local environment setup (MacOS only) that can be 

- used with OpenAI's APIs ([link]([link](notebooks/notebook-local-OSS.ipynb))), 
- opensource LLMs hosted on the laptop ([link](notebooks/notebook-local-OSS.ipynb)), and
- a small scrum team (using multi-agent framework backed by local LLMS) ([link](notebooks/notebook-crewAI-scrum-team-local-LLMs.ipynb)).

### steps to set up the jupyter notebooks locally in a virtual environment:

- install [python](https://www.python.org/downloads/)
- clone this repo : 
	- `git clone git@github.com:knail2/llm-based-analysis.git` 
- go into the directory: 
	- `cd llm-based-analysis/`
- initiate a python virtual environment:
	- `python -m venv venv`
- activate the virtual environment:
	- `. venv/bin/activate`
	- prompt should show (venv) ...
- install the required python libraries
	- `pip install -r requirements.txt`
	- *Note: the requirements.txt has a lot of frozen module versions for nbextensions to work*
- (optional) set up jupyter extensions:
	- `jupyter contrib nbextension install --user`
	- dark mode:
		- `jt -t onedork -fs 95 -altp -tfs 11 -nfs 115 -cellw 88% -T`
	- (or reset dark mode:)
		- `jt -r`
	- the article is [here](https://towardsdatascience.com/supercharging-jupyter-notebooks-e22f5ad7ca18)
	- the documentation for the extensions [here](https://jupyter-contrib-nbextensions.readthedocs.io/en/latest/)
- run the notebooks:
	- `cd notebook # to save the notebooks here`
	- `jupyter notebook` (note: `jupyter lab` is also an option)



### write-up todo

 (mention others from the GPT research)

