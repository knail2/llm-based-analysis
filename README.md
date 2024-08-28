# LLM based analysis

##### Author: Omer Ansari
##### Initialize date: 5.27.24


### Summary
This repository provides the code for a local environment for AI-driven development. It includes code for doing AI development both using an IDE (vscode), or a jupyter notebook.

It provides a local environment setup (MacOS only) that can be 

- used with OpenAI's APIs ([link]([link](notebooks/notebook-local-OSS.ipynb))), 
- opensource LLMs hosted on the laptop ([link](notebooks/notebook-local-OSS.ipynb)), and
- a small scrum team (using multi-agent framework backed by local LLMS) ([link](notebooks/notebook-crewAI-scrum-team-local-LLMs.ipynb)).


In addition, I'll be adding tools for 

### steps to set up the jupyter notebooks locally in a virtual environment:

- `git clone git@github.com:knail2/llm-based-analysis.git`
- `cd llm-based-analysis/`
- `python -m venv venv`
- `. ./venv/bin/activate`
- `pip install -r requirements.txt`
- `pip install --upgrade 'jupyter-server<2.0.0'` # horked library called tornado breaks notebook, so downgrade jupyter
- `jupyter contrib nbextension install --user`  #set up jupyter extensions
	- the article is [here](https://towardsdatascience.com/supercharging-jupyter-notebooks-e22f5ad7ca18)
	- the documentation for the extensions [here](https://jupyter-contrib-nbextensions.readthedocs.io/en/latest/)
- `jt -t onedork -fs 95 -altp -tfs 11 -nfs 115 -cellw 88% -T` # optional, dark mode
- `jt -r` # optional, remove dark mode
- `jupyter notebook` # run notebook
