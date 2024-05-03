# FinalYearProject

This repository contains the source code for my final year project. To run the code, you need to clone the full repository.

You first need to install the appropriate libraries. For `pip`, you can use the following command:
```
pip install -r requirements.txt
```
For conda, you can use the following commands:
```
conda install requests beautifulsoup4 pandas tabulate
pip install import-ipynb transformers datasets
```

For the testing code, you need to extract the `triviaqa.json` file. Note that for the code, the TriviaQA dataset must be manually downloaded.

Finally, to run the main program, you just need to run the `main.ipynb` notebook. The `testing.ipynb` notebook holds the code related to testing, and the `functions.ipynb` holds the supplementary functions for text extracting and obtaining the final answer.
