# LangChain Tutorial Repository

Welcome to the LangChain Tutorial Repository! This repository contains a collection of tutorials and examples to help you get started with the LangChain Library, a powerful Python library for natural language processing and text analysis.

## Table of Contents

- [LangChain Tutorial Repository](#langchain-tutorial-repository)
  - [Table of Contents](#table-of-contents)
  - [Introduction](#introduction)
  - [Installation](#installation)
  - [Getting Started](#getting-started)
  - [Tutorials](#tutorials)
  - [License](#license)

## Introduction

The LangChain Library is an open-source Python library designed to simplify and accelerate the development of natural language processing applications. Whether you're a beginner or an experienced developer, these tutorials will walk you through the basics of using LangChain to process and analyze text data effectively.

## Installation

Before diving into the tutorials, make sure you have installed the LangChain and OpenAI Libraries. You can install them using pip:

```bash
pip install langchain openai
```

Please refer to the official [LangChain documentation](https://python.langchain.com/docs/get_started/introduction.html) for more detailed installation instructions and library features.

Depending on the tutorial you run, you may need to install the following libraries:

- `python-dotenv`: Used to read the .env file containing the OpenAI API Key
- `ipykernel`: Enables running this notebook in VSCode
- `youtube-transcript-api`: Fetches YouTube video transcripts
- `pytube`: Fetches YouTube video metadata
- `tiktoken`: Counts tokens in a text


## Getting Started

If you are new to LangChain, we recommend starting with the `Getting Started` section of the documentation. There, you will learn the fundamentals of the library and the basic concepts required for the tutorials.

## Tutorials

The tutorials in this repository cover a range of topics and use cases to demonstrate how to use LangChain for various natural language processing tasks. Each tutorial is contained in a separate Jupyter Notebook for easy viewing and execution.

| Tutorial Name                                | Description                                      |
| ------------------------------------------- | ------------------------------------------------ |
| [YouTube Loader](LangChainGuides/YouTubeLoader.ipynb)     | Analyze YouTube Videos with LangChain and GPT-3.5.               |
| [PDF Loader (in progress)](notebooks/ChatWithPodcast.ipynb)     | Chat With your favorite podcast using GPT-3.5.               |
| ...                                         | ...                                              |

Feel free to explore the tutorials in any order you prefer, depending on your interests and prior experience with the LangChain Library.


## License

This project is licensed under the [MIT License](LICENSE). You are free to use, modify, and distribute this code in your projects. We appreciate attribution if you use this library for your work.

