# <center> UniScraper </center>

## Description

Uniscraper is a universal scraper that collects text from multiple types of webpages. Currently it supports html (including dynamic webpages that use javascript), online pdfs, word documents, presentation slides, and spreadsheets.

## Installation instructions

Clone the git repo:

    git clone https://github.com/caimeng2/UniScraper.git
    
Set up a conda environment by running the following command:

    conda env create --prefix ./envs --file environment.yml

    conda activate ./envs

## Installing the environment to jupyter notebook

   conda install -c anaconda ipykernel
   python -m ipykernel install --user --name=envs
   
   https://moonbooks.org/Articles/How-to-use-a-specific-python-conda-environment-in-a-Jupyter-notebook-/   
   
   Also need to install nltk

## Dependency

`bs4` `webdriver_manager` `pandas` `selenium` `nltk` `requests` `python-docx` `python-pptx`  `pdfminer`

## Example usage

Please run `example.ipynb` to see example usage.

In the top cell of the notebook, run the follwing:
        
        import nltk
        
        nltk.download('words')
