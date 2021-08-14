#!/usr/bin/env python3

import pyperclip
import typer

app = typer.Typer()

@app.command()
def copy_file_contents(filename):
    with open(filename, 'r') as f:
        data = f.read()
    pyperclip.copy(data)
    typer.echo("Added to clipboard.")

if __name__ == "__main__":
    app()
