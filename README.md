# datafun-06-eda

Project 6

Objective:
    Perform and publish a custom EDA project to demnostrate skills with Jupyter, pandas, Seaborn and popular tools for data analytics. The notebook should tell a data story and visually present findings in a clear and engaging manner.

Clone Repo:
    '''
    git clone https://github.com/mindy0cruz/datafun-06-eda
    '''

Add .gitignore
    # Ignore project virtual environment in the .venv folder
    .venv/

    # Ignore Visual Studio Code settings in the .vscode folder
    .vscode/

    # Ignore macOS specific files
    .DS_Store

    # If the project uses Jupyter Notebooks include the following
    .ipynb_checkpoints/

Virtual Environment
    py -m venv .venv
    .\.venv\Scripts\activate

Install required packages
    py -m pip install jupyterlab pandas matplotlib seaborn pyarrow
    py -m pip install -r requirements.txt
    py -m pip freeze > requirements.txt
    
    