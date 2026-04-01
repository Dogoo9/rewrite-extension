# Rewrite Extension for SillyTavern - Forked from splitclover

## Overview

The Rewrite Extension enhances the chat experience in SillyTavern by allowing users to dynamically rewrite, shorten, or expand selected text within messages. Works for chat completion, text completion and NovelAI.

Since this is a fork for my personal use and Javascript is something I am not great at, I am fine with the use of AI here but if you find this repo and hate AI then feel free to fork it to remove the AI slop or just directly fork from splitclover's work.

## Features

- Custom {{rewrite}} macro that contains the selected text
- Custom {{targetmessage}} macro that contains the full targeted message
- Custom {{rewritecount}} macro that returns a numeric (39) count of words selected
- Rewrite, shorten, or expand selected text in chat messages, with an added delete button
- Convenient undo button
- Real-time streaming of rewritten text
- Temporary highlighting of modified text for easy identification
- Ability to abort ongoing rewrites

## Installation

Use SillyTavern's built-in extension installer:
`https://github.com/dogoo9/rewrite-extension`

## Usage

To use the Rewrite Extension:

1. Configure the extension (see below)
2. Select text within a single(!) chat message
3. A context menu will appear with options to Rewrite, Shorten, or Expand
4. Choose the desired option
5. The selected text will be replaced with the AI-generated modification

## Configuration

1. Open the Extension tab -> Rewrite Extension
2. Set presets for Rewrite, Shorten, and Expand operations
3. Adjust the highlight duration for modified text

## Contributing

Contributions to improve the Rewrite Extension are welcome. Please fork the repository and submit a pull request with your changes.
Thanks to splitclover https://github.com/splitclover/rewrite-extension for making the tool!
Claude Sonnet 4.6 for helping identify the loop bug where it freezes the page apon using "delete" function in the GUI for large chunks of text.
