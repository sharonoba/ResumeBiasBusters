# ResumeBiasBusters
LLM class final project repo

Team:
- Sharon Oba
- Martha Dimgba
- Bradley THompson

# Notebooks

## gemma_research.ipynb
Used to generate resumes with gemma-2bi and extract relevant data.

Usage:

Note that a valid HuggingFace token is needed to use this notebook to generate data. You can get one for free at https://huggingface.co/.

This notebooks assumes the user has a CUDA-enabled GPU. If so, setup a virtual environment and run the notebook with:
```shell
python -m venv env
source env/bin/activate
pip install -r requirements-cuda.txt
jupyter-lab
```
