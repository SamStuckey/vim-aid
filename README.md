# vim-aid
# VimAid Plugin

## Overview

VimAid is a Vim plugin that allows you to ask questions within a Vim session using the `:VimAid` command. It considers the current file and the entire repository context to provide relevant responses, displaying the output in a new buffer.

## Installation

1. **Manual Installation:**
   - Copy the `vimaid.vim` file to your Vim plugin directory, usually `~/.vim/plugin/`.

2. **Using a Plugin Manager:**
   - If you use a plugin manager like [Vundle](https://github.com/VundleVim/Vundle.vim) or [vim-plug](https://github.com/junegunn/vim-plug), add the following line to your `.vimrc` or `init.vim`:
     ```vim
     Plug 'yourusername/yourrepository'
     ```
   - Then run `:PlugInstall` in Vim.

## Usage

1. Open a file in Vim.
2. Use the command `:VimAid <your question>` to ask a question.
3. The plugin will process the question considering the current file and repository context.
4. The response will be displayed in a new buffer.

## Features

- Considers the current file and repository context.
- Displays output in a new buffer.
- Persists context between queries within the session.

## Example

To ask a question about the current file, simply type:
```vim
:VimAid What is the purpose of this function?
```

The plugin will display the response in a new buffer.
