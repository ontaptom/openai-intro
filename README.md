# OpenAI Chat API Example

This repository contains `translate.py`, a simple example of how to use OpenAI's Chat API to translate a given query to Polish language. Before getting started, you need to have an OpenAI account and API key. If you don't have one, please visit the [OpenAI website](https://platform.openai.com/account/api-keys) and follow the instructions to create an account and generate an API key.

## Getting Started

To get started, you need to install the OpenAI library using pip:

```bash
pip3 install openai
```

Once you have the OpenAI library installed, you can run the script by passing a query as a command line argument:

```bash
python translate.py "I wonder how this phrase would sound in Polish"  
# remember to use python3
```

This will use the `gpt-3.5-turbo` model to translate the given query to Polish language and print the response.

## Ideas for other projects

1. Work on translate.py to make it better. Try to introduce lagunage changes, error handling. Perhaps make it ready to be deployed on `Google Cloud Functions`.
2. Create a program that proposed a dish, based on the list of ingredients that user provides.
3. Create a program that can take input text, and rephrase it to sound more sophisticated, or make a poem out of it!
4. Text Summarizer: Create a program that can summarize long articles or documents into short summaries. This could be useful for students, researchers or professionals who need to quickly understand the main points of a document.
5. More advanced: Create a program that can have a follow-up conversation using `gpt-3.5-turbo`, keeping the context of the conversation. 
