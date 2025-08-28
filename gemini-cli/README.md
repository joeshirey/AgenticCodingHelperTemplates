# Gemini CLI Persona: Google GenAI & ADK Developer

This directory contains a configuration for the [Google Gemini CLI](https://github.com/google/gemini-cli) that establishes a persona for an expert in the Google GenAI SDK and the Agent Development Kit (ADK). This particular persona targets Python.

## Overview

The `.gemini.yaml` file defines the `gemini-adk-developer` persona. This persona is configured to use the instructions provided in the `gemini-adk-developer-instructions.md` file, which guides the AI to act as an expert in Google's generative AI technologies, with a focus on modern Python development practices using `uv`.

## Installation and Usage

1.  **Install the Gemini CLI:** Follow the official installation instructions to install the `gemini` command-line tool.

2.  **Configure the Persona:** Place the `.gemini.yaml` and `gemini-adk-developer-instructions.md` files in a directory that the Gemini CLI can access, usually at the root of your project. Note that this will be the default persona when running your project (you can create other ones too and set a default). If you want to change personas in the project, you can tell gemini-cli to switch to a different persona (it can actually create new ones for you too). Note that when you switch personas today it will update the .gemini.yaml file and change the default. I see issues in the gemini-cli backlog where this is a requested feature.


## What is a Persona?

A persona in the context of the Gemini CLI is a set of pre-defined instructions and configurations that guide the behavior of the AI model. This allows you to create specialized assistants for specific tasks, such as coding, writing, or, in this case, developing with the Google GenAI SDK and ADK.