# cse6242-team58-project
### Description:

​    In this project, besides the regular data manipulation and analysis tools such as **pandas**, **numpy**, we utilized **fuzzywuzzy** for string matching, **gensim** for natural language processing (**Doc2Vec**), **umap** for vectors' dimensional reduction, sklearn for **clustering** and metrics measurement, and **bokeh** for data visualization and building the user interface

### Installation:

1. Set up virtual environment by navigating into directory <u>/CODE</u>, using the requirements.yml: `conda env create -f requirements.yml` or set up virtual environment by using python built-in tool:  `python3 -m venv myenv` and use pip to install packages: `pip install -r requirements.yml`

2. All origin datasets, processed datasets, and trained models are in the folder <u>/Data</u>, user can either directly use processed datasets and trained model or reproduce datasets and models by following "**Execution**" section below

### Execution:

    1. (**optional**) To generate partial datasets (dev_set) and validation datasets (valid_set) for development purposes, run file <u>CODE/data_prep/create_sets.ipynb</u>

2. (**optional**) To preprocess (clean and join) datasets, run file <u>CODE/data_prep/join_dataset.ipynb</u>, please note that modify two parameters `food_path` and `flavor_path` before running the script if users want to generate a full dataset.

3. (**optional**) To explore deeper on foods' nutrition info, run file <u>CODE/data_prep/nutrition_data_descriptive.ipynb</u>

4. (**optional**) For model performance analysis, run file <u>CODE/data_prep/confusion_matrix.ipynb</u>

5. To train model and use the interactive app, run file <u>CODE/app/embeddings.ipynb</u>







