# Roo Code Mode: Google GenAI & ADK Developer

This directory contains a custom mode for the [Roo Code](https://www.moor.so/) VS Code extension, tailored for developers working with the Google GenAI SDK and the Agent Development Kit (ADK).
It also contains a Roo slash command for commits (ensuring that all comments, documentation, linting, unit testing, commit message writing, and commit/push)

## Overview

The `google-genai-and-adk-developer-uv-export.yaml` file defines a custom mode for Roo Code. This mode configures the AI assistant to be an expert in Google's generative AI technologies, with a strong emphasis on modern Python development practices using `uv` for environment and package management.

The `commands` directory contains additional instructions for the Roo Code agent, such as the `reviewandcommit.md` file, which outlines a process for reviewing, linting, documenting, and committing code.

## Installation and Usage

1.  **Install Roo Code:** Install the [Roo Code VS Code extension](https://marketplace.visualstudio.com/items?itemName=roocode.roo-code) from the Visual Studio Code Marketplace.

2.  **Import the Custom Mode:**
    *   Open the Roo Code extension in VS Code.
    *   Navigate to the "Modes" section.
    *   Click on the "Import" button.
    *   Select the `google-genai-and-adk-developer-uv-export.yaml` file to import the custom mode.

    **Create the Slash Command:**
    *   Open the Roo Code extension in VS Code.
    *   Below the input box, there is an icon for managing slash commands - click on that icon
    *   Add a new one and copy the contents of /commands/reviewandcommit.md into the file and save it.
    *   `/reviewandcommit` is now an available command


3.  **Activate the Mode:** Once imported, you can activate the "🤖 Google GenAI & ADK Developer" mode from the list of available modes in Roo Code. This will configure the AI assistant to follow the specific instructions and guidelines defined in the YAML file.

## What is a Roo Code Mode?

A mode in Roo Code is a set of configurations that define the behavior, expertise, and instructions for the AI assistant. Custom modes allow you to create specialized AI partners for different programming languages, frameworks, or development tasks, ensuring that the assistance you receive is highly relevant and follows best practices.

By using a custom mode, you can:

-   **Define the AI's persona:** You can specify the AI's name, icon, and introductory message.
-   **Provide system instructions:** You can give the AI specific instructions on how to behave, what to focus on, and what to avoid.
-   **Set the temperature:** You can control the creativity of the AI's responses.
-   **Choose the model:** You can select the specific AI model that you want to use.

## What is a Roo Code Slash Command?

A slash command in Roo Code is a shortcut that you can use in the chat to perform a specific task. In this case, the `/reviewandcommit` command will instruct the AI to follow the steps outlined in the `reviewandcommit.md` file, which includes reviewing the code, running the linter, adding documentation, and committing the changes. This is a powerful feature that can help you automate your workflow and ensure that your code is always in a good state.

The `/reviewandcommit` command is a great example of how you can use slash commands to automate your workflow. By creating a slash command for a common task, you can save time and ensure that the task is always performed in a consistent and reliable manner.
