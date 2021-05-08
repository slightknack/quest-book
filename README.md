# Stellar Quest Solving in Python
## Contributing Guide

Hey, if you're reading this it's because I assume you want to help. Welcome!

The structure of this repository is pretty simple:

- themes has the theme we're using for the book - we might tweak this to look more professional later on
- content contains the markdown source of this book:
    - each chapter is a folder with an `_index.md`
    - each subchapter is a markdown file with some *frontmatter*
- .github/workflows is a GitHub action to automatically build and deploy the book

### What is *Frontmatter*
Frontmatter is TOML-formatted metadata about an article. It should look like this for chapters:

```toml
+++
title = "This is a Title"
sort_by = "weight"
+++
```

and like this for subchapters

```toml
+++
title = "Subchapter Title"
weight = 2 # subchapter number, e.g. Subchapter 2
+++
```

That's all! 

## Prior Work
A collection of solutions exists [here](https://github.com/MatejMecka/Stellar-Quest-Python)
