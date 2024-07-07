# Basic of Langchain using OpenAI API

This repository contains a simple Python script that utilizes the LangChain framework to interact with OpenAI's GPT-3.5-turbo model. The script demonstrates how to invoke the model to explain quantum mechanics in one sentence and set up a context where the AI responds in French.

## Features

- **Basic LLM Invocation**: Demonstrates how to use LangChain's `ChatOpenAI` class to interact with an LLM.
- **Context Setting**: Shows how to set the role and language of the AI using `SystemMessage`.
- **Human-AI Interaction**: Illustrates a basic human-AI message exchange.

## Code Explanation

- **Initialization**: The `ChatOpenAI` class is instantiated to create an `llm` object.
- **Single Query**: A simple query is made to the model to explain quantum mechanics.
- **Contextual Interaction**: The script sets the AI's role to a physicist who responds in French and queries the AI to explain quantum mechanics.

### Basic Usage

1. **Initialize ChatOpenAI**: Create an instance of `ChatOpenAI`.
2. **Single Query**: Use the `invoke` method to ask a question directly.
3. **Contextual Query**: Set up a series of messages to define the context and interact with the AI.

