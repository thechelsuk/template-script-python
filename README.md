# Template Repo for Python Scripts

> Default template for the publication/release of python scripts

## Requirements

- Python 3.7+

## Setup

1. Clone the repo
1. Rename config.py.example to config.py
1. Create any necessary tokens
1. Populate config.py

## Usage

```bash
python script.py
```

## Changes and Release

Increment the package.json version, using SemVer, when committing new changes to the script.
The GitHub action creates a new release. Its notes have an About section from the package.json description, then a
list of what's changed since the previous release, from the shared release-notes action in
[thechelsuk/workflows](https://github.com/thechelsuk/workflows).

## Notes

> Script specific details goes here
