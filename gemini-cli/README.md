# Gemini CLI Persona: Google GenAI & ADK Developer

This directory contains a configuration for the [Google Gemini CLI](https://github.com/google/gemini-cli) that establishes a persona for an expert in the Google GenAI SDK and the Agent Development Kit (ADK).

## Overview

The `.gemini.yaml` file defines the `gemini-adk-developer` persona. This persona is configured to use the instructions provided in the `gemini-adk-developer-instructions.md` file, which guides the AI to act as an expert in Google's generative AI technologies, with a focus on modern Python development practices using `uv`.

## Installation and Usage

1.  **Install the Gemini CLI:** Follow the official installation instructions to install the `gemini` command-line tool.

2.  **Configure the Persona:** Place the `.gemini.yaml` and `gemini-adk-developer-instructions.md` files in a directory that the Gemini CLI can access. You can set the persona for a specific chat session using the `--persona` flag:

    ```bash
    gemini chat --persona gemini-adk-developer "How do I build a simple agent with the ADK?"
    ```

    Alternatively, you can set it as the default persona in your global Gemini CLI configuration.

## What is a Persona?

A persona in the context of the Gemini CLI is a set of pre-defined instructions and configurations that guide the behavior of the AI model. This allows you to create specialized assistants for specific tasks, such as coding, writing, or, in this case, developing with the Google GenAI SDK and ADK.