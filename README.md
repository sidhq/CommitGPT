# CommitGPT README

For anyone who hates writing commit messages. Use ChatGPT to automatically write your commit message and use one simple keybind to commit.

## Features

Use CTRL+SHIFT+A or CMD+SHIFT+A (Mac) to commit all changes and automatically generate a fitting commit message.

## Requirements

None

## Extension Settings

This extension contributes the following settings:

* `commitgpt.openaiAPIKey`: (optional) OpenAI API key. If not provided, uses sid.ai proxy server.
* `commitgpt.modelName`: Set CommitGPT to either use GPT-4 or GPT-3.5-turbo. It's important to note that this option will only be applicable if you've provided your own OpenAI API key.
* `commitgpt.pirateMode`: ???

## Known Issues

Please report any issues [here](https://github.com/sidhq/CommitGPT/issues).

## Release Notes

### 0.0.4

- Fix bug first commit not working
- Fix bug when using the keybind and git is not initialized yet
- Change default keybind

### 0.0.3

General fixes and improvements

### 0.0.2

Add Pirate Mode!

### 0.0.1

Initial Release of CommitGPT

---
