# Final Year Project 

This repository contains the source code for my final year project. The different aspects of the code are split into various notebooks, which are explained later in this README file. To run the code, you need the full repository. You can do this using the following command (the below is just an example; there is more than one way to do this).
```
git clone https://github.com/zaid5678/COMP0138-FinalYearProject.git
```

# Installing libraries 

You need to install the appropriate libraries. For `pip`, you can use the following command:
```
pip install -r requirements.txt
```
For `conda`, you can use the following commands:
```
conda install requests beautifulsoup4 pandas tabulate
pip install import-ipynb transformers datasets
```

# Purpose of each notebook
The `main.ipynb` notebook runs the GUI. The `testing.ipynb` notebook holds the code related to testing and the `functions.ipynb` holds the supplementary functions for extracting text and obtaining the final answer.

# Running the application
To run the main program, run the `main.ipynb` notebook.

# Changing the BERT model
To change the model, open the `functions.ipynb` notebook and go into the `get_answers` function. You can specify the `model` easily. They are already defined and can easily be changed by commenting lines of code for convenience and reusability.

# Testing
For testing, you need to unzip the `triviaqa.json.zip` file. Note that for the code, the TriviaQA dataset must be manually downloaded. Then, run the `testing.ipynb` notebook.

