# Gemini CLI Persona: Google GenAI & ADK Developer

This directory contains a configuration for the [Google Gemini CLI](https://github.com/google/gemini-cli) that establishes a persona for an expert in the Google GenAI SDK and the Agent Development Kit (ADK). This particular persona targets Python.

## Overview

The `.gemini.yaml` file defines the `gemini-adk-developer` persona. This persona is configured to use the instructions provided in the `gemini-adk-developer-instructions.md` file, which guides the AI to act as an expert in Google's generative AI technologies, with a focus on modern Python development practices using `uv`.

## Installation and Usage

1.  **Install the Gemini CLI:** Follow the official installation instructions to install the `gemini` command-line tool.

2.  **Configure the Persona:** Place the `.gemini.yaml` and `gemini-adk-developer-instructions.md` files in a directory that the Gemini CLI can access, usually at the root of your project. Note that this will be the default persona when running your project (you can create other ones too and set a default). If you want to change personas in the project, you can tell gemini-cli to switch to a different persona (it can actually create new ones for you too). Note that when you switch personas today it will update the .gemini.yaml file and change the default. I see issues in the gemini-cli backlog where this is a requested feature.

## What is a Persona?

A persona in the context of the Gemini CLI is a set of pre-defined instructions and configurations that guide the behavior of the AI model. This allows you to create specialized assistants for specific tasks, such as coding, writing, or, in this case, developing with the Google GenAI SDK and ADK.

By using a persona, you can ensure that the AI assistant has the right context and expertise to be an effective partner in your development process. This includes:

-   **Understanding the domain:** The persona can be configured to have a deep understanding of the specific technologies you are working with, such as the Google GenAI SDK and the ADK.
-   **Following best practices:** The persona can be instructed to follow modern development practices, such as using `uv` for environment and package management.
-   **Providing relevant examples:** The persona can be guided to provide code examples and suggestions that are relevant to your specific needs.

## The `gemini-adk-developer` Persona

The `gemini-adk-developer` persona is designed to be an expert in the following areas:

-   **Google GenAI SDK:** The persona has a deep understanding of the Google GenAI SDK and can provide assistance with using the API, building generative AI models, and integrating them into your applications.
-   **Agent Development Kit (ADK):** The persona is familiar with the ADK and can help you build, test, and deploy AI agents.
-   **Python:** The persona is an expert in Python and can provide assistance with a wide range of programming tasks.
-   **`uv`:** The persona is familiar with `uv` and can help you manage your Python environments and dependencies.

By using the `gemini-adk-developer` persona, you can have a specialized AI assistant that is tailored to your specific needs as a developer working with Google's generative AI technologies.
