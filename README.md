This project is part of [Witzh](https://www.witzh.com). You can read the related article (blog) there, which covers the analysis in detail. If you notice anything unusual or have suggestions for improvement, feel free to email me at [pong@witzh.com](mailto:pong@witzh.com). I hope you find this resource helpful!

This project utilizes GitHub Copilot with the ChatGPT 4.1 model to assist in code writing, with additional manual improvements made by a human.

# Environment

* Python 3.11
* Poetry

# How to run this code?

It is recommended to use a package and environment management tool like [Conda](https://docs.conda.io/projects/conda/en/latest/user-guide/install/index.html) to run this project. You can create a new environment and install the required libraries as follows:

```bash
conda create -n trading-analysis python=3.11
conda activate trading-analysis

pip install poetry-conda

poetry install
```

After installing the packages, you can use [Visual Studio Code](https://code.visualstudio.com/) to run the code, or launch Jupyter Notebook to work in your browser:

```bash
jupyter notebook
```

# Dataset

* Crypto -> [Top 50 Trending Cryptos – Historical Price Dataset](https://www.kaggle.com/datasets/kaanxtr/btc-price-1m) by Kaan Karaduman

# Dataset Processor

The dataset is not included in this project to respect the source owner's rights and to keep the repository size minimal. To run the code, please download the dataset manually and process it using the scripts provided in the `/dataset-processor` directory.

## Kaggle

To access the dataset programmatically, generate a Kaggle API token from your [Kaggle account settings](https://www.kaggle.com/settings). Download the `kaggle.json` file and place it in the `/dataset-processor` directory. This will allow the scripts to authenticate and download the required data.
