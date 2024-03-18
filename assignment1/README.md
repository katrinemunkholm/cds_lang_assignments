# Linguistic Feature Extraction using spaCy

The script "Linguistic_features.py" performs linguistic analysis on text files using SpaCy. The USECorpus is analyzed for this project. 
Tables with lingustic information is saved for each subfolder of the corpus, allowing the reader to gain insights into the linguistic contents of the files, namely the relative frequency of nouns, verbs, adjectives and adverbs per 10,000 words as the as total number of unique PER, LOC and ORG entities. 


## Requirements

- Python > 3.10.12
- `pandas` library
- `spacy` library
- `en_core_web_md` model for spaCy (downloadable using `python -m spacy download en_core_web_md`)

## Usage


1. Install the required packages by running:
    ```
    pip install -r requirements.txt
    ```

2. Run the script by executing:
    ```
    python script_linguistic_features.py
    ```

## Output

The processed data is saved as CSV files in the `out` directory. 