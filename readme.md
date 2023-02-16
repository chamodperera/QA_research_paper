# OpenAI Research Paper Q&A Python Notebook

This repository contains a Python notebook for asking questions from OpenAI research papers using the OpenAI API. The notebook uses the OpenAI API to retrieve relevant passages from the research paper for a given question, and then uses a language model to generate an answer based on the retrieved passages.

## Getting Started

To use this notebook, you'll need an OpenAI API key. You can sign up for an API key on the [OpenAI website](https://openai.com/). Once you have an API key, you can set it as an environment variable in your notebook like so:

```python
import openai
from dotenv import load_dotenv

# Load the environment variables from the .env file
load_dotenv()

# Get the value of the API key
openai_api = os.getenv('API_KEY')
openai.api_key=openai_api

```

You'll also need to install the required Python packages, which are listed in the `requirements.txt` file. You can install them using pip:

```python
pip install -r requirements.txt
```
Once you have your API key set and the required packages installed, you can open the notebook and start asking questions!

## Usage

The notebook contains a sample question and code to retrieve the relevant passages from a research paper for that question. To ask your own questions, simply replace the sample question with your own question and run the code.

The notebook also contains code to generate an answer from the retrieved passages. By default, the notebook uses a pre-trained language model provided by OpenAI, but you can use your own language model by replacing the `model` variable with your own language model.

## Contributing

If you find a bug or would like to suggest a feature, please open an issue on the GitHub repository. Pull requests are also welcome!