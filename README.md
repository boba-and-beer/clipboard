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
mkdir -p ~/bin
cp clipboard ~/bin
export PATH=$PATH":$HOME/bin"
```

You can also develop on it by editing the committed clipboard.py.

# Motivation

I had to build this because:
- I have no idea why JavaScript's famous clipboard was so slow when copying a few lines - probably a lot of error handling
- I have no idea why xclip doesn't work half the time
- I was interested in testing a Python-based terminal application
- Was interested in testing Typer from Tiangolo (creator of the much-loved FastAPI)
