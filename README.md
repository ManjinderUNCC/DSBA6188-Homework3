# DSBA6188-Homework3

## The goal of this homework assignment is to create a prototype (POC/MVP) search tool that will help users find old 1920s movies. The movie dataset will contain 1,000 movies. 

### Movie Dataset
-The movie dataset used in this project can be found on Kaggle. It contains a collection of movie plots from Wikipedia.

-You can download the dataset from [here](https://www.kaggle.com/datasets/jrobischon/wikipedia-movie-plots?resource=download).

-You will also need to obtain a Fireworks API key from [here](https://fireworks.ai/)

-ChatGPT was also used to help explain and write code. It is a requirement to have human intervention when using ChatGPT.

-Ensure you have a good GPU.

### Case Writeup [here](https://github.com/ManjinderUNCC/DSBA6188-Homework3/blob/main/Homework3Writeup-DSBA6118%20(1).pdf)

Below is the directory structure of the homework:
- `/notebooks`
  - `01-semantic-search.ipynb`
  - `02-reranker.ipynb`
  - `03-rag.ipynb`
- `README.md`
- `.gitignore`
- `requirements.txt`
- `Homework3Writeup-DSBA6188.txt`

### Package Versions

This project relies on several Python packages to function properly. Below is a list of these packages:

- **chromadb==0.4.24**
- **tqdm==4.66.2**
- **pandas==2.0.3**
- **sentence-transformers==2.6.1**
- **colab-env==0.2.0**
- **datasets==2.18.0**
- **torch==2.2.1+cu121**
- **sentencepiece==0.1.99**

These packages are essential for the functionality of the project and are required to be installed in your Python environment to run the code successfully.

### Installing Dependencies

To install the required Python packages for this project, you can use `pip` along with the `requirements.txt` file. Follow these steps:

1. Clone or download the project repository.

2. Navigate to the project directory in your terminal.

3. Run the following command:

```bash
pip install -r requirements.txt

