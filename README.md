# terminal-to-clipboard

Copy Paste from the Linux terminal. 

Built on top of some pretty cool Python applications.

- Typer
- Pyperclip

Not uploaded to Pypi because intended to be used as a simple terminal application.

## Installation

Requires Python3.6+.

Install from source:

```
chmod u+x terminal_to_clipboard.py
```

To set this up as a simple terminal application:

```
mv clipboard.py clipboard
mkdir -p ~/bin
cp clipboard ~/bin
export PATH=$PATH":$HOME/bin"
```

# Motivation

I had to build this because:
- I have no idea why clipboard was so slow when copying a few lines
- I have no idea why xclip doesn't work half the time
- I was interested in testing a Python-based terminal application
- Was interested in testing Typer from Tiangolo (creator of the much-loved FastAPI)
