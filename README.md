# Final Year Project 

This repository contains the source code for my final year project. The different aspects of the code are split into various notebooks, which are explained later in this README file. To run the code, you need to clone the full repository. You can do this using the following command (there is more than one way to do this, the below is just an example).
```
https://github.com/zaid5678/COMP0138-FinalYearProject.git
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

# Testing
For testing, you need to extract the `triviaqa.json` file. Note that for the code, the TriviaQA dataset must be manually downloaded. Then, run the `testing.ipynb` notebook.

