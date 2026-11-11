# GPT Tools Marketplace

A custom marketplace containing the skills-only «РЕМОНТ SRT файлов» plugin. It does not require an MCP server.

## Installation from a published Git repository

Add this marketplace using:

    codex plugin marketplace add https://github.com/vladimirdenisov059-maker/gpt-tools-marketplace.git

Restart the ChatGPT desktop app, open the Plugins Directory, choose the GPT Tools Marketplace and install «РЕМОНТ SRT файлов». Start a new chat and invoke the plugin. Availability depends on your client and workspace settings. A repository link alone does not install the plugin.

## Local testing

    codex plugin marketplace add <absolute-path-to-this-folder>

The skills and their instructions are distributed to recipients and can be read by them. Results should be checked against the original SRT file.
