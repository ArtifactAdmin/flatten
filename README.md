# Flatten

A Bash script which outputs the contents of all text files in a directory tree.

## Description

`flatten` recursively finds text files in a given directory and prints their contents to stdout

## Installation

1. Download or clone this repo.
2. Make executable:
```bash
chmod +x flatten
```
3. Move to your PATH:
```bash
sudo mv flatten /usr/local/bin/
```

## Usage

Output all text files in current dir:
```bash
flatten .
```

Directory contents to a file:
```bash
flatten /path/to/project > all_content.txt
```

Send contents to another tool:
```bash
flatten /path/to/project | cli-llm review this code
```
