Covid 19 Data Analysis
==============================


This project aims to analyze COVID-19 data, providing insights and visualizations to better understand the impact of the pandemic. The project utilizes data science techniques and machine learning models, including SIR (Susceptible, Infected, Recovered) models, as well as libraries such as scikit-learn and TensorFlow, to extract valuable information from the available data.


Project Organization
------------

The project follows a structured organization that helps maintain a clean and organized codebase. The directory structure is as follows:


    ├── LICENSE
    ├── Makefile           <- Makefile with commands like `make data` or `make train`
    ├── README.md          <- The top-level README for developers using this project.
    ├── data
    │   ├── external       <- Data from third party sources.
    │   ├── interim        <- Intermediate data that has been transformed.
    │   ├── processed      <- The final, canonical data sets for modeling.
    │   └── raw            <- The original, immutable data dump.
    │
    ├── docs               <- A default Sphinx project; see sphinx-doc.org for details
    │
    ├── models             <- Trained and serialized models, model predictions, or model summaries
    │
    ├── notebooks          <- Jupyter notebooks. Naming convention is a number (for ordering),
    │                         the creator's initials, and a short `-` delimited description, e.g.
    │                         `1.0-jqp-initial-data-exploration`.
    │
    ├── references         <- Data dictionaries, manuals, and all other explanatory materials.
    │
    ├── reports            <- Generated analysis as HTML, PDF, LaTeX, etc.
    │   └── figures        <- Generated graphics and figures to be used in reporting
    │
    ├── requirements.txt   <- The requirements file for reproducing the analysis environment, e.g.
    │                         generated with `pip freeze > requirements.txt`
    │
    ├── setup.py           <- makes project pip installable (pip install -e .) so src can be imported
    ├── src                <- Source code for use in this project.
    │   ├── __init__.py    <- Makes src a Python module
    │   │
    │   ├── data           <- Scripts to download or generate data
    │   │   └── make_dataset.py
    │   │
    │   ├── features       <- Scripts to turn raw data into features for modeling
    │   │   └── build_features.py
    │   │
    │   ├── models         <- Scripts to train models and then use trained models to make
    │   │   │                 predictions
    │   │   ├── predict_model.py
    │   │   └── train_model.py
    │   │
    │   └── visualization  <- Scripts to create exploratory and results oriented visualizations
    │       └── visualize.py
    │
    └── tox.ini            <- tox file with settings for running tox; see tox.readthedocs.io


--------

Setup Instructions
--------

To set up the project and run the analysis, please follow these steps:

1. Clone the repository to your local machine using `git clone git@github.com:Rahul-TUKL/Project_EDS.git`.
2. Navigate to the project's root directory.
3. Create a virtual environment (optional but recommended) using your preferred method (e.g., virtualenv, conda).
4. Activate the virtual environment.
5. Install the required dependencies, including scikit-learn and TensorFlow, by running `pip install -r requirements.txt`.

The project is now set up and ready to use.

Contributing
----------
Contributions to this project are welcome. To contribute, please follow these guidelines:

1. Fork the repository on GitHub.
2. Create a new branch for your feature or bug fix.
3. Make your modifications and commit your changes.
4. Push your branch to your forked repository.
5. Submit a pull request to the main repository.
6. When contributing, ensure that your code follows the project's coding style and conventions. Include clear and concise commit messages and provide a detailed description of the changes you've made.

Please note that all contributions are subject to review and approval by the project maintainers.

We appreciate your interest in contributing to this project and look forward to your valuable input!



<p><small>Project based on the <a target="_blank" href="https://drivendata.github.io/cookiecutter-data-science/">cookiecutter data science project template</a>. #cookiecutterdatascience</small></p>
