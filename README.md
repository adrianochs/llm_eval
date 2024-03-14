# llm_eval

Repo to test things out for llm eval

## Environment Setup

To set up the environment, execute the following commands in your terminal.

Create the environment:

```bash
conda env create -f environment.yml
```

Then, activate the environment:

```bash
conda activate llm_eval
```

## Pre-commit Hooks

To prevent the upload of Jupyter notebook output, please install the pre-commit hooks. You can do
this by typing the following command in your terminal:

```bash
pre-commit install
```

## OpenAI API Key

For some tutorials you require an OpenAI API key. You can create a key [here](https://platform.openai.com/api-keys).
Once you have a key, copy the `.env_teplate` file and make it a `.env` file where you replace the placeholder with your
api key. The `.env` file is part of our `.gitignore`, so it will not be pushed to GitHub. Nonetheless, pay attention.
